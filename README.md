# Dashboard interativo com a biblioteca Streamlit

Este projeto utiliza dados de uma empresa de vendas de produtos online, acessados através de uma API para a criação de um Dashboard interativo.

## 📂 Estrutura dos Dados

- Dashboard.py
Arquivo principal do app Streamlit.
Nele você faz:
  - Leitura e tratamento dos dados (groupby, merge, agg, etc).
  -Criação de tabelas de receita, vendas e categorias.
  -Criação de gráficos (plotly.express: mapas, linhas, etc).
  -Organização em seções (### Tabelas, ## Gráficos).

- Dados_brutos.py (dentro da pasta pages/)
Script para exibir os dados brutos (sem agregações) no Streamlit, acessível como uma página separada no menu lateral.

- .streamlit/config.toml
Arquivo de configuração do Streamlit (ex.: cores, tema, fonte).

- requirements.txt
Lista os pacotes necessários (ex.: streamlit, pandas, plotly) para rodar o projeto.

## ⚙️ Tecnologias e Bibliotecas

- Python 3
- Pandas
- Streamlit
- Requests
- Plotly.express
