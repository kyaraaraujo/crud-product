# API-CRUD

<div align="center">


<table>
  <tr align="center">
    <th>Java 11</th>
    <th>Spring Boot</th>
    <th>Dependências</th>
  </tr>
  <tr align="center">
    <td>
      <img alt="java logo" height="30" width="30" src="https://raw.githubusercontent.com/kyaraaraujo/kyaraaraujo/images/logos/java-logo-sem-nome.png">
    </td>
    <td>
      <img  alt="spring logo" height="30" width="40" src="https://raw.githubusercontent.com/kyaraaraujo/kyaraaraujo/images/logos/spring-logo.png">
    </td>
    <td >
      <span >MySQL, Lombok, JPA, Hibernate</span>
    </td>
  </tr>
</table>


| Status do Projeto  | 
|        :---:       |  
| Em desenvolvimento |   

|                       [Kyara Araújo](https://github.com/kyaraaraujo)                  |
|                                        :---:                                          |
| <img src="https://github.com/kyaraaraujo.png" width="80" alt="Foto de Kyara Araújo"/> |  



<br>


</div>


---


## Tópicos


[Objetivo](#objetivo) &nbsp;&nbsp; | &nbsp;&nbsp;
[Aprendizados / Utilizados](#aprendizados/utilizados) &nbsp;&nbsp; | &nbsp;&nbsp;
[Como usar](#como-usar) &nbsp;&nbsp; | &nbsp;&nbsp;
[Informações Extras](#informações-extras) &nbsp;&nbsp; | &nbsp;&nbsp;
[Referências](#referências) &nbsp;&nbsp;

<br>

## Objetivo:
O objetivo deste projeto é praticar API e utilizar como consulta de estudo.
Usado ações primitivas no banco de dados: CREATE, READ, UPDATE, DELETE para manipular os produtos.

## Aprendizados/Utilizados
- Spring boot
- Banco de dados relacional: MySQL
- Annotations Lombok e JPA
- Variáveis de ambiente no IntelliJ (para arquivo de configuração com o banco de dados `application.properties`)

## **Como Usar**
- Ter o JDK instalado
- Para compilar e executar: através de uma IDE que possa compilar e executar Java (ex: IntelliJ, Eclipse)
- Ter MySQL instalado

Após baixar o projeto, substituir as variáveis de ambiente do arquivo `application.properties` com suas informações:
  ```properties
  spring.datasource.username = usuárioDoSeuBancoDeDados
  spring.datasource.password = senhaDoSeuBancoDeDados
```

## Informações Extras
### Criar variáveis de ambiente no IntelliJ
Serve para que não se envie dados sensíveis ao repositório, mantendo a informação localmente.

1. Acessar a configuração de execução do projeto

![](https://raw.githubusercontent.com/kyaraaraujo/kyaraaraujo/images/variaveis-ambiente/passo1.png)


2. Em `Environment variables` informar variáveis e valor separadas por ; ou clicar no ícone para informar como uma tabela.
   1. Caso deseje informar na linha, após isso basta clicar em `Apply` e `OK`.
   ![](https://raw.githubusercontent.com/kyaraaraujo/kyaraaraujo/images/variaveis-ambiente/passo2.png)
   
   2. Caso clique no ícone no final da linha à direita, abrirá uma outra janela, após inserir ao lado esquerdo o nome da variável e ao lado direito o valor, basta clicar em `OK`, `Apply` e `OK`.
   ![](https://raw.githubusercontent.com/kyaraaraujo/kyaraaraujo/images/variaveis-ambiente/passo3.png)

As variáveis precisam ter o mesmo nome que foi informado no seu arquivo de configuração com o banco de dados, nesse caso 
o arquivo `application.properties` estaria escrito:
  ```properties
  spring.datasource.username = ${YOUR_VARIABLE_USERNAME}
  spring.datasource.password = ${YOUR_VARIABLE_PASSWORD}
```



## Referências
- [Spring Boot, MySQL, JPA, Hibernate Restful CRUD API Example](https://www.youtube.com/watch?v=IucFDX3RO9U)


---
⬆ [Voltar ao início](#api-crud)

<br>
