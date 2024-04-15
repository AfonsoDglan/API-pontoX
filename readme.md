# API - APP PontoX
![Built with](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=green)
![Built with](https://img.shields.io/pypi/pyversions/Django) 


Este projeto é uma aplicação web para gerenciamento de ponto eletrônico lista de contatos, desenvolvida utilizando Django para o backend, Next.js para o frontend, e Docker com Docker Compose para orquestração de containers. O banco de dados utilizado é o PostgreSQL.
![](https://c.tenor.com/wwRvaO_vk4IAAAAd/tenor.gif)

# Pré-requisitos

- [Docker e docker-compose](https://docs.docker.com/engine/install/)

# Execução com docker-compose

```sh
git clone https://github.com/AfonsoDglan/API-pontoX.git
```

```sh
cd API-pontoX
```

```sh
docker-compose up -d --build
```

- Acesse a API em [http://localhost:8000/](http://localhost:8000/)

# Desenvolvimento

Para executar o servidor de desenvolvimento da API, você pode executar os seguintes comandos:

API - backend (Django):

```sh
pip install -r requirements.txt # (apenas na primeira execução ou se houverem novas dependências)
python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver 0.0.0.0:8000
```

# Contribuindo

Contribuições são bem-vindas! Se você encontrou algum problema, tem uma ideia para uma nova funcionalidade ou simplesmente quer melhorar o projeto, sinta-se à vontade para abrir uma issue ou enviar um pull request.

# Licença

Este projeto está licenciado sob a Licença MIT.
