# 📊 [Modelo IMDB Preditivo]

---

## 📖 Índice

- [📊 \[Modelo IMDB Preditivo\]](#-modelo-imdb-preditivo)
  - [📖 Índice](#-índice)
  - [🎯 Sobre o Projeto](#-sobre-o-projeto)
  - [🛠️ Tecnologias Utilizadas](#️-tecnologias-utilizadas)
  - [🚀 Como Usar](#-como-usar)
    - [Pré-requisitos](#pré-requisitos)
    - [Instalação](#instalação)
    - [Execução](#execução)
  - [📂 Estrutura do Notebook](#-estrutura-do-notebook)
  - [📈 Resultados](#-resultados)
  - [📬 Contato](#-contato)

---

## 🎯 Sobre o Projeto

Esse é um projeto de ciência de dados para uma empresa de Hollywood. Através da análise de um banco de dados de filmes, o objetivo é criar modelos para identificar quais os principais fatores estão relacionados com o sucesso de um filme.

*   **Problema**: Qual o proximo tipo de filme a ser desenvolvido?
*   **Objetivo**: Criar um modelo capaz de prever a nota do IMDB de um filme com base em suas características.
*   **Metodologia**: Análise exploratória dos dados e criação de modelos de Machine Learning.

---


## 🛠️ Tecnologias Utilizadas

Bibliotecas e frameworks utilizadas neste projeto


*   [Python](https://www.python.org/)
*   [Pandas](https://pandas.pydata.org/)
*   [NumPy](https://numpy.org/)
*   [Matplotlib](https://matplotlib.org/)
*   [Seaborn](https://seaborn.pydata.org/)
*   [Scikit-learn](https://scikit-learn.org/stable/)
*   [Jupyter Notebook](https://jupyter.org/) / [Google Colab](https://colab.research.google.com/)

---

## 🚀 Como Usar

Instruções sobre como você pode rodar seu notebook localmente.

### Pré-requisitos

Certifique-se de ter o Python e o pip instalados em sua máquina.

*   Python (versão 3.8 ou superior)
*   pip

### Instalação

1.  Clone o repositório:
    ```bash
    git clone https://github.com/seu-usuario/Modelo-Preditivo-IMDB.git
    ```
2.  Navegue até o diretório do projeto:
    ```bash
    cd Modelo-Preditivo-IMDB
    ```
3.  (Recomendado) Crie e ative um ambiente virtual:
    ```bash
    python -m venv venv
    venv\Scripts\activate  # No Linux, use `source venv/bin/activate`
    ```
4.  Instale as dependências:
    ```bash
    pip install -r requirements.txt
    ```
5. Rodes esses comandos uma vez apenas:
    ```bash
    %pip install nltk #(rodar uma vez para instalar o nltk)
    
    nltk.download('stopwords')# (rodar uma vez para baixar as stopwords)
    nltk.download('punkt') # (rodar uma vez para baixar o tokenizer)
    nltk.download('wordnet') # (rodar uma vez para baixar o lemmatizer)
    nltk.download('punkt_tab')(rodar uma vez para baixar o tokenizer)
    ```
    
### Execução

1.  Inicie o Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
2.  Abra o arquivo `story.ipynb` e execute as células sequencialmente.

---

## 📂 Estrutura do Notebook

O notebook está dividido nas seguintes seções:

1.  **Carregamento dos Dados**: Importação das bibliotecas e leitura do dataset.
2.  **Análise Exploratória de Dados (EDA)**: Visualizações e estatísticas descritivas para entender os dados.
3.  **Pré-processamento e Limpeza**: Tratamento de valores ausentes, normalização, etc.
4.  **Engenharia de Features**: Criação de novas variáveis a partir das existentes.
5.  **Modelagem**: Treinamento do(s) modelo(s) de Machine Learning.
6.  **Avaliação do Modelo**: Análise de métricas de performance (acurácia, precisão, recall, F1-score, etc.).
7.  **Conclusão**: Resumo dos resultados e insights obtidos.

---

## 📈 Resultados

*   A analise exploratoria dos dados revelou uma forte correlação entre as variaveis Gross e No_of_Votes, indicando que a popularidade de um filme esta ligada ao seu faturamento.
*   O modelo de regressão nos mostra que a nota do IMDB esta fortemente relacionada com a Meta_Score e o No_of_votes, indicando que a popularidade é um ponto chave para o sucesso de um filme
*   Problemas de classificação de gênero: para prever o genero de um filme utilizei tecnicas de NLP e um classificador. O modelo de regressão logística nos retornou uma taxa de 99% de precisão no conjunto de teste, provando que é possivel inferir o genero de um filme à partir de sua sinópse.
*   Problema de previsão de nota do IMDB: Optei por utilizar o modelo RandomForest Regressor para prever a nota do IMDB que é um problema de regressão, a performance do modelo foi avaliada com base na métrica MAE e obtive um resultado de 0.21, que significa que em média as previsões ficam a 0.21 pontos de seu resultado real.

---

## 📬 Contato

Micaías Viola – leo.micaias@gmail.com

Modelo-Preditivo_IMBD: https://github.com/micaiasviola/Modelo-Preditivo-IMDB

