Hate speech-detection

# Projeto de Detecção de Discurso de Ódio

Este projeto utiliza técnicas de Processamento de Linguagem Natural (NLP) e aprendizado de máquina para detectar discurso de ódio em textos. O modelo foi treinado com um conjunto de dados do Kaggle, que inclui várias amostras de texto classificadas como discurso de ódio, linguagem ofensiva ou nenhum dos dois.

## Descrição

O objetivo deste projeto é construir um modelo de machine learning que possa classificar textos com base em seu conteúdo potencialmente ofensivo ou prejudicial. Este repositório contém o notebook Jupyter usado para treinar o modelo, além de uma descrição detalhada de todo o processo, desde o pré-processamento dos dados até a avaliação do modelo.

## Tecnologias Utilizadas

- Python 3
- Jupyter Notebook
- Bibliotecas Python:
  - Pandas
  - NumPy
  - Scikit-Learn
  - TensorFlow
  - NLTK

## Estrutura do Repositório

hate-speech-detection/
│
├── notebooks/ - Contém o notebook do projeto.
│ └── Hate_Speech_Detection.ipynb
│
├── data/ - Diretório para os datasets utilizados.
│ └── labeled_data.csv
│
└── README.md - Descrição do projeto e instruções.


## Como Configurar e Executar

### Pré-requisitos

Antes de executar o notebook, é necessário instalar as dependências do projeto, o que pode ser feito através do seguinte comando:

Dependências Básicas :

>pip install jupyter  # Para rodar o Jupyter Notebook
>pip install numpy  # Para operações matemáticas e matriciais
>pip install pandas  # Para manipulação e análise de dados


Dependências para Processamento de Linguagem Natural :

> pip install nltk  # Natural Language Toolkit, para tarefas de NLP

Dependências para Machine Learning :

>pip install scikit-learn  # Para algoritmos de aprendizado de máquina e ferramentas de modelagem
>pip install tensorflow  # Para redes neurais e aprendizado profundo

Dependências para Manipulação de Dados e Preprocessing :

>pip install beautifulsoup4  # Para web scraping e limpeza de dados HTML

Dependências para Visualização de Dados :

>pip install matplotlib  # Para criação de gráficos e visualizações
>pip install seaborn  # Baseado em matplotlib, para visualizações estatísticas mais bonitas

Comando de Instalação Agrupado :
Para facilitar, você também pode instalar todas essas dependências de uma vez com o seguinte comando ->

> pip install jupyter numpy pandas nltk scikit-learn tensorflow beautifulsoup4 matplotlib seaborn


### Execução

Para executar o notebook:

Clone o repositório para sua máquina local:

>git clone https://github.com/seu-usuario/hate-speech-detection.git


Navegue até o diretório do projeto e inicie o Jupyter Notebook:

>cd hate-speech-detection/notebooks
jupyter notebook


Abra o arquivo Hate_Speech_Detection.ipynb e execute as células sequencialmente.

# Como Contribuir

Contribuições para o projeto são bem-vindas. Para contribuir, por favor siga os passos:

1.Faça fork do repositório.

2.Crie uma nova branch para suas modificações (git checkout -b feature/nova-feature).

3.Faça commit das suas alterações (git commit -am 'Adiciona nova feature').

4.Faça push para a branch (git push origin feature/nova-feature).
Crie um novo Pull Request.


#Autores

Guilherme Braga
