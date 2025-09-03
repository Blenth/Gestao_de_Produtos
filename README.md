# Gestão de Produtos 

Todos os arquivos presentes são modelos base, todo texto precisa ser adicionado pelos comandos de install djando e venv


Comands => 
{
> pip install django ( instala Django )
> 
> python -m venv venv ( crear amiente virtual )
>
> django-admin startproject [meu_projeto] ( criar projeto )
> 
> souce venv\Scripts\activate or  venv\Scripts\activate ( ativar amiente virtual )
> 
> pip install -r requirements.txt ( lista todas as dependências do projeto e suas versões exatas )
>
> python manage.py makemigrations ( criar migração )
>
> pip install django-bootstrap-v5 ( instala bootstrap )
>
> python manage.py runserver ( rodar aplicação )
};



# Exemple altomatic installation

INSTALLED_APPS = [
    'django.contrib.admin',
    'django.contrib.auth',
    'django.contrib.contenttypes',
    'django.contrib.sessions',
    'django.contrib.messages',
    'django.contrib.staticfiles',
    'blog',  # app criado
    'bootstrap5', #Bootstrap 5
]

