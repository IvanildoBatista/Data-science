# Sobre o projeto

O objetivo desse projeto é utilizar o modelo de regressão linear simples para modelar o valor do sinistro pago pelo clientes em contratos de planos de saúde.

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

|  **Métrica**     |  **Valor**  |
|:--------:|:-----------:|
|Erro médio absoluto   | 4243.654116653135|
|Erro médio quadrado   |35117755.73613631     |
|Erro mediano absoluto  | 2699.86836163708  |
|Erro médio absoluto  | 5926.023602394468  |
|*R-squared*  |76.7%  |


Após a inserção das nova *features* polinomiais todas métricas de erro caíram para e o *R-squared* melhorou significativamente, conforme abaixo:

|  **Métrica**     |  **Valor**  |
|:--------:|:-----------:|
|Erro médio absoluto   | 2785.592897670839|
|Erro médio quadrado   |22067396.46853433 |
|Erro mediano absoluto  | 1694.2992920982797 |
|Erro médio absoluto  | 4697.594753545088  |
|*R-squared*  |85.3%  |
