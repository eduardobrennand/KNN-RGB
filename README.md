# KNN-RGB
Estudo sobre o algoritmo de Machine Learning K-Nearest Neighbor. Utilizei um conjunto de dados com mais de 5000 exemplos de cores classificadas a partir do seus valores RGB (red, blue, green).

### A partir deste conjunto de dados, apliquei o algoritmo KNN de duas maneiras distintas:

1. No primeiro método, no arquivo "KNN Classificar Cores - Manual.ipynb", montei o algoritmo de forma manual, utilizando da fórmula da distância euclidiana e obtive uma acurácia geral de 91%.

2. No segundo método, no arquivo "KNN Classificar Cores - SciKit-Learn.ipynb", utilizei o algoritmo a partir da biblioteca Scikit-Learn (KNeighborsClassifier) e obtive uma acurácia geral de 86%.

Além disso, os dois arquivos apresentam um classification report, função do scikit-learn para expor métricas referentes aos modelos, como acurácia, precisão, recall e f1-score. Para ter um entendimento melhor dessas métricas, utilizei também a função de matriz de confusão do scikit-learn e criei um gráfico utilizando matplotlib e seaborn para visualizar a partir de um gráfico de calor essa matriz.

## Conclusão:
Nos dois modelos, consegui obter uma acurácia geral muito boa de mais de 80% nos dois casos. Entretanto, no modelo manual, consegui métricas excelentes e consideravelmente melhores que o modelo do scikit-learn.
