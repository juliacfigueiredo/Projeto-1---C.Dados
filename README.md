# Projeto-1---C.Dados


No nosso projeto, realizamos diversas etapas, dentre elas, a classificação manual de tweets relacionados ao produto Coca-Cola. Posteriormente, começamos pela limpeza do nosso DataFrame, removendo caractericas que julgamos necessárias, além do espaçamento entre palavras e emojis. Após isso, criamos tabelas relativas a partir de cada classificação (Relevante e Irrelevante). Com isso em mãos, fizemos duas equações para depois facilitar o processo de verificar a relevância de um deteminado tweet aleatório. A primeira equação foi a def probabilidade_conjunto, na qual tinhamos como objetivo descobrir a frequência de uma palavra dentro da tabela relativa da própia. Após isso, fizemos a suavização de Laplace através da função def laplace, afim de sanar possíveis erros de quando uma palavra que não aparece na nossa base de dados fosse implementada, dando assim, uma probabilidade muito pequena nessas ocasiões. A partir disso, realizamos uma classificação final (def verifica_relevancia), que incluia todos os passos descritos, retornando a partir da análise de cada palavra se aquele tweet recebido seria Relevante ou Irrelevante. 

Gustavo Borba e Julia Figueiredo
