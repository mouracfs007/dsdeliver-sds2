# Projeto DS Delivery  
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/mouracfs007/dsdeliver-sds2/blob/main/LICENSE) 

# Sobre o projeto

DS Delivery é uma  **SPA** ( Single page application) ou uma aplicação full stack web e mobile construída durante a 2ª edição da **Semana DevSuperior** (#sds2), evento organizado pela [DevSuperior](https://devsuperior.com.br "Site da DevSuperior").

### Mas afinal, o que é realmente este projeto?

A aplicação consiste em um sistema de registro e entrega de pedidos, que em primeira mão pode parecer simples, mas é rico em detalhes. Existem vários objetos de interação no app mobile, tais como: ver os pedidos, produtos a serem entregues e a quantidade de minutos. Além disso, é possível acompanhar a navegação do pedido com objetos de interação de uma biblioteca de mapas totalmente gratuita. 

### E aí, ficou curioso para saber como que ficou o site construído ? 

É só clicar no link : https://mouracfsds2.netlify.app 

    Observação: Ao entrar na página home e clicar em " Fazer pedido " e estranhar que os produtos da seguinte página não foram listados, 
    espere de 30 segundos a 1 minuto, pois a aplicação (back end ) está hospedada no Heroku. 
    E como é um serviço gratuioto ele " adormecee " a aplicação após 30 minutos sem nenhum tipo de atividade. 

# Veja abaixo como ficou toda a elaboração e aplicação do projeto:

## Modelo conceitual
![Modelo Conceitual](https://github.com/mouracfs007/dsdeliver-sds2/blob/main/dsdeliver/assets/modelo-conceitual.png)

## Padrão de camadas adotado
![Modelo de camadas](https://github.com/mouracfs007/dsdeliver-sds2/blob/main/dsdeliver/assets/Modelo%20padr%C3%A3o%20de%20camadas%20adotado.png)


## Layout web - Página Home
![ front-web 1](https://github.com/mouracfs007/dsdeliver-sds2/blob/main/dsdeliver/assets/DSdeliver-Layout/HOME%20DELIVERY.png)
## Layout web- Seleção de produtos e mapas.
![front-web 2](https://github.com/mouracfs007/dsdeliver-sds2/blob/main/dsdeliver/assets/DSdeliver-Layout/SELECIONAR%20PRODUTOS.png)

## Layout mobile
![Mobile 1](https://github.com/mouracfs007/dsdeliver-sds2/blob/main/dsdeliver/assets/DSdeliver-Layout/Mobile%20P1.png)
![Mobile 2](https://github.com/mouracfs007/dsdeliver-sds2/blob/main/dsdeliver/assets/DSdeliver-Layout/Mobile%20P2.png)
![Mobile 3](https://github.com/mouracfs007/dsdeliver-sds2/blob/main/dsdeliver/assets/DSdeliver-Layout/Mobile%20P3.png)

## Checklist do back end

- Setup inicial do projeto
  - Dependências
  - Arquivos .properties
  - Configuração de segurança
- Modelo de domínio
  - Entidades e relacionamentos
  - Mapeamento objeto-relacional
  - Seed
- Criar endpoints
  - [GET] /products
  - [GET] /orders
  - [POST] /orders
  - [PUT] /orders/{id}/delivered
- Validar perfil dev
  - Base de dados Postgres local
  - Testar todos endpoints
- Preparar projeto para implantação
  - Arquivo system.properties
  - Profile prod -> commit
- Implantar projeto no Heroku
  - Criar app e provisionar Postgres
  - Criar base de dados remota
  - Executar comandos no Heroku CLI

# Tecnologias utilizadas
## Back end
- Java
- Spring Boot
- JPA / Hibernate
- Maven
## Front end
- HTML / CSS / JS / TypeScript
- ReactJS
- React Native
- MapBox


## Implantação em produção
- Back end: Heroku 
- Front end web: Netlify 
- Banco de dados: PostgreSQL

# Como executar o projeto

## Ferramentas que você deverá instalar no seu computador:
Pré-requisitos: 
- JDK 11
-	STS
-	Postman
- Postgresql 12 e pgAdmin
- Heroku CLI
- npm / yarn
- git ou Github desktop
- VS code

# Considerações finais / curiosidades!!!
  Quero desde já deixar meu agradecimento a toda equipe da [DevSuperior](https://devsuperior.com.br "Site da DevSuperior") em especial o professor Nélio Alves e o mestre do Front-end Washington Soares.
Foi uma experiência incrível e cheio de desafios pelo caminho , mas com total dedicação e foco consegui concluir o objetivo da criação do projeto ***DS Delivery***. Muitos se perguntam, o que é necessário para fazer este projeto?
pois bem, em minha visão nada além de um computador com acesso a internet e muita, mas muita dedicação e persistência. Foi um evento incrível, com REALMENTE muita " mão na massa " e que pra mim foi bastante enriquecedor.
 
 **Lembrando**: Todas as ferramentas utilizadas no evento foram totalmente gratuitas, ou seja, você não precisa tirar um centavo do seu bolso. Tanto a hospedagem no back / front-end foram de formas grátis.
 Agradecendo também a todas as empresas que corroboraram com o projeto, seja a Heroku, Netlify, MapBox, que tem sim as limitações, mas o plano gratuito para um projeto de primeira mão é simplesmente fantástico para quem está começando.
  Espero participar de mais eventos como estes, que para mim foi mais do que o suficiente para saber que minha área é a programação e eu sou apaixonado por isto. 
  #DevSuperior #programaçãoFullStack

## Você Sabia ?
 Mesmo o evento sendo 100 % online e  gratuito, conseguimos chegar aos ***Github Trending*** ; é isso mesmo , chegamos aos 3 repositórios mais badalados do mundo. Duvidou ? Não acredita ? Acompanhe o vídeo do Professor Nélio Alves: [Clique aqui para assistir ao vídeo](https://www.youtube.com/watch?v=-hyQ2HcLL0A "Vídeo da DevSuperior no Trending"). Vamos lá, não vai levar muito tempo, são apenas 2 minutos de vídeo.   


# Autor
 _by:_ **Daniel Moura Guedes**

