# Projeto_Data_Science_Vendas
Objetivo prever as vendas futuras com base nos dados obtidos

Departamento de vendas

Base de dados: https://www.kaggle.com/c/rossmann-store-sales/data

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
- tensorflow

Observações:

# Detalhes do Data-Frame

Você recebe dados históricos de vendas de 1.115 lojas Rossmann. A tarefa é prever a coluna "Vendas" para o conjunto de teste. Observe que algumas lojas no conjunto de dados foram temporariamente fechadas para reforma.

# arquivos

train.csv - dados históricos, incluindo vendas
test.csv - dados históricos excluindo vendas
sample_submission.csv - um arquivo de envio de amostra no formato correto
store.csv - informações complementares sobre as lojas
Campos de dados
A maioria dos campos são autoexplicativos. A seguir estão as descrições para aqueles que não são.

# Colunas

Id - um Id que representa uma duplicata (Store, Date) dentro do conjunto de teste

Loja - um ID exclusivo para cada loja

Vendas - o volume de negócios para um determinado dia (é o que você está prevendo)

Clientes - o número de clientes em um determinado dia

Aberto - um indicador para saber se a loja estava aberta: 0 = fechado, 1 = aberto

StateHoliday - indica um feriado estadual. Normalmente todas as lojas, com poucas exceções, estão fechadas nos feriados estaduais. Observe que todas as 
escolas estão fechadas nos feriados e fins de semana. a = feriado, b = feriado da páscoa, c = natal, 0 = nenhum

SchoolHoliday - indica se a (Loja, Data) foi afetada pelo fechamento de escolas públicas

StoreType  - diferencia entre 4 modelos de loja diferentes: a, b, c, d

Sortimento - descreve um nível de sortimento: a = básico, b = extra, c = estendido

CompetitionDistance - distância em metros até a loja concorrente mais próxima

CompetitionOpenSince[Month/Year] - fornece o ano e o mês aproximados em que o concorrente mais próximo foi aberto

Promo - indica se uma loja está executando uma promoção naquele dia

Promo2 - Promo2 é uma promoção contínua e consecutiva para algumas lojas: 0 = a loja não está participando, 1 = a loja está participando

Promo2Since[Year/Week] - descreve o ano e a semana do calendário em que a loja começou a participar do Promo2

PromoInterval - descreve os intervalos consecutivos em que a Promo2 é iniciada, nomeando os meses em que a promoção é iniciada novamente. Por exemplo, "fevereiro, maio, agosto, novembro" significa que cada rodada começa em fevereiro, maio, agosto, novembro de qualquer ano para essa loja.
