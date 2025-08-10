# Imersão Dados com Python Alura - Análise de Dados com Pandas

Este projeto é um notebook de análise de dados criado como parte da "Imersão Dados com Python Alura", focando na utilização da biblioteca Pandas para explorar e analisar um conjunto de dados sobre salários em cargos de tecnologia.

## Conjunto de Dados

O conjunto de dados utilizado, 'salaries.csv', foi obtido de um repositório no GitHub. Ele contém as seguintes colunas:
- `work_year`: O ano de trabalho em que o salário foi pago.
- `experience_level`: O nível de experiência do funcionário (por exemplo, SE - Senior Engineer, MI - Middle-level, EN - Entry-level).
- `employment_type`: O tipo de emprego (por exemplo, FT - Full-time).
- `job_title`: O cargo do funcionário.
- `salary`: O salário bruto.
- `salary_currency`: A moeda do salário bruto.
- `salary_in_usd`: O salário convertido para USD.
- `employee_residence`: O país de residência do funcionário.
- `remote_ratio`: A proporção de trabalho remoto (0, 50, 100).
- `company_location`: O país da empresa.
- `company_size`: O tamanho da empresa (S, M, L).

## Análise Realizada

O notebook executa os seguintes passos para a análise inicial do conjunto de dados:
1.  **Importação de Bibliotecas:** Importa a biblioteca `pandas` para a manipulação e análise dos dados.
2.  **Carregamento dos Dados:** Lê o arquivo `salaries.csv` diretamente de uma URL do GitHub em um DataFrame.
3.  **Exploração Inicial:**
    -   Exibe as primeiras linhas do DataFrame para uma visualização rápida (`df.head()`).
    -   Fornece um resumo conciso do DataFrame, incluindo o número de linhas e colunas, tipos de dados e contagem de valores não nulos (`df.info()`).
    -   Apresenta estatísticas descritivas das colunas numéricas, como contagem, média, desvio padrão, mínimo e máximo (`df.describe()`).
    -   Verifica as dimensões do DataFrame (`df.shape`).

## Como Executar o Notebook

Para executar este notebook, você precisará ter o Python e a biblioteca Pandas instalados. A maneira mais fácil de usar é através do Google Colab ou de um ambiente Jupyter local.

1.  Clone este repositório ou baixe o arquivo `Imersão_dados_com_Python_Alura_Agosto_2025.ipynb`.
2.  Abra o notebook em seu ambiente preferido (Jupyter Notebook, JupyterLab ou Google Colab).
3.  Execute as células sequencialmente para reproduzir a análise.
