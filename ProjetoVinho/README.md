# Aplicando *K-Means* para agrupamento de vinhos

O vinho é uma das bebidas mais conhecidas do mundo e tem uma longuíssima história, com as primeiras vinhas cultivadas por volta do ano 7000 a 5000 a.C na Geórgia, que pode 
apontar para o primeira evidência de vitcultura. Em seguida, na Armênia, por volta de 4000 a.C. os primeiro equipamentos para criados para produção da bebida. Em lendas como
a de Gilgamesh e no relato bíblico do gênesis (antigos textos) mostram a presença da bebida, desde muito antes de muitas grandes e famosas civilizações.

Além da região do Cáucaso, o vinho desenvolveu-se também no Antigo Egito (conforme hieróglifos da era pré-dinástica dos faraós), mais espeficamente na região do Vale do Nilo.
Como o vinho era um bebida de difícil produção, então seu consumo era restrito a faraós e famílias importantes do Egito. A grande contribuição dos egípcios foi o processo de 
fermentação do vinho, que ao invés de deixarem fermentar sozinho, começaram a manejar esse processo.

A história do vinho também segue-se pela Grécia e Roma, mas foi na Idade Média (após a queda do império romano) que o consumo do vinho estava difundido em todo velho 
continente e era usado, principalmente, em banquetes. E nessa a França ascende como uma grande produtora vinho. O vinho francês ficou conhecido por sua qualidade e, essa fama,
que perdura até os dias de hoje.

Existem diferentes tipos de vinhos nos dias de hoje, como:

1) **Vinhos Brancos**: leves, de corpo médio e encorpados;

2) **Vinhos Rosés**: leves e encorpados;

3) **Vinhos Tintos**: leves, de corpo médio e encorpados;

4) **Vinhos espumantes**: por tipos de fermentação (*Asti, Charmat* e *Champenoise*);

5) **Vinhos de Sobremesa**: Colheita tardia, Botrytizados, Fortificados e Passificados.

Usaremos variantes tinto e branco do vinho "Vinho Verde" português. Esses vinhos foram os primeiros vinhos portugueses exportados para mercados europeus. 
Nos séculos XVI e XVII os vinhos do Vale do Minho e do Vale do Lima eram regularmente transportados para o norte da Europa nas mesmas embarcações que transportavam o 
bacalhau e produtos manufaturados.

Hoje a região dos Vinhos Verdes, ocupando o noroeste de Portugal, é uma das maiores e mais antigas regiões vinícolas do mundo. A origem do nome Vinho Verde refere-se às 
características naturais da região, que produzem uma folhagem verde densa.

Usarei nesse projeto o algoritmo de ahgrupamento *K-Means*, que é um dos modelos mais conhecidos para esse tipo de trabalho.

## Dados

Os dados podem ser obtidos nos *links* abaixo:

1) https://www.kaggle.com/uciml/red-wine-quality-cortez-et-al-2009?select=winequality-red.csv;

2) https://archive.ics.uci.edu/ml/datasets/Wine.

## Etapas do projeto 

1) Importação das bibliotecas;

2) Importação dos dados;

3) Análise exploratória dos dados;

4) Redução de dimensionalidade;

5) Modelagem dos dados:

   5.1) *K-Means*

6) Conclusão.

## Resultados

Com o algoritmo *K-Means* encontramos 4 grupos de vinhos.
