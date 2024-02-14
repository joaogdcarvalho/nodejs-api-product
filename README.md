# NODEJS API PRODUCT

## Sobre o Projeto

O NodeJS API Product é um projeto voltado para o desenvolvimento de uma API REST utilizando Node.js. Esta aplicação permite a criação, leitura, atualização e exclusão (CRUD) de produtos, fornecendo um conjunto de endpoints para interação com o banco de dados.

## Estrutura do Projeto

O projeto está organizado da seguinte forma:

```
src/
|-- controllers/
|   |-- ProductController.js
|-- models/
|   |-- Product.js
|-- routes.js
|-- package-lock.json
|-- package.json
|-- README.md
|-- server.js
```

## Funcionalidades Implementadas

- Criação de registros de produtos.
- Listagem de produtos com paginação.
- Implementação do CRUD (Create, Read, Update, Delete) para produtos.
- Adição de CORS para permitir o acesso de diferentes origens à API.

## Tópicos Abordados

- Utilização do Node.js para o desenvolvimento de uma API REST.
- Integração com banco de dados MongoDB utilizando Mongoose.
- Implementação de endpoints para interação com os recursos da API.
- Configuração do CORS para permitir solicitações de diferentes origens.
- Utilização do Nodemon para reinicialização automática do servidor durante o desenvolvimento.

## Como Executar o Projeto

### Pré-requisitos

Antes de começar, é necessário ter instalado na máquina:
- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/) (ou uma instância acessível de MongoDB)

### Rodando a Aplicação

1. Clone o repositório:
    ```bash
    git clone https://github.com/seu-usuario/nodejs-api-product
    ```

2. Acesse a pasta do projeto:
    ```bash
    cd nodejs-api-product
    ```

3. Instale as dependências:
    ```bash
    npm install
    ```

4. Execute a aplicação:
    ```bash
    npm start
    ```

5. A API estará disponível em [http://localhost:3000](http://localhost:3000)

## Como Contribuir para o Projeto

Este projeto é de código aberto e contribuições são bem-vindas. Sinta-se à vontade para abrir issues relatando problemas ou sugerindo melhorias. Pull requests também são encorajados.

## Licença

Este projeto está licenciado sob a [Licença MIT](LICENSE).