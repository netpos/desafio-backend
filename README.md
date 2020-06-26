# Desafio Backend - NetPOS

## Problema

A NetPOS fornece uma aplicação para que empresários consigam ter uma visão clara do seu negócio e como otimizar suas vendas e lucros. 
Para completar essa missão iremos construir uma aplicação para que esses empresários cadastrem seus produtos e gerencie seu estoque.

O processo começa com a criação de um Usuário (UserAccount), os campos de nome, e-mail e Senha são obrigatórios, sendo **o e-mail é um campo único** para identificar o empresário.

O sistema deve ser capaz de listar os usuários e trazer informações detalhadas de um usuário. 
Deve ser possível filtrar os resultados pelo nome. 
Sua busca deve considerar resultados que comecem com a string especificada no filtro. Não é a necessário tratar acentos.

Após o seu usuário ser criado você deve ser capaz de **criar, alterar, listar e buscar um produto** especifico. 
Um produto deve ter um código, nome, preço e estoque, sendo que o **código deve ser unico para a conta desse usuário**.
Deve ser possivel movimentar o estoque dos produtos, lembrando que **não é permitido que um produto tenha acima de 1000 unidades em estoque e ele não pode ser negativo**. 

**Não deve ser possivel um usuário listar produtos de outras contas.**
**Nos endpoints de produto, o ID do usuário deve ser passado via header.**

Sua tarefa é desenvolver uma API capaz de cumprir os requisitos especificados.

A especificação da API está disponível no nosso git no formato Swagger 2.0, e pode ser visualizado utilizando o Swagger.
Você pode abri-la no [Swagger Editor](https://editor.swagger.io) ou utilizar a [a imagem do docker](https://hub.docker.com/r/swaggerapi/swagger-editor/) para rodar local.

## Instruções
Para ajudar e evitar perda de tempo, segue uam estrutura básica para o desenvolvimento da sua solução utilizando a plataforma Java (Spring Boot).
**Dica: Indicamos que você use o banco de dados H2, se utilizar alguma outra solução de banco e for necessário enviar o script para criação da estrutura.**

## Avaliação
A avaliação será constituída de duas etapas principais: Correção objetiva e qualitativa.
**Caso você não se sinta à vontade com a arquitetura proposta, você pode apresentar sua solução utilizando frameworks diferentes**. 

A correção objetiva será realizada através de um script automatizado.
A correção qualitativa será com base nos seguintes critérios:

- Modelagem de Dados
- Domínio da Linguagem
- Legibilidade do Código
- Estrutura do Código
- Organização do Código
- Design Patterns
- Manutenibilidade do Código
- Diferenciais: Testes Unitários e Cobertura de Testes

## Como submeter

Envie um email para **vagas@netpos.com.br** com seu Nome, Telefone para contato e a solução. 
Se já estiver em processo de avaliação, enviar o email com cópia para o seu recrutador.

**Lembre-se de não enviar arquivos compilados e configurações de IDE ao submeter a sua solução.**