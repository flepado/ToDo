# Projeto Python-Django

Este é um projeto de python que usa o framework Django para criar uma aplicação web. O objetivo do projeto é demonstrar as principais funcionalidades do Django.

## Requisitos

Para executar este projeto, você precisa ter instalado:

- Python 3.9 ou superior

Você também precisa instalar as seguintes bibliotecas usando o comando `pip install`:

- django
- python-decouple
- dj-database-url
- black

## Instalação

Para iniciar o projeto, siga os seguintes passos:

1. Clone o repositório usando o comando `git clone https://github.com/flepado/ListaToDo.git`
2. Navegue até a pasta do projeto usando o comando `cd ListaToDo`
3. Crie um ambiente virtual usando o comando `python -m venv .venv`
4. Caso ocorra um erro de permissão utilize o comando `Set-ExecutionPolicy -Scope Process -ExecutionPolicy bypass`
5. Ative o ambiente virtual usando o comando `./.venv\Scripts\activate`
6. Execute as migrações do banco de dados usando o comando `python manage.py migrate`
7. Crie um usuário administrador usando o comando `python manage.py createsuperuser`
8. Rode o servidor de desenvolvimento usando o comando `python manage.py runserver`
9. Para acessar o projeto, você pode acessar o seguinte endereço no seu navegador `http://localhost:8000/`

<!--
Você verá uma página inicial com um menu de navegação para as diferentes seções do projeto, tais como:

- Home: a página inicial do projeto
- Atividades: uma lista de atividades cadastradas no banco de dados
- Novas atividades: um formulário para adicionar novas atividades ao banco de dados
- Login: uma página para fazer login na aplicação
- Admin: uma página para acessar o painel de administração do Django 

## Testes

Para executar os testes do projeto, você pode usar o comando `python manage.py test`. Isso irá rodar os testes definidos na pasta `tests` do projeto.
-->

## Contribuição

Se você quiser contribuir para este projeto, sinta-se à vontade para fazer um fork, criar uma branch, fazer as suas alterações e enviar um pull request.
