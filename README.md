📊 Projeto de Imersão de Dados em Python - Alura
================================================

🚀 Sobre o projeto
------------------

Este projeto foi desenvolvido durante a **Imersão de Dados em Python da Alura**. O objetivo foi explorar uma base de dados de salários na área de tecnologia, realizar análises exploratórias, tratar inconsistências e construir um **dashboard interativo** para visualizar os principais insights.

🛠️ Tecnologias utilizadas
--------------------------

-   **Python 3.13**

-   **Pandas** → análise e limpeza dos dados

-   **NumPy** → manipulação de valores nulos

-   **Matplotlib / Seaborn** → gráficos estáticos

-   **Plotly Express** → visualizações interativas

-   **Streamlit** → construção do dashboard

-   **Jupyter Notebook** → exploração inicial dos dados

📂 Estrutura do projeto
-----------------------

Código

```
├── data/                # Base de dados utilizada 
├── notebooks/           # Análises exploratórias e tratamento dos dados
├── dashboard/           # Código do dashboard interativo 
├── requirements.txt     # Dependências do projeto
└── README.md            # Documentação

```

▶️ Executar no Google Colab
---------------------------

Você pode abrir e executar o notebook diretamente no Google Colab clicando no botão abaixo:

[![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/thxt4/imersao-dados-python-alura/blob/main/notebooks/analise_salarios.ipynb


📊 Principais etapas
--------------------

### 1\. Carregamento e exploração inicial

-   Importação da base `salaries.csv`.

-   Verificação de colunas, tipos de dados e estatísticas descritivas.

-   Ajuste dos nomes das colunas para maior clareza.

### 2\. Limpeza e padronização

-   Padronização de categorias (`senioridade`, `contrato`, `tamanho_empresa`, `remoto`).

-   Tratamento de valores nulos com diferentes estratégias (média, mediana, forward fill, substituição por valores padrão).

-   Conversão da coluna `ano` para inteiro.

### 3\. Análises e visualizações

-   Distribuição de cargos e senioridade.

-   Salário médio anual por nível de senioridade.

-   Histogramas e boxplots para entender a distribuição dos salários.

-   Gráficos interativos com **Plotly** (barras, pizza e mapas).

### 4\. Dashboard interativo

O dashboard foi construído em **Streamlit** e permite:

-   Filtrar dados por **ano, senioridade, tipo de contrato e tamanho da empresa**.

-   Visualizar métricas gerais: salário médio, salário máximo, total de registros e cargo mais frequente.

-   Explorar gráficos interativos:

    -   **Top 10 cargos por salário médio**

    -   **Distribuição de salários anuais**

    -   **Proporção dos tipos de trabalho (remoto, híbrido, presencial)**

    -   **Mapa de salários médios de Cientistas de Dados por país**

-   Consultar os dados filtrados em uma tabela detalhada.

⚙️ Como executar
----------------

1.  Clone este repositório:

    ```
    git clone https://github.com/seu-usuario/seu-repo.git

    ```

2.  Instale as dependências:

    ```
    pip install -r requirements.txt

    ```

3.  Execute o notebook para visualizar as análises:


    ```
    jupyter notebook notebooks/analise_salarios.ipynb

    ```

4.  Rode o dashboard:

    ```
    streamlit run dashboard/app.py

    ```

📈 Resultados
-------------

-   Padronização dos dados de senioridade, contrato e tamanho de empresa.

-   Identificação de diferenças salariais entre níveis de senioridade.

-   Visualização clara da proporção de trabalho remoto, híbrido e presencial.

-   Dashboard interativo para facilitar a exploração dos insights.

👩‍💻 Autoria
-------------

Projeto desenvolvido por **Thaís Soares** durante a Imersão de Dados em Python da Alura.
