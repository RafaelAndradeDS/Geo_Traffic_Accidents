# Análise Geoespacial de Acidentes de Trânsito

## Visão Geral

Este projeto tem como objetivo a análise de acidentes de trânsito utilizando dados geoespaciais. Através de mapas interativos e análises estatísticas, buscamos identificar padrões, áreas de maior risco e possíveis fatores que influenciam na ocorrência dos acidentes.

## Tecnologias Utilizadas

- **Python 3.x**
- **Pandas** para manipulação de dados
- **Geopandas** para análise geoespacial
- **Folium** para visualização de mapas
- **Matplotlib / Seaborn** para visualizações estatísticas
- **Jupyter Notebook** para execução interativa do projeto

## Estrutura do Projeto

```
/
|-- data/                 # Pasta contendo os datasets
|   |-- acidentes.csv      # Base de dados principal
|
|-- notebooks/            # Jupyter Notebooks com a análise
|   |-- analise_acidentes.ipynb
|
|-- scripts/              # Scripts Python para manipulação de dados
|   |-- processa_dados.py
|
|-- outputs/              # Resultados da análise (gráficos, mapas, relatórios)
|
|-- README.md             # Documentação do projeto
```

## Instalação e Execução

### 1. Clonar o repositório
```bash
git clone https://github.com/seu-usuario/nome-do-repositorio.git
cd nome-do-repositorio
```

### 2. Criar ambiente virtual e instalar dependências
```bash
python -m venv venv
source venv/bin/activate   # No Windows: venv\Scripts\activate
pip install -r requirements.txt
```

### 3. Executar a análise no Jupyter Notebook
```bash
jupyter notebook notebooks/analise_acidentes.ipynb
```

## Funcionalidades

- **Carga e limpeza de dados**: Remoção de valores ausentes, conversão de tipos e tratamento de outliers.
- **Mapeamento de acidentes**: Geração de mapas interativos com Folium.
- **Análise estatística**: Geração de histogramas, boxplots e correlações.
- **Mapas de calor**: Identifica regiões com alta ocorrência de acidentes.

## Possíveis Melhorias

- Integração com dados meteorológicos para correlação com condições climáticas.
- Implementação de um modelo preditivo para estimar riscos de acidentes.
- Desenvolvimento de um dashboard interativo com Streamlit ou Dash.

