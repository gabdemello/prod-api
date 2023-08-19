
# Prod API 

O projeto Prod API se trata de uma RESTful API básica para gerenciamento de produtos. A API permite a criação, leitura, atualização e exclusão de registros de produtos, fazendo uso do banco de dados PostgreSQL para armazenamento de dados.

## O Por quê do projeto?

Este projeto foi criado com o objetivo de fornecer uma aplicação prática no conhecimento de Restful API utilizando Java com Spring Boot. 

## Observações da API

- A API segue os princípios do HATEOAS (Hypermedia as the Engine of Application State), fornecendo links relacionados para facilitar a navegação.

- Endpoints:
  - `POST /products`: Cria um novo registro de produto.
  - `GET /products`: Obtém uma lista de todos os produtos, incluindo links para detalhes individuais.
  - `GET /products/{id}`: Obtém detalhes de um produto específico, incluindo links relacionados.
  - `PUT /products/{id}`: Atualiza um produto existente com os dados fornecidos.
  - `DELETE /products/{id}`: Exclui um produto existente.

## Funcionalidades

- Criação, leitura, atualização e exclusão de registros de produtos.
- Uso de links HATEOAS para navegação e descoberta de recursos relacionados.

## Getting Started

Para executar o projeto localmente, siga as etapas abaixo:

1. **Clonar o repositório:**
   ```sh
   git clone https://github.com/gabdemello/prod-api.git   
   ```

2. **Configurar o PostgreSQL:**
   Certifique-se de ter um banco de dados PostgreSQL configurado. Atualize as configurações de conexão no arquivo `application.properties`.

3. **Build e Run:**
   Navegue até o diretório do projeto e execute o seguinte comando:
   ```sh
   ./mvnw spring-boot:run
   ```

4. **Acessar a API:**
   Acesse a API através do navegador ou de um cliente HTTP, utilizando as URLs dos endpoints descritos acima.

## Tecnologias Usadas

- Java
- Spring Boot
- Spring Validation
- PostgreSQL
- Maven

---

Este é um projeto de exemplo e pode ser aprimorado de várias maneiras, como autenticação, autorização, tratamento de erros mais detalhado e muito mais. Fique à vontade para explorar e expandir de acordo com suas necessidades e aprendizado contínuo.

Lembre-se de salvar este conteúdo em um arquivo com a extensão `.md`, como por exemplo `README.md`, no diretório raiz do seu projeto no GitHub. Certifique-se de substituir os espaços reservados (como `SEU_USUARIO` e `seu-projeto`) pelas informações reais do seu repositório e projeto.
