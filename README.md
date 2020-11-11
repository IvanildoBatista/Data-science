# Data-science

Nesse repositório constam projetos de *data science* com algoritmos de *machine learning* de aprendizado supervisionado (regressão e classificação) e de aprendizado não supervisionado (*clustering*). Também projetos de *deep learning*, onde aplico redes neurais para problemas de classificação, regressão e séries temporais.

# Projetos

**Projeto 1 - AutoML para regressão**
Utilização da biblioteca *TPOT* para modelagem de problema de regressão da competição *Kaggle* de previsão do preços de casas. Após aplicar várias gerações, aplicamos os dados de teste ao modelo e obtivemos, na competição, um **RMSE** (raiz quadrada do erro média quadrado) de **0.15742**;

**Projeto 2 - Clustering de ações**
Usando dados de indicadores fundamentalistas extraídos do *site Fundamentus* agrupei ações de empresas listadas na Bovespa. Geramos com o modelo *Mini Batch Kmeans* 5 grupos de ações similares;

**Projeto 3 - Competição Titanic**
Usando modelos de *machine learning* para prever a sobrevivência de passageiros do *Titanic*. Foram usados 21 modelos de classificação, desses, o de melhor desempenho na competição da *Kaggle*, foi o **MPL Classifier** (uma rede neural da biblioteca *Scikit-Learn*) com **80.32%** de  acurácia;

**Projeto 4 - ProjetoCampanha**
Usando o modelo *Gradient Boosting* para classificar clientes de uma campanha bancária, o modelo teve um desempenho superior à baseline (50.32%), tendo uma **acurácia média de 82% e AUC de 0.9** (considerado um resultado considerado satisfatório);

**Projeto 5 - ProjetoCancer**
Aplicando um algoritmo de árvore de decisão (*Decision Tree*) para identificação de tipos de tumores. O modelo obteve uma precisão de 97% para a classe de tumores beningnos e de 93% de precisão para a classe de tumores malignos. Também foi gerado um modelo com apenas as *features* mais importantes, mas o desem penho foi um pouco inferior ao primeiro modelo;

**Projeto 6 - ProjetoCenso**
Aplicação de modelos de *machine learning* para classificação de renda de indivíduos com base nas características do censo. Foram utilizados 11 modelos de classificação e, desses modelos, o de melhor desempenho foi o *XGBoost Classifier* que obteve uma **acurácia de 88.77% e um AUC de 0.96** (desempenho alto);

**Projeto 7 - ProjetoDiabetes**
Classificando ocorrência de diabetes. Foram usados 8 modelos de classificação (sendo 6 do tipo árvore) e destes modelos o que apresentou melhor desempenho na classificação da doença de diabetes foi a *Extra Tree* com uma **acurácia de 85%** e uma **AUC de 88%**;

**Projeto 8 - ProjetoInsurance**
Usando regressão linear para prever/calcular o valor do sinistro pago por clientes de planos de saúde a partir das características dos mesmos. Foram aplicadas ao modelo *features* que possuiam maior correlação, além de aplicarmos *features* polinomiais ao modelo o que reduziu o erro do modelo e aumentou o poder explicativo do mesmo;

**Projeto 9 - ProjetoVinho**
A partir das características de vários tipos de vinho e aplicando métodos de seleção de *clusters* (*elbow method* e *silhouette score*), utilizamos o algoritmos de clusterização *KMeans* e identificamos 4 *clusters* de vinhos;

**Projeto 10 - Rede Neural para Classificação**
Aplicação de redes neurais artificais para identificação de clientes que sejam propensos a contratar o empréstimo pessoal oferecido pelo banco. Como resultado foram geradas três redes neurais com acurácia acima de 98%.

**Projeto 11 - Regras de Associação**
Aplicando o algoritmo *Apriori* em uma base de cestas de compras foram identificadas regras e padrões de compras, como por exemplo : 

1) quem compra *butter, other vegetables e whipped/sour cream* também compra *whole milk* com uma confiança de 0.723404	e um *lift* de 3.2527;

2) quem compra *butter, other vegetables e yogurt* também compra *whole milk* com uma confiança de 0.73469 e um *lift* 3.3035;

3) quem compra *citrus fruit, root vegetables e tropical fruit* também compra *other vegetables* com uma confiança de 0.8 e um *lift*	de 4.7819.

**Projeto 12 - AutoML para classificação**
Aplicação da biblioteca de AutoML TPOT para classificação de preços de celulares. Com o uso dessa biblioteca foi gerado um modelo com uma acurácia de **97.4%**.
