comando PowerShell para gerar o ambiente virtual (venv):
    "python -m venv .venv"

comando caso não seja permitido a criação de ambiente virtual:
    "Set-Execution -Scope Process -ExecutionPolicy bypass"

Comando para ativação da venv (Windows):
    "./.venv\Scripts\activate"

Bibliotecas necessarias:
(para a instalação utilize o "pip install" + o nome da biblioteca)
    - django
    - python-decouple
    - dj-database-url
    - black

Comando utilizado para rodar a aplicação:
    "python manage.py runserver"