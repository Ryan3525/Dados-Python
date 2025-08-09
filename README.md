# Dados-Python

Este projeto é um **dashboard interativo** desenvolvido em **Python** utilizando **Streamlit**, **Pandas** e **Plotly** para explorar e visualizar informações salariais na área de dados ao longo dos anos.

## Funcionalidades

- **Filtros dinâmicos** para:
  - Ano
  - Senioridade
  - Tipo de contrato
  - Tamanho da empresa
- **Métricas principais (KPIs)**:
  - Salário médio
  - Salário máximo
  - Total de registros
  - Cargo mais frequente
- **Visualizações interativas**:
  - Top 10 cargos por salário médio
  - Distribuição de salários anuais
  - Proporção de trabalho remoto, híbrido ou presencial
  - Mapa mundial com salários médios de Cientistas de Dados
- **Tabela de dados filtrados** para consulta detalhada

## Tecnologias Utilizadas

- [Python](https://www.python.org/)
- [Streamlit](https://streamlit.io/)
- [Pandas](https://pandas.pydata.org/)
- [Plotly](https://plotly.com/python/)

## Instalação e Execução

1. **Clone este repositório**
   ```bash
   git clone https://github.com/Ryan3525/Dados-Python.git
   cd Dados-Python

### 2. Criação da Venv (opcional)
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Window

# 3.Instalação das bibliotecas
pip install -r requirements.txt

# 4.Execute o Aplicativo
streamlit run app.py

# 5. Acesse no navegador
http://localhost:8501


## Estrutura do Projeto
📂 Dados-Python
 ├── app.py               # Código principal do dashboard
 ├── requirements.txt     # Lista de dependências do projeto
 └── README.md            # Documentação do projeto

## Fonte de Dados

https://raw.githubusercontent.com/vqrca/dashboard_salarios_dados/refs/heads/main/dados-imersao-final.csv
