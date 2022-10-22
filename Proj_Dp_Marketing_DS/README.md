# Proj_Data_Science_Dp_Marketing
Examinar a base de dado e encontrar perfis de clientes(Agrupamento por características)

**Departamento de marketing

Base de Dados: https://www.kaggle.com/arjunbhasin2013/ccdata

Ações:
- Realizar Limpeza e tratamento dos dados
- Retirar colunas desnecessarias
- Examinar os dados
- Criar visualizações de gráficos
- Verificar correlações entre os dados

Libraries usadas:

- pandas
- numpy
- seaborn
- matplotlib.pyplot
- sklearn.preprocessing - (StandardScaler)
- sklearn.cluster - (KMeans)
- sklearn.decomposition - (PCA)
- tensorflow.keras.layers - (Input, Dense)
- tensorflow.keras.models - (Model)

Observações:
- Foi criado clusters de clientes com características semelhantes, e verificando esses grupos foram possíveis observar as seguintes informações.

- Grupo 1: (VIP/Prime): limite do cartão alto (15570) e o mais alto percentual de pagamento da fatura completa (0.47). Opção de ação para o Grupo: Aumentar o limite do cartão e o hábito de compras;

- Grupo 2: clientes que pagam poucos juros para o banco e são cuidadosos com seu dinheiro. Possui menos dinheiro na conta-corrente (104) e não sacam muito dinheiro do limite do cartão (302). 23% de pagamento da fatura completa do cartão de crédito.
Opção de ação para o Grupo: Criar campanhas para o uso do cartão de credito e uso do cartão para saques.

- Grupo 3: usam o cartão de crédito como "empréstimo" (setor mais lucrativo para o banco), possuem muito dinheiro na conta-corrente (5119) e sacam muito dinheiro do cartão de crédito (5246), compram pouco (0.3) e usam bastante o limite do cartão para saques (0.51). Pagam muito pouco a fatura completa (0.03);
Opção de ação para o Grupo: Criar campanhas de marketing para os clientes pagarem um percentual maior da fatura.

- Grupo 4: (clientes novos): clientes mais novos (7.23) e que mantém pouco dinheiro na conta-corrente (863);
Opção de ação para o Grupo: Influenciar clientes ao hábito de compras e saques com o cartão.**
