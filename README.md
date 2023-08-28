# CRUD Simples
Este repositório contém um CRUD simples construído com o intuito de praticar a criação de CRUD com Java Spring.

## Instalação

1. Clone o repositório:

```bash
$ git clone https://github.com/mateus-montagnini/Crud-Project.git
```

2. Instale as dependências com Maven

## Uso

1. Inicie a aplicação com Maven 
2. A API está acessível em http://localhost:8080


## API Endpoints
A API fornece os seguintes endpoints:

```markdown
GET /product - Retorna todos os produtos.

POST /product - Registra um novo produto.

PUT /product - Atualiza dados de um produto.

DELETE /product/{id} - Torna um produto inativo.
```

## Banco de Dados
O projeto usa o PostgreSQL como banco de dados e as migrations foram criadas com o Flyway

Para instalar o PostgreSQL localmente você pode [clicar aqui](https://www.postgresql.org/download/).
