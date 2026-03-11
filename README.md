# Flix App

Flix App é uma aplicação desenvolvida em Streamlit que consome uma API de filmes. O sistema permite visualizar e gerenciar informações relacionadas a filmes, atores, gêneros e avaliações.

## Aplicação Online

A aplicação pode ser acessada em:
https://seu-app.streamlit.app

## Requisitos

Certifique-se de que os seguintes itens estejam instalados em seu sistema:

- Python 3.7 ou superior
- Pip
- Dependências listadas no arquivo `requirements.txt`

## Instalação

Clone o repositório:

git clone https://github.com/pombinhagab/flix_app.git

Acesse a pasta do projeto:

cd flix_app

Crie e ative um ambiente virtual (opcional, mas recomendado).

### Windows

python -m venv venv
venv\Scripts\activate

### Linux / Mac

python -m venv venv
source venv/bin/activate

Instale as dependências do projeto:

pip install -r requirements.txt

## Execução do Projeto

Após instalar as dependências, execute o comando:

streamlit run app.py

Depois disso, a aplicação estará disponível em:

http://localhost:8501

## Estrutura do Projeto

flix_app/
│
├── app.py
├── requirements.txt
│
├── actors/
├── genres/
├── movies/
├── reviews/
└── login/

## Tecnologias Utilizadas

- Python
- Streamlit
- Requests
- Pandas
- Django REST Framework
