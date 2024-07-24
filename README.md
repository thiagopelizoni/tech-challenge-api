# Tech Challenge 8SOAT

Tech Challenge do curso de Software Archictecture da FIAP.

# DDD

* [Diagramas Event Storm](https://miro.com/app/board/uXjVK0LIAuE=/)

# Requisitos

* [Docker](https://docs.docker.com/engine/install/)
* [Docker Compose](https://github.com/docker/compose)

# Versões

* Ruby 3.3.2
* Rails 7.1.3.4

Para verificar a versão de todas as bibliotecas, consulte o [Gemfile.lock](api/Gemfile.lock).

# Instalação

```
docker-compose up --build -d
```

A aplicação estará disponível em http://localhost:3000/.

Esta porta é definida no [docker-compose.yml](docker-compose.yml).

# Configurações

As configurações que estarão dentro dos containers por meio de variáveis de ambiente estão no arquivo [.env](.env).

# Estrutura

Os arquivos do projeto Rails estão dentro do diretório [api](api).