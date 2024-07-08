# Spring Web Security with Database

Este projeto é uma implementação de segurança com Spring Security, utilizando autenticação em memória e roles de usuários, além de integração com Spring Data JPA e banco de dados H2.

## Requisitos

- Java 1.8
- Maven 3.6+
- IntelliJ IDEA ou outra IDE de sua preferência

## Dependências

O projeto utiliza as seguintes dependências principais:

- `spring-boot-starter-security`: Para configuração de segurança.
- `spring-boot-starter-data-jpa`: Para integração com JPA.
- `spring-boot-starter-web`: Para criar aplicações web.
- `h2`: Banco de dados em memória para testes.
- `spring-boot-starter-test`: Para testes.
- `spring-security-test`: Para testes de segurança.

## Configuração de Segurança

A configuração de segurança está definida na classe `WebSecurityConfig`. 

## Executando o Projeto

Para executar o projeto, você pode usar sua IDE preferida ou executar o comando Maven a partir da linha de comando:

### Usando a IDE (IntelliJ IDEA)

1. Importe o projeto como um projeto Maven.
2. Navegue até a classe principal `SpringWebSecurityDatabaseApplication`.
3. Clique com o botão direito do mouse e selecione `Run`.

### Usando a linha de comando

1. Navegue até o diretório raiz do projeto.
2. Execute o seguinte comando Maven:

```bash
mvn spring-boot:run
```

## Testando a Aplicação

Você pode acessar a aplicação em [http://localhost:8080](http://localhost:8080). 

Utilize as credenciais configuradas (`user/user123` para usuários e `admin/master123` para administradores) para fazer login e testar as diferentes permissões de acesso.

