# Sobre o projeto

Uma dos desafios em certos setores da economia (principalmente no varejo) é a modelagem do comportamento dos consumidores; entretanto, o desafio é ainda maior por conta da grande
quantidade de consumidores e de compras que são efetuadas pelos mesmos. Dado esse grande volume de informações, praticamente, torna-se inviável a identificação de padrões de 
consumo. Porém, com o uso de ferramentas matemáticas, estatísticas e tecnológicas podem ser desenvolvidas técnicas para análise e extração de regras e uma das principais ferramentas
que estão sendo usadas são os algoritmos de *machine learning* e dentre os muitos algoritmos que existem, há um que é usado justamente para a identificação dessas regras, que é o 
algoritmo *Apriori*, que nesse projeto, será usado para identificar relações e padrões em cestas de compras. 


# Resultados

|          |  Itens *X*  |   Item *Y*   |    Confiança    |     *Lift*      |
|:--------:|:-----------:|:------------:|:---------------:|:---------------:|
|Regra 1   | *cream cheese* e *domestic eggs*  |  *whole milk*|  0.71428    |   3.2117    |
|Regra 2   |*curd* e *domestic eggs*      |  *whole milk*      |  0.71428       |   3.2117   |
|Regra 3   | *domestic eggs* e *sugar*      | *whole milk*     |   0.7045       |      3.1679   |
|Regra 4   | *butter*, *other vegetables* e *whipped/sour cream*   | *whole milk*  | 0.723404 |  3.2527  |
|Regra 5   | *butter*, *other vegetables* e *yogurt*  |  *whole milk*  |  0.73469  |     3.3035  |
|Regra 6   | *citrus fruit*, *root vegetables* e *tropical fruit* |  *other vegetables*  |  0.8 | 4.7819  |
|Regra 7   |*cream cheese* e *domestic eggs*      | *whole milk* |    0.70731  |    3.1804    |
|Regra 8   | *curd* e *domestic eggs*       | *whole milk*  |  0.70909 |   3.1884    |
|Regra 9   | *curd*, *tropical fruit* e *yogurt*  | *whole milk*  |  0.78048   |   3.5094  |
|Regra 10  | *root vegetables*, *tropical fruit* e *whipped/sour cream* |  *other vegetables* |  0.7179 | 4.2914  |
|Regra 11  | *root vegetables*, *tropical fruit* e *yogurt* |  *whole milk*  |  0.73529   |   3.3062 |
|Regra 12  | *tropical fruit*, *whipped/sour cream* e *yogurt* |  *whole milk* |  0.73076  |  3.2859 |
|Regra 13  | *butter*, *other vegetables* e *whipped/sour cream* | *whole milk* | 0.70212 |   3.1586 |
|Regra 14  | *butter*, *other vegetables* e  *yogurt* |  *whole milk*  |  0.714285 |  3.21339 |
|Regra 15  | *citrus fruit*, *root vegetables* e *tropical fruit* | *other vegetables* |  0.77777 |  4.6521|
|Regra 16  | *curd*, *tropical fruit* e *yogurt* |  *whole milk*  |  0.75609 | 3.4014  |
|Regra 17  | *root vegetables*, *tropical fruit* e *yogurt*  | *whole milk* | 0.72058 | 3.2417  |
|Regra 18  | *tropical fruit*, *whipped/sour cream* e *yogurt*   | *whole milk* |0.71153 |3.20103 |
|Regra 19  | *other vegetables*, *root vegetables*, *tropical fruit* e *yogurt*  | *whole milk*| 0.76190 |3.4259 |
|Regra 20  | *other vegetables*, *root vegetables*, *tropical fruit* e *yogurt*  | *whole milk*| 0.73809 | 3.32050 |










