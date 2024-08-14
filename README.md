Dataset 1: Classificação (Aprendizado Supervisionado)
Nome: Iris Species
Link: https://www.kaggle.com/datasets/uciml/iris
Objetivo: Classificar flores de íris em três espécies diferentes (Iris setosa, Iris versicolor e Iris virginica) com base em suas características.
Entradas:
SepalLengthCm: Comprimento da sépala (em cm).
SepalWidthCm: Largura da sépala (em cm).
PetalLengthCm: Comprimento da pétala (em cm).
PetalWidthCm: Largura da pétala (em cm).

Saída:
Species: Espécie da flor de íris (Iris setosa, Iris versicolor ou Iris virginica).
Descrição do Problema: O problema é classificar flores de íris em suas respectivas espécies com base em medidas de suas pétalas e sépalas.



Dataset 2: Regressão (Aprendizado Supervisionado)
Nome: Boston House Prices
Link: https://www.kaggle.com/datasets/vivin/boston-housing-dataset
Objetivo: Prever o valor mediano das casas em diferentes áreas de Boston, utilizando características socioeconômicas da região.
Entradas:
CRIM: Taxa de criminalidade per capita por município.
ZN: Proporção de terrenos residenciais para lotes maiores que 25.000 pés quadrados.
INDUS: Proporção de acres de indústria comercial não varejista por município.
CHAS: Variável dummy River Charles (1 se o município limita o Rio Charles; 0 caso contrário).
NOX: Concentração de óxidos nítricos (partes por milhão).
RM: Número médio de quartos por residência.
AGE: Proporção de unidades ocupadas por proprietários construídas antes de 1940.
DIS: Dimensões ponderadas para acessos às cinco rodovias principais.
RAD: Índice de acessibilidade às rodovias radiais.
TAX: Taxa de imposto de propriedade de $ 10.000.
PTRATIO: Razão aluno-professor por município.
B: 1000(Bk - 0,63)^2, onde Bk é a proporção de pessoas de ascendência afro-americana por município.
LSTAT: Porcentagem da população de baixa renda.

Saída:
MEDV: Valor mediano das casas ocupadas pelo proprietário em US$ 1.000.
Descrição do Problema: O objetivo é prever o valor mediano das casas em diferentes áreas de Boston, utilizando informações sobre as características socioeconômicas de cada região.




Dataset 3: Aprendizado Não Supervisionado - Exemplo Adicional
Nome: Customer Segmentation Dataset
Link: https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python
Objetivo: Segmentar clientes em grupos distintos com base em seus dados demográficos e de comportamento de compra.
Entradas:
CustomerID: Identificador único do cliente.
Gender: Sexo do cliente.
Age: Idade do cliente.
Annual Income (k$): Renda anual do cliente (em milhares de dólares).
Spending Score (1-100): Pontuação atribuída pelo shopping com base no comportamento de compra do cliente (quanto maior, mais o cliente gasta).

Saída:
Não há uma saída explícita em aprendizado não supervisionado. O objetivo é encontrar grupos de clientes similares sem a necessidade de rótulos pré-definidos.
Descrição do Problema: O problema consiste em segmentar os clientes do shopping em grupos distintos, com base em suas características, para que o shopping possa direcionar campanhas de marketing personalizadas e otimizar suas estratégias de negócio.
Observações:
Este dataset é ideal para aplicar algoritmos de clustering como K-means, Mean Shift Clustering e Agglomerative Clustering.
A análise dos clusters formados pode revelar insights importantes sobre o comportamento dos clientes, como a identificação de grupos com alto potencial de compra ou grupos com baixo índice de fidelidade.
Após a segmentação, outras análises e modelos de aprendizado de máquina podem ser aplicados para otimizar as estratégias de marketing e vendas.
