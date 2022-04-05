# redesolidariedade



Rede de Solidariedade
Projeto de Extensão IFSC 2021/2 - Rede Solidariedade

Para Rodar o Projeto:
1. certifique-se que está na raiz do repositorio [...]/redesolidariedade/"
2. crie uma venv "python -m venv venv"
3. ative a venv "venv\Scripts\activate"
4. instale o pip "python -m pip install --upgrade pip"
5. instale os requirements.txt "pip install -r requirements.txt"
6. va para a pasta app "cd app"
7. va para a raiz do app "cd main"
8. faça as migrations "python manage.py makemigrations"
9. migre os dados "python manage.py migrate"
10. crie um superuser "python manage.py createsuperuser"
11. Você deve gerar uma secretkey para o arquivo .env, que por padrão vai estar vazia.
12. rode o app "python manage.py runserver"
13. acesse a pagina Admin
14. crie um grupo de usuario chamado "user_admin" com todas as permissoes
15. crie um grupo de usuario chamado "user_common" sem nenhuma permissão
16. atribua ao super user criado anteriormente o grupo "user_admin"
17. acesse o Site
