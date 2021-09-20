# Documentação OneCar

![Sem título-1_Prancheta 1](https://user-images.githubusercontent.com/56441318/133950991-44ac40d3-c041-4c7a-b35b-bbf84abc9c37.png)

O OneCar foi desenvolvido para melhoria contínua de um produto já existente de nosso cliente.  O projeto está sendo desenvolvido à partir de uma parceria com a [Fatec São José dos Campos - Prof. Jessen Vidal](https://fatecsjc-prd.azurewebsites.net/). 

## Disciplinas Integradas

- Segurança da Informação
  Prof. Me. Eduardo Sakaue

- Redes de Computadores
  Prof. Jean Carlos Lourenço Costa

- Programação para Dispositivos Móveis
  Prof. Dr. Gerson da Penha Neto

- Laboratório de Banco de Dados
  Prof. Me. Fernando Masanori Ashikaga

## Time

- José Danrley - PO - [LinkedIn](https://www.linkedin.com/in/jos%C3%A9-danrley-069827191)
- Raquel Ribeiro - Scrum Master - [LinkedIn](https://www.linkedin.com/in/raquel-rodrigues-ribeiro-a9537818b)
- Cristiane Rodrigues - DEV Team - [LinkedIn](https://www.linkedin.com/in/cristiane-rodrigues-20b3b61b2)
- Luis Guilherme - DEV Team - [LinkedIn](https://www.linkedin.com/mwlite/in/luis-guilherme-a17b58185)
- Ygor Melo - DEV Team - [LinkedIn](https://www.linkedin.com/in/ygor-melo-18a172214)


## Objetivo

Desenvolver um Portal de anúncios de vendas de carros.

## O Projeto

Trata-se de uma aplicação Web e Mobile para anúncios de vendas de carros. É possível que o anunciante faça o upload de um csv contendo informações de usuários e anúncios. Cada anunciante tem acesso ao número de visualizações e interesses em seu anúncia e se comunica com o comprador através de um chat do sistema.

### Requisitos Funcionais

- Importar arquivos estruturados (csv) com os dados do anúncio e com os dados de anunciantes/usuário e a possibilidade de importar as fotos do anúncio;

- O sistema deve cadastrar automaticamente a senha para o primeiro acesso, obrigando a alteração no momento que o usuário realizar o login;

- Comunicação entre comprador e vendedor dentro do sistema em tempo real;

- Painel administrativo do anúncio, para pausar o anúncio e visualizar informações importantes como quantidade de acessos / quantidade de contatos recebidos;

- Alguns anunciantes são pessoas físicas, portanto, alguns dados devem ser sigilosos;

- Funcionalidade para pesquisa de veículos anunciados;

- Possibilidade de realizar a exclusão definitiva dos usuários/anúncios/comprador;

- Gerador de relatórios.

### Requisitos Não Funcionais

- LGPD;

- Alta disponibilidade (99%);

- Segurança da informação;

- A expectativa de anúncios ativos por mês é de 7 milhões;

- O sistema deverá ser intuitivo, pois, não contará com manual de utilização e atenderá a todo tipo de público;

- Desenho da Arquitetura aplicação;

- Documento de implantação;

- Documento de estratégia de branchs/versionamento;

- Documentação das APIs;

- Relatório com o histórico do build automatizado;

- A quantidade de visualizações do anúncio, é extremamente confidencial, os usuários não podem visualizar dados de outros anúncios.

### Tecnologias utilizadas

- NodeJS
- Typescript
- PostgreSQL
- MongoDB
- ReactJS
- Styled Components
