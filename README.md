# Árvore de decisão
<div align="center"> <a href="#Sobre">Sobre</a> • <a href="#Tecnologias-e-bibliotecas">Tecnologias e bibliotecas</a> • <a href="#Dataset">Dataset</a> </div>
  

# Sobre
Árvores de decisão são modelos estatísticos que utilizam treinamento supervisionado para realizar a classificação ou previsão de dados. O objetivo é criar um modelo que preveja o valor de uma variável de destino aprendendo regras de decisão simples inferidas a partir dos recursos de dados.

Estes modelos utilizam a estratégia de dividir para conquistar: um problema complexo é decomposto em sub-problemas mais simples e recursivamente esta técnica é aplicada a cada sub-problema. As árvores de decisão estão entre os mais populares algoritmos de inferência e tem sido aplicado em várias áreas como:

- Diagnóstico médico;
- Risco de crédito
- Perfil de clientes
- Classificação e predição diversos problemas de negócios

Através das árvores de decisão é possível extrair regras do tipo “se-então” que são facilmente compreendidas.

# Motivação
Esse projeto foi desenvolvido como demonstração prática do algoritmo utilizado no [Bootcamp DiversiData Tech PAN](https://www.igti.com.br/bootcamp/diversidata-tech-pan), IGIT Data Science.

# Tecnologias e bibliotecas
Linguagem de programação:</br>
[Python 3.9](https://www.python.org/)

Bibliotecas utilizadas:

1. [graphviz](https://pypi.org/project/graphviz/) - Utilizada para criação e rendenização de gráficos na linguagem DOT;
2. [imblearn](https://pypi.org/project/imblearn/) - Utilizada para tratar dados desbalanceados;
3. [matplotlib](https://pypi.org/project/imblearn/) - Responsável pela criação de representações gráficas;
4. [os](https://docs.python.org/pt-br/3.7/library/os.html) - Responsável por realizar diversas interfaces de sistema operacional;
5. [pandas](https://pandas.pydata.org/docs/index.html) - Utilizada para realizar manipulação e análise de dados em dataframes e series;
6. [sklearn](https://scikit-learn.org/stable/) - Utilizada para criação de modelos de Machine Learning;

IDE:

Para esse projeto, optei por utilizar o aplicativo web Jupyter Notebook com Colab Google:</br>
[Jupyter Notebook](https://jupyter.org/)</br>
[Colab Google](https://colab.research.google.com/)

# Dataset
Utilizamos o dataset diabets disponibilizado em:</br>
[Dataset diabets](https://www.kaggle.com/datasets/saurabh00007/diabetescsv?select=diabetes.csv)
