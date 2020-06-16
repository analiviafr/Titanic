# Titanic
O presente repositório realiza classificação e predição sobre o dataset [Titanic](https://www.kaggle.com/c/titanic), disponibilizada pela plataforma Kaggle.
Além disso, também foi realizada uma análise exploratória sobre os dados.

## Resultados

### Classificação e Predição
Foram realizados experimentos com variadas técnicas de machine learning, tais como Nearest Centroid, Decision Tree, Random Forest e entre outros.
A partir da análise dos experimentos executados verificou-se que o método Ranfom Forest obteve melhor resultado, alcançando 96,41% de acurácia.
O segundo melhor resultado foi dado pelo método Hist Gradient Boosting Classifier, o qual atingiu acurácia de 93,94%.

Foi gerado um arquivo .csv para cada método contendo suas respectivas previsões. O método teve suas previsões enviadas para a competição realizada pela Kaggle, alcançando 0,75598 pontos no desafio.

Todos os experimentos realizados podem ser executados a partir do arquivo *Titanic.ipynb*.

### Análise Exploratória
O passo a passo da análise exploratória realizada e os códigos utilizados estão disponíveis no arquivo *TitanicAnalysis.ipynb*. Tal análise resultou nas plotagens apresentadas abaixo.

#### Histograma das variaveis numéricas
<p align="center">
  <img src="/docs/Histogram.PNG" >
</p>

#### Sobrevivência por classe
<p align="center">
  <img src="/docs/Pclass.PNG" >
</p>

#### Sobrevivência por ponto de embarque
<p align="center">
  <img src="/docs/Embarked.PNG" >
</p>

#### Influência da idade sobre os sobreviventes
<p align="center">
  <img src="/docs/Age.PNG" >
</p>

#### Heatmap
<p align="center">
  <img src="/docs/Heatmap.PNG" >
</p>

#### Matriz de dispersão
<p align="center">
  <img src="/docs/Scatter_matrix.PNG" >
</p>
