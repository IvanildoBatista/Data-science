# Sobre o projeto

Diabetes é uma doença extremamente danosa ao ser humano. Segundo A Organização Mundial de Saúde (OMS) cerca de 422 milhões de adultos estão com diabetes no mundo 
(90% desse são portadores do tipo 2 da doença) e no Brasil cerca de 6% da população possue essa doença. Nesse projeto iremos usar modelos de machine learning para tentar 
diagnosticar essa doença, com base em outras características, se mulheres são ou não portadores de diabetes.  

# Dados
Usaremos dados PIMA Indian diabetes que pode ser obtido em https://www.kaggle.com/uciml/pima-indians-diabetes-database e também se encontra em anexo. 

# Etapas do projeto

1) Importação das bibliotecas
2) Importação dos dados
3) Tratamento dos dados
4) Análise exploratória dos dados
5) Separação dos dados de treino e teste
6) Modelagem
7) Análise dos resultados

# Modelos usados

1) Regressão Logística;
2) SVM
3) Decision Tree
4) Random Forest
5) Extra Tree
6) LightGBM
7) XGBoost
8) CatBoost

# Bibliotecas usadas

1) Pandas
2) Numpy
3) Seaborn
4) Matplotlib
5) Scikit-larn
6) imblearn
7) LightGBM
8) XGBoost
9) Catboost

# Resultado

Após treinarmos e testarmos os modelos, encontramos que o melhor modelo foi o Extra Tree que teve uma acurácia de 85% , precisão para as classes 0 e 1, respectivamente, 
de 87% e 83% e um AUC (Area Under The Curve) de 88%.
