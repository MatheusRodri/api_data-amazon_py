#  DATA AMAZON

> O projeto se trata, do consumo da API da Amazon, disponibilizado pelo site rapidapi.com, para obter dados dos produtos mais vendidos em uma determinada categoria e logo em seguida uma breve analise dos dados.


## Sumário

- [Funcionalidades](#funcionalidades)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Como Rodar](#como-rodar)
  - [Pré-requisitos](#pré-requisitos)
- [Como Usar](#como-usar)
- [Como Contribuir](#como-contribuir)


## Funcionalidades

- Faz uma requisição para a API da rapidata.com da Amazon
- Gera um arquivo JSON com os dados dos produtos mais vendidos em uma determinada categoria
- Realiza uma breve análise dos dados utilizando o Pandas

## Tecnologias Utilizadas

- Python
    - Biblioteca Requests
    - Biblioteca Pandas

## Como Rodar
### Pré-requisitos

Antes de executar o projeto, certifique-se de ter os seguintes requisitos instalados:
- Python 3.10 ou superior
- Anaconda
- Editor de texto ou IDE de sua preferência (Visual Studio Code, PyCharm, etc.)
- Databricks

## Como rodar

- Extrair os dados: (Caso queira apenas analisar os dados, pule essa etapa)
  - Clone ou baixe o repositório no seu computador
  - Navegue até o diretório do projeto pelo terminal
  - Crie o ambiente e instale as dependências com o comando:
    ```bash
    conda env create -f environment.yml
    ```
  - Renomeie o arquivo `header-sample.py` para `header.py` e adicione as credenciais da sua conta do rapidapi.com
  - Execute o script com `python main.py` para gerar o arquivo JSON

- Analisar os dados:
  - Dentro do Databricks:
    - Crie uma pasta
    - Dentro da pasta crie uma outra pasta chamada `data`
    - Faça o upload do arquivo `amazon-data.json` para a pasta `data`
    - Dentro da pasta principal, importe o notebook `main.ipynb`
    - Execute o notebook `main.ipynb` para realizar a análise dos dados.

## Como Contribuir

- Entre em contato comigo pelo [LinkedIn](https://www.linkedin.com/in/matheus-rodrigues-mrj/)
- Faço fork do repositório