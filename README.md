# Desafio de classificação de câncer de mama com machine learning

Esse projeto de ciência dados tem como objetivo utilizar modelos de machine learning para classificar células cancerigenas entre malignas e benignas.
Para isso, foi criado um notebook python utilizando bibliotecas como pandas, numpy, matplotlib, seaborn, sklearn e outras.

Os dados foram extraído do Kaggle: https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data
O conjunto de dados contém várias métricas de amostras de células cancerigenas, como espessura, tamanho do tumor, cor e outros.
Além disso, existe uma coluna resposta (Diagnostico) com M para maligno e B para benigno.

Primeiramente, foi realizada uma análise exploratória dos dados para identificar desbalanceamento, outliers e nulos.
Depois, foi utilizada a técnica de SMOTE para balancear os dados.
Por fim, para classificar e treinar o modelo de machine learning, foram utlizados os modelos de logistic regression, decision tree, e KNN (nearst neighbors).

