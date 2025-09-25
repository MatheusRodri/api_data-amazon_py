# 🚀 DATA AMAZON

O projeto se trata, do consumo da API da Amazon, disponibilizado pelo site rapidapi.com, para obter dados dos produtos mais vendidos em uma determinada categoria e logo em seguida uma breve analise dos dados.

---

## ✅ Requisitos

Antes de executar o projeto, certifique-se de ter os seguintes requisitos instalados:

- Python 3.8 ou superior
- Editor de código (VSCode, PyCharm, etc.)
---

## 🛠 Tecnologias Utilizadas

O projeto foi construído com as seguintes tecnologias:

### 🔙 Back-end
- Python
	- Requests
	- Pandas

---

## ▶️ Como Executar o Projeto

Siga os passos abaixo para rodar o projeto localmente:

- Clone ou baixe o repositório
- Navegue até o diretório do projeto pelo terminal
- Crie o ambiente e instale as dependências com o comando:
  ```bash
  conda env create -f environment.yml
  ```
- Duplique o arquivo `header-sample.py` para `header.py` e adicione as credenciais da sua conta do rapidapi.com
- Opcional, pode deletar o arquivo `amazon-data.json` para gerar um novo arquivo com a função `main.py`
- Execute o script com `python main.py` para gerar o arquivo JSON ( Caso tenha deletado o arquivo `amazon-data.json`)
- Execute o notebook `main.ipynb` para ler o arquivo JSON e fazer os tratamentos nos dados