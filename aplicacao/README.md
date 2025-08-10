# 📊 Dashboard de Análise de Salários na Área de Dados

Este projeto é um dashboard interativo construído com a biblioteca [Streamlit](https://streamlit.io/) em Python. Ele permite a exploração e análise de um conjunto de dados sobre salários em cargos da área de dados. O objetivo é fornecer insights visuais sobre a distribuição salarial, os cargos mais bem pagos, a proporção de trabalho remoto e outros fatores que influenciam a remuneração.

O dashboard foi criado como parte de um curso ou imersão, e serve como uma excelente demonstração de como usar ferramentas modernas de visualização de dados para criar aplicações web interativas com poucas linhas de código.

## 🚀 Funcionalidades

O dashboard oferece as seguintes funcionalidades:

-   **Métricas Principais (KPIs):** Visão geral instantânea do salário médio, salário máximo, total de registros e o cargo mais frequente na base de dados.
-   **Filtros Interativos:** A barra lateral permite filtrar os dados por:
    -   Ano
    -   Senioridade do cargo
    -   Tipo de Contrato
    -   Tamanho da Empresa
-   **Visualizações Gráficas:**
    -   **Top 10 cargos por salário médio:** Gráfico de barras que mostra os cargos com os maiores salários médios.
    -   **Distribuição de salários:** Histograma que exibe a frequência de salários em diferentes faixas.
    -   **Proporção de tipos de trabalho:** Gráfico de pizza que ilustra a divisão entre trabalho remoto, híbrido e presencial.
    -   **Salário médio de Cientista de Dados por país:** Gráfico de mapa (coropleth) que mostra a média salarial para o cargo de Cientista de Dados em diferentes países.
-   **Tabela de Dados:** Uma tabela detalhada com todos os registros filtrados, permitindo uma inspeção aprofundada dos dados subjacentes.

## ⚙️ Como Executar o Projeto

Para executar este dashboard localmente, siga os passos abaixo.

### Pré-requisitos

Certifique-se de ter o Python 3.7 ou superior instalado.

### 1. Instalar as dependências

Você precisa instalar as bibliotecas `streamlit`, `pandas` e `plotly`. Use o pip para instalá-las:

```bash
pip install streamlit pandas plotly
