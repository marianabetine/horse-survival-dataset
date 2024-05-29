# Previsão da Sobrevivência de Cavalos: Um Modelo Supervisionado de Classificação
O objetivo do trabalho foi desenvolver um modelo que fosse capaz de prever a sobrevivência de cavalos com base em informações sobre suas condições médicas. Para alcançar esse objetivo, foi utilizada a técnica de Classificação. A escolha da técnica se justifica pela natureza categórica da variável alvo, que assume três valores distintos (morte, sobrevivência e eutanásia).

Este trabalho foi realizado para a disciplina de Data Mining da Pós-Graduação em Ciência de Dados e Inteligência Artificial da PUC-RJ.

## Base de Dados
O desenvolvimento deste trabalho baseou-se em um conjunto de dados previamente dividido em conjuntos de treinamento e teste, conforme fornecido pelo curso. Os arquivos utilizados foram:
* horse.csv: Este arquivo contém o conjunto de dados de treinamento, utilizado para construir o modelo de machine learning.
* horseTest.csv: Este arquivo contém o conjunto de dados de teste, utilizado para avaliar o desempenho do modelo treinado.

Vale ressaltar que a base de dados original, intitulada "Horse Colic", foi disponibilizada no repositório UCI Machine Learning Repository. A autoria do dataset é atribuída a Mary McLeish e Matt Cecile, e sua publicação ocorreu em 1989. Para mais informações, consulte o seguinte link: https://doi.org/10.24432/C58W23.

## Modelos utilizados
Para desenvolver um modelo preditivo eficaz para o problema em questão, foram testados diversos algoritmos de aprendizado de máquina supervisionado. Os algoritmos testados foram:
* Árvore de Decisão
* KNN
* Regressão Logística Multinomial (RLM)
* Árvores de Decisão Aleatórias (Random Forests)

