# Sistema de Gestão de Vendas

Este é um projeto em Java que visa criar um Sistema de Gestão de Vendas usando Spring Boot. O sistema gerencia entidades como Usuários, Pedidos, Categorias e Produtos, permitindo operações de criação, atualização, exclusão e recuperação de informações.

## Pré-requisitos

Certifique-se de ter o seguinte instalado em seu ambiente de desenvolvimento:

- Java 17
- Spring Boot 3.2.4
- Banco de Dados H2 (em tempo de execução)
- IDE Java (recomendado, mas não obrigatório)

## Configuração do Banco de Dados

1. Certifique-se de ter o servidor H2 em execução.
2. O banco de dados é gerado automaticamente durante a inicialização da aplicação.

## Configuração do Projeto

1. Clone este repositório em sua máquina local.
2. Importe o projeto para sua IDE Java.

## Executando a Aplicação

1. Execute a aplicação Spring Boot.
2. Acesse a aplicação em seu navegador da web em `http://localhost:8080`.

## Funcionalidades

O sistema oferece as seguintes funcionalidades:

- **Gerenciamento de Usuários**: Cadastro, atualização, exclusão e obtenção de informações de usuários.
- **Gestão de Pedidos**: Criação, atualização, exclusão e obtenção de informações de pedidos.
- **Administração de Categorias**: Operações para adicionar, atualizar, excluir e obter detalhes de categorias.
- **Controle de Produtos**: Gerenciamento de produtos, incluindo adição, atualização, exclusão e obtenção de informações.

## Endpoints

1. **Usuários**:
    - Listar todos os usuários: `GET /users`
    - Obter um usuário específico: `GET /users/{id}`
    - Adicionar um novo usuário: `POST /users`
    - Atualizar informações de um usuário: `PUT /users/{id}`
    - Excluir um usuário: `DELETE /users/{id}`

2. **Pedidos**:
    - Listar todos os pedidos: `GET /orders`
    - Obter um pedido específico: `GET /orders/{id}`
    - Adicionar um novo pedido: `POST /orders`
    - Atualizar informações de um pedido: `PUT /orders/{id}`
    - Excluir um pedido: `DELETE /orders/{id}`

3. **Categorias**:
    - Listar todas as categorias: `GET /categories`
    - Obter uma categoria específica: `GET /categories/{id}`
    - Adicionar uma nova categoria: `POST /categories`
    - Atualizar informações de uma categoria: `PUT /categories/{id}`
    - Excluir uma categoria: `DELETE /categories/{id}`

4. **Produtos**:
    - Listar todos os produtos: `GET /products`
    - Obter um produto específico: `GET /products/{id}`
    - Adicionar um novo produto: `POST /products`
    - Atualizar informações de um produto: `PUT /products/{id}`
    - Excluir um produto: `DELETE /products/{id}`

## Estrutura do Projeto

```
src/
|-- main/
|   |-- java/
|   |   |-- com/
|   |       |-- educandoweb.course/
|   |           |-- sistema/
|   |               |-- controller/: Contém os controladores REST para cada entidade.
|   |               |-- model/: Contém as classes de modelo para Usuários, Pedidos, Categorias e Produtos.
|   |               |-- repository/: Contém as interfaces de repositório para acesso aos dados.
|   |               |-- service/: Contém as classes de serviço para lógica de negócios.
|-- resources/
    |-- application.properties: Arquivo de configuração Spring Boot para propriedades do aplicativo.
```
