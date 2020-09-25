# Sobre o projeto

Tumor é o nome dado ao crescimento anormal de células de qualquer tecido do corpo humano. Os tumores podem ser benignos (apenas crescem e não danificam outros tecidos) ou malignos
(também chamados de câncer e se propagam para outros tecidos - metástase - e prejudica-os). Geralmente um célula do corpo humano nasce, exerce suas funções e, em seguida, morre 
por conta de algum problema ou por não poder exercer suas funções. O nascimento celular é sempre controlado para que não haja células em demasia, sempre substituindo as antigas
que morreram. Entretanto, por conta de alguma mutação celular, algumas células acabam não morrendo e continuam a se produzir, sem que o corpo identifique essa anomalia.

Dependendo do tipo do tumor, sua localização no corpo humano, da velocidade de crescimento das células e do tempo de diagnóstico dos exames, o quadro do paciente piorado. 
Por isso, o melhor seria, um avaliação mais rápida do quadro do paciente; o que nos sugere um problema de classificação: se o tumor é ou não maligno (ou benigno). Um tumor que é 
letal e afeta bastante as mulheres (em raros casos, homens também) são os tumores mamários (ou câncer de mama).

Nesse projeto usaremos dados sobre tumores e iremos, com um modelo de classificação do tipo *Árvore de Decisão*, vamos classificar se tumores mamários são ou não malignos.
 
# Dados

Os dados podem ser obtidos em https://www.kaggle.com/uciml/breast-cancer-wisconsin-data e estão anexadas nessa pasta em formato csv.

# Etapas

**1) Análise Exploratória dos dados**

**2) Tratar dos dados**

**3) Separar os dados entre treino e teste**

**4) Criar do modelo de Árvore**

**5) Avaliação do modelo**

# Resultados

Encontramos um modelo do tipo árvore que que identificou com uma precisão de 98% os tumores que são benignos e com 91% os tumores que são malignos, a acurácia desse modelo foi de 
92.27%. Após uma seleção de *features* pelo método *importance_features* da Árvore de Decisão, a precisão para tumores benignos caiu para 97% (o que ainda é alta), mas a precisão
de classificação de tumores malignos subiu para 93%, e a acurácia do modelo subiu para 93.84%.
