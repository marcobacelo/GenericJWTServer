<<<<<<< HEAD
# JWT Server com Java 21 e Spring 6

Este é um projeto de exemplo para demonstrar como criar um servidor JWT simples usando Java 21 e Spring 6.

[![Java 21](https://img.shields.io/badge/Java-21-blue)](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html)
[![Spring 6](https://img.shields.io/badge/Spring-6-green)](https://spring.io/)
[![JWT](https://img.shields.io/badge/JWT-Authentication-yellow)](https://jwt.io/)
[![Gradle](https://img.shields.io/badge/Gradle-8.6-blue)](https://gradle.org/releases/)


## Requisitos

- Java 21
- Spring 6
- Maven

## Instalação

1. Clone este repositório:

```sh
git clone https://github.com/marcobacelo/Generic-JWT-Server.git
```
2. Tenha o Docker e o Docker Compose instalado e execute o seguinte comando:
```sh
docker-compose up -d
```

# API JWT com Java 21, Gradle 8.6 e Spring 6

Este é um projeto de exemplo de uma API simples que utiliza JWT (JSON Web Token) para autenticação em Java 21, Gradle 8.6 e Spring 6. JWT é um padrão aberto (RFC 7519) que define uma forma compacta e autocontida para transmitir informações de forma segura entre partes como um objeto JSON. Essa API utiliza as bibliotecas Java-JWT e JJWT para gerar e verificar tokens JWT.

## Recursos Principais

- **Autenticação JWT:** A API permite que os usuários se autentiquem e recebam tokens JWT válidos para acessar recursos protegidos.
- **Proteção de Rotas:** As rotas da API podem ser protegidas com JWT, garantindo que apenas usuários autenticados possam acessá-las.
- **Renovação de Tokens:** A API oferece um mecanismo para renovar tokens expirados sem a necessidade de autenticação novamente.

## Tecnologias Utilizadas

- **Java 21:** Linguagem de programação principal utilizada no desenvolvimento da API.
- **Gradle 8.6:** Ferramenta de automação de compilação e construção utilizada para gerenciar as dependências do projeto.
- **Spring 6:** Framework utilizado para criar a estrutura da aplicação web.
- **Java-JWT e JJWT:** Bibliotecas utilizadas para geração e verificação de tokens JWT.
