# MEET APP - Eventos para Dev's

### Antes de mais nada, tenha instalado em sua máquina:

  - [Node](https://nodejs.org/en/download/);
  - [Yarn](https://yarnpkg.com/en/lang/pt-br/docs/install/) - *Opcional*;
  - [Docker CE](https://docs.docker.com/get-started/);

### Configurações:

**DOCKER**: `Antes de rodar a aplicação é necessário ter as seguitnes imagens em sua máquina:`
  - Postgres;
  - Mongo DB;
  - Redis ( Versão Alpine recomendada );

Para facilitar, execute o comando abaixo dentro da pasta do projeto para subir automáticamente as imagens necessárias;

```bash
  docker-compose up -d
```

**ATENÇÃO**
As seguintes portas utilizadas no ambiente devem estar liberadas:
 - Postgres: `5432`;
 - MongoDB: `27017`;

#### Ferramentas recomendadas para uso durante a aplicação:

*** Postgres ***: Para visualizar os dados cadastrados no Postgres, utilize a interface: [PostBird](https://electronjs.org/apps/postbird);
*** MongoDB ***:  Para visualizar os dados cadastrados no Postgres, utilize a interface: [Mongo Compass](https://www.mongodb.com/products/compass);
