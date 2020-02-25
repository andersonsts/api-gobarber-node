# CONCEITOS DOCKER
- Criação de ambientes isolados (container)
- Containers expõe portas para comunicação
- Imagem: Tecnologias que podem ser inseridas dentro de um container. Ex:
          MySQL, Postgres, Mongo...
- Container: Instancia de uma imagem. Ex: 3 BD's Postgres usando a imagem
             Postgres.
- Docker Registry (Docker Hub): Registro onde ficam todas as imagens do Docker.
  - Docker file: Receita para montagem de uma imagem.

# CONCEITOS SEQUELIZE
- É um ORM para Nodejs e bancos relacionais como Postgres, Mysql

## ORM
- Forma de abstrair nosso banco de dados.
- Tabelas do nosso BD viram models.

## MANIPULAÇÃO DE DADOS
- Sem SQL
- Apenas código JavaScript

## MIGRATIONS
- Controle de versão para base de dados;
- Cada arquivo contém instruções para criação, alteração ou remoção de tabelas
  ou colunas;
- Mantém a base de dados atualizada entre todos os desenvolvedores do time e também
  no ambiente de produção;
- Cada arquivo é uma migration e sua ordenação ocorre por data;
- JAMAIS edite uma migration que ja foi processada. Se for necessário realizar alguma
  modificação, é necessário realizar outra migration.
- É possivel desfazer uma migration se errarmos, enquanto estivermos em ambiente de               desenvolvimento.
- Cada migration deve realizar alteraçôes em apenas UMA tabela.

## SEEDS
- Populam nossa base de dados para desenvolvimento;
- Muito utilizado para popular dados para testes;
- Executaveis apenas por código;
- Jamais serão usados para produção;
- Caso sejam dados que precisam ir para produção, a própria migration pode manipular
  dados das tabelas;

## ARQUITETURA MVC
 ### MODEL ->
  Armazena a abstração do banco
 ### CONTROLLER ->
  Ponto de entrada das requisições de nossa aplicação. Incluem
  nossas regras de negócio.
 ### VIEW ->
  View é o retorno ao cliente. Em casos de aplicações envolvendo API REST, nossa view é apenas
  JSON que é retornado para nosso front-end, e manipulado pelo React e React Native.

## A FACE DE UM CONTROLLER
  Classes;
  Sempre retorna um JSON;
  Não chama outro controller/método;

  Apenas 5 métodos;
  Estou falando da mesma ENTIDADE? Se sim, criamos um controller.

  index() -> Listagem de users,
  show() -> Exibe um user,
  store() -> Cria um user,
  update() -> Atualiza um user,
  delete() -> Deleta um user


# CONCEITOS JWT (JSON WEB TOKEN)
- AUTENTICAÇÃO JWT
  POST http://api.com/sessions
  {
    "email": "anderson@gmail.com",
    "password": "123456"
  }

  Se tiver correto, o token jwt é gerado:
  dhbwuebfewnwubn324.324j1ifhf1uf1njfeh.12f33u7g811fub44n1

  A primeira parte até o primeiro ponto se chama Headers (tipo do token);
  A segunda parte até o proximo ponto se chama payload (podemos guardar algumas informações
            aqui dentro como o id do user)
  A terceira parte se chama assinatura do token (Garante que o token não foi modificado por               outro usuário por exemplo)








