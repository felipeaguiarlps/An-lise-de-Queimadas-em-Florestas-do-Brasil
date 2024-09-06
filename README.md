# Análise de Queimadas na Amazônia

Este projeto tem como objetivo analisar os dados de queimadas na Floresta Amazônica e correlacionar com a diminuição do bioma na cidade de Araguari, Minas Gerais. Através de técnicas de análise de dados utilizando Python, visualizamos o impacto das queimadas e seus efeitos na biodiversidade da região.

## Índice
- [Sobre o Projeto](#sobre-o-projeto)
- [Estrutura dos Dados](#estrutura-dos-dados)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Instalação e Uso](#instalação-e-uso)
- [Resultados Obtidos](#resultados-obtidos)
- [Contribuindo](#contribuindo)
- [Licença](#licença)

## Sobre o Projeto

O projeto analisa dados de queimadas na Floresta Amazônica, obtidos de fontes públicas de dados ambientais. A partir desses dados, investigamos a relação entre o aumento de queimadas e a degradação da floresta, com foco na cidade de Araguari, MG.

O propósito da análise é fornecer insights sobre a gravidade do impacto das queimadas ao longo do tempo, visando contribuir para políticas públicas e conscientização ambiental.

## Estrutura dos Dados

O arquivo de dados usado no projeto é um arquivo CSV contendo os seguintes campos principais:
- `date`: A data em que o evento de queimada foi registrado.
- `latitude`: A latitude do local da queimada.
- `longitude`: A longitude do local da queimada.
- `estado`: O estado brasileiro onde a queimada ocorreu.
- `focos`: A quantidade de focos de incêndio registrados.

## Tecnologias Utilizadas

As principais ferramentas e bibliotecas utilizadas no projeto são:

- **Python 3.8+**
- **Jupyter Notebook**: Para execução dos códigos e análise interativa.
- **Pandas**: Para manipulação e análise de dados.
- **Matplotlib**: Para visualização de gráficos.
- **Seaborn**: Para visualizações estatísticas avançadas.

## Instalação e Uso

### Pré-requisitos

Certifique-se de ter Python e o `pip` instalados no seu ambiente. Você também precisará instalar as bibliotecas usadas no projeto.

### Instalação

Clone este repositório:
   ```bash
   git clone https://github.com/felipeaguiarlps/An-lise-de-Queimadas-em-Florestas-do-Brasil.git

####Instale as dependências necessárias:

pip install pandas matplotlib seaborn jupyter

####Abra o Jupyter Notebook para rodar as análises:

jupyter notebook

####Carregue o arquivo CSV com o caminho correto no notebook e rode as células.

df = pd.read_csv('caminho/para/seu/arquivo.csv', encoding_errors='ignore', parse_dates=['date'])


