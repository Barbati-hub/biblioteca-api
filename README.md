1 - python3 -m venv venv
2 - django-admin startproject libray .
django-admin startapp books

atualizar django

4 - python3 -m pip install django
5 - python3 manage.py migrate - para criar as tabelas

6 - python3 manage.py runserver - para rodar o projeto
7 - pip3 install restframework
8 - pip install django-rest-framework 


TODA VEZ QUE FOR FEITA MUDANÇAS NOS MODELS FAZER UM MAKEMIGRATIONS PARA ATUALZIAR AS INFORMATIONS

9 - python3 manage.py makemigratinos
10 - python3 manage.py migrate




DOCKER
docker build -t app .


docker run -p 8888:80

docker run -d -p 8080:80 --name bibliotecadjango app


-------- ----------------
GOOGLE CLOUD
logar - gcloud auth login
nomer a imagem - docker tag app gcr.io/api-image-django-378719/app
mostrar as imagens do docker - docker images

docker push gcr.io/api-image-django-378719/app



DENTRO DO GOOGLE CLOUD
PROCURAR Container Registry E ATIVAR