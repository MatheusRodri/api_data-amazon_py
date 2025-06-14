# Sobre o projeto

O projeto se trata um conjunto com duas funções:
A primeira função(main.py) é fazer a requisição a uma API da Amazon, disponibilizado pelo site rapidapi.com e gerar um arquivo JSON com os dados dos mais vendidos de uma determinada categoria de produtos.
A segunda função(main.ipynb) é um notebook Jupyter que lê o arquivo JSON gerado pela primeira função e faz alguns tratamentos nos dados.



# Tecnologias utilizadas
- Back end
    - Python



# Como executar o projeto

- Clone ou baixe o repositório
- Inicie o ambiente virtual com `python -m venv .venv`
- Ative o ambiente virtual com `source .venv/bin/activate` (Linux ou MacOs) ou `.venv\Scripts\activate` (Windows) 
- Instale as dependências com `pip install -r requirements.txt`
- Duplique o arquivo `header-sample.py` para `header.py` e adicione as credenciais da sua conta do rapidapi.com
- Opcional, pode deletar o arquivo `amazon-data.json` para gerar um novo arquivo com a função `main.py`
- Execute o script com `python main.py` para gerar o arquivo JSON ( Caso tenha deletado o arquivo `amazon-data.json`)
- Execute o notebook `main.ipynb` para ler o arquivo JSON e fazer os tratamentos nos dados

