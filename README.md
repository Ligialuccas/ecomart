# Ecomart

Projeto desenvolvido com **Spring Boot** para testes e integração com **OpenAI** utilizando o **Spring AI**.

## 🚀 Tecnologias Utilizadas

- **Java 21**
- **Spring Boot 3.5.4**
- **spring-boot-starter-web** — para criação da API REST
- **spring-boot-devtools** — para desenvolvimento com hot reload
- **spring-boot-starter-test** — para testes unitários e de integração
- **Spring AI** — integração com modelos OpenAI (`spring-ai-starter-model-openai`)
- **jtokkit** — biblioteca para manipulação de tokens de linguagem natural
- **Maven** — gerenciamento de dependências e build

## 🔗 URLs Importantes

| Endpoint        | Método | Descrição                                                                 | Exemplo de Uso                                                                 |
|-----------------|--------|---------------------------------------------------------------------------|--------------------------------------------------------------------------------|
| `/gerador`      | GET    | Gera 5 produtos ecológicos a partir de um prompt pré-definido.            | `http://localhost:8080/gerador`                                                |
| `/categorizador`| GET    | Recebe o nome de um produto e retorna a categoria correspondente.         | `http://localhost:8080/categorizador?produto=Escova%20de%20dentes`             |
| `/imagem`       | GET    | Recebe o nome de um produto e retorna a imagem gerada para ele.           | `http://localhost:8080/imagem?prompt=sacola%20reutilizavel`                    |
