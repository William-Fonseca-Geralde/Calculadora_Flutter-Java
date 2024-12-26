# Projeto Calculadora em Flutter e Java

## Introdução

Este repositório apresenta um projeto de exemplo que integra o Flutter como front-end e o Spring como back-end para construir uma aplicação de calculadora. O objetivo deste projeto é entender melhor como essas duas tecnologias podem ser utilizadas juntas em uma aplicação.

## Sobre os Frameworks

### Flutter (Dart)

Flutter é um framework de desenvolvimento de interfaces de usuário criado pela Google. Ele permite criar aplicações multiplataforma (iOS, Android, Web e Desktop) com uma única base de código, utilizando a linguagem de programação Dart.

#### Por que usar Flutter?

- Desenvolvimento rápido com hot reload;
- Interface de usuário customizável e responsiva;
- Suporte a multiplataforma.

### Spring (Java)

Spring é um framework de desenvolvimento em Java amplamente utilizado para criar aplicações web, microsserviços e APIs REST. É conhecido por sua flexibilidade e capacidade de integração com outras ferramentas e tecnologias.

#### Por que usar Spring?

- Suporte robusto para criação de APIs REST;
- Escalabilidade e performance para aplicações empresariais;
- Grande comunidade e ecossistema.

## Estrutura do Projeto

### Front-end (Flutter)

O front-end é responsável por:

- Exibir a interface de usuário da calculadora;
- Capturar as operações matemáticas solicitadas pelo usuário;
- Enviar essas operações para o back-end via API;
- Exibir o resultado retornado pelo back-end.

### Back-end (Spring)

O back-end é responsável por:

- Receber as operações matemáticas enviadas pelo Flutter;
- Realizar os cálculos necessários;
- Retornar os resultados ao front-end.

### Comunicação Front-end e Back-end

A comunicação entre Flutter e Spring é feita via requisições HTTP, utilizando o padrão REST. O Flutter consome as APIs expostas pelo Spring para obter os resultados dos cálculos.

## Configurações do Ambiente

### Requisitos

- Flutter SDK;
- Java 17+;
- Spring Boot CLI;
- Um editor de texto ou IDE, como Visual Studio Code.

### Instruções de Instalação

1. Clone o repositório
2. Acesse a pasta `frontend`.
3. Instale as dependências do Flutter:

   ```bash
   flutter pub get
   ```
4. E por fim, execute o projeto nessa pasta

   ```bash
   flutter run
   ```