# O projeto

O objetivo desse projeto é utilizar o modelo de regressão linear simples para modelar o valor do sinistro pago pelo clientes em contratos de planos de saúde

# Dados

Os dados podem ser obtidos em https://www.kaggle.com/mirichoi0218/insurance.

# Etapas

**1) Análise Exploratória dos dados**

**2) Separar os dados entre treino e teste**

**3) Aplicar modelo de regressão linear**

**4) Avaliação do modelo**

**5) Criação de novas features**

**6) Reaplicar modelo de regressão linear**

**7) Reavaliação do modelo**


# Resultados

No primeiro modelo geramos as seguites métricas de erros:

O erro médio absoluto é : 4243.654116653135
O erro médio quadrado é : 35117755.73613631
O erro mediano absoluto é : 2699.86836163708
O erro médio absoluto é : 5926.023602394468

e tivemos um R-squared de 76.7%.


Após a inserção das nova features polinomiais todas métricas de erro caíram para :

O erro médio absoluto é : 2785.592897670839
O erro médio quadrado é : 22067396.46853433
O erro mediano absoluto é : 1694.2992920982797
O erro médio absoluto é : 4697.594753545088

e o R-squared teve um aumento para 85.3%.
