Padrões de Projeto Java com Spring Boot

# 📋 Sobre o Projeto
Este repositório contém uma aplicação Spring Boot desenvolvida como laboratório para estudos de padrões de projeto em Java. O projeto inclui uma API documentada com Swagger/OpenAPI e uma configuração de ambiente completa.

# 🚀 Tecnologias e Ferramentas
Spring Boot - Framework principal para desenvolvimento da aplicação

Java 100% - Linguagem de programação

Maven - Gerenciamento de dependências e build

Swagger/OpenAPI - Documentação interativa da API

Git - Controle de versão


## 📁 Estrutura do Projeto

```text
lab-padroes-projeto-java-springboot/
├── .mvn/
│   └── wrapper/              # Wrapper do Maven
├── src/
│   ├── main/
│   │   ├── java/             # Código-fonte da aplicação
│   │   └── resources/        # Configurações (application.yml/properties)
│   └── test/                 # Testes automatizados
├── mvnw                      # Maven Wrapper (Unix)
├── mvnw.cmd                  # Maven Wrapper (Windows)
├── pom.xml                   # Configuração do Maven e dependências
├── .gitignore                # Arquivos ignorados pelo Git
├── .gitattributes            # Atributos do Git
└── README.md                 # Documentação do projeto

```

## 🔧 Configuração e Dependências
O arquivo pom.xml contém as configurações e dependências do projeto, incluindo:

Dependências do Spring Boot

Configuração do Swagger/OpenAPI para documentação da API

Configurações do Maven para build e execução



## 📚 Documentação da API
O projeto inclui configuração do Swagger/OpenAPI, proporcionando:

Documentação interativa dos endpoints da API

Interface para teste dos endpoints diretamente do navegador

Especificação OpenAPI para integração com outras ferramentas

## 🎯 Objetivo de Aprendizado
Este repositório serve como ambiente de laboratório para estudo e aplicação de padrões de projeto em conjunto com o ecossistema Spring Boot, focando em boas práticas de desenvolvimento de APIs e documentação.

## 💻 Como Executar
Clone o repositório

Execute mvn spring-boot:run ou use o wrapper (./mvnw spring-boot:run)

Acesse a documentação da API em http://localhost:8080/swagger-ui.html
