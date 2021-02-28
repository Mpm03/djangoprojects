## Python Shell

Como iniciar o python shell

- > "C:\Arquivos de programas\Python39\python"

Como sair do python shell

- > exit()

## Ambiente Virtual em Python

Como criar um ambiente virtual para python

- > "C:\Arquivos de programas\Python39\python" -m venv myvenv

Como ativar o ambiente virtual

- > . myvenv/Scripts/activate

Como sair do ambiente

- > cd..


## Outros comandos do prompt

Como limpar o prompt

- > clear

Como criar a pasta _meuprojeto_

- > mkdir meuprojeto

Como entrar na pasta _meuprojeto_

- > cd meuprojeto

Como sair do diretório corrente

- > cd ..

## Projeto django

Como instalar as bibliotecas (com o ambiente virtual ativo)

```bash
pip install django
pip install djangorestframework
pip install pillow
```

Como criar o projeto (com o ambiente virtual ativo)

```bash
django-admin startproject dinoProject
cd dinoProject
```

Como criar um app

- > python manage.py startapp dinosaurs
- Incluir `'rest_framework'` e `'dinosaurs'` em `INSTALLED_APPS`, no arquivo _settings.py_
