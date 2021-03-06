# DSVendas 
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/valsonpereira/projeto-sds3/blob/master/LICENSE) 

# Sobre o projeto

DSVendas é uma aplicação full stack web com API REST Spring Boot e React desenvolvida durante a 3ª edição da **Semana DevSuperior** (#sds3), evento organizado pela [DevSuperior](https://devsuperior.com.br "Site da DevSuperior").

A aplicação consiste em exibir um dashboard implementado em ReactJS a partir de dados fornecidos por uma API REST construída com Spring Boot para análise de desempenho de vendas por diferentes perspectivas. 

### Link da Aplicação em produção 
https://valsonpereira-dsvendas.netlify.app/

Obs.: Em razão do deploy do back-end ser realizado utilizando o plano gratuito do Heroku, o dashboard pode levar alguns segundos para exibir os dados.


## Layout
![Web 1](https://raw.githubusercontent.com/valsonpereira/my-assets/main/sds3/home.png)

![Web 2](https://raw.githubusercontent.com/valsonpereira/my-assets/main/sds3/dashboard.png)

![Web 3](https://raw.githubusercontent.com/valsonpereira/my-assets/main/sds3/tabela.png)

## Modelo conceitual
![Modelo Conceitual](https://raw.githubusercontent.com/valsonpereira/my-assets/main/sds3/sds3-mc.png)

# Tecnologias utilizadas
## Back-end
- Java 11
- Spring Boot
- Spring Data JPA 
- Maven
- H2 Database
## Front-end
- HTML / CSS / JS / TypeScript
- Bootstrap
- ReactJS
- Apex Charts
## Implantação em produção
- Back-end: Heroku
- Front-end web: Netlify
- Banco de dados: Postgresql

# Como executar o projeto

## Back-end
Pré-requisitos: Java 11

```bash
# clonar repositório
git clone https://github.com/valsonpereira/projeto-sds3.git

# entrar na pasta do projeto back-end
cd backend

# executar o projeto
./mvnw spring-boot:run
```

## Front-end 
Pré-requisitos: npm / yarn

```bash
# clonar repositório
git clone https://github.com/valsonpereira/projeto-sds3.git

# entrar na pasta do projeto front-end
cd frontend

# instalar dependências
yarn install

# executar o projeto
yarn start
```

# Autor

Valson Pereira

https://www.linkedin.com/in/valson-java-developer
