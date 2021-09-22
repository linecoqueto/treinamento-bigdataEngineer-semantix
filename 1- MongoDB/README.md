# MongoDB - Básico

- Entendimento de conceitos e arquitetura NoSQL e MongoDB; 
- Instalação de cluster MongoDB através de container e Cloud; 
- Manipular coleções, documentos e índices; 
- Realizar diversas pesquisas no MongoDB com diferentes operadores; 
- Fazer uso das interfaces gráficas MongoExpress e MongoCompass; 
- Trabalhar com pipeline de agregações; 
- Entendimento de Replicação e shards; 
- Desafiar os estudantes na utilização desses novos conhecimentos com exercícios práticos.

### Carga horária 12 horas

### Badge
https://badgr.com/public/assertions/eA2DRxROQbiD_uMK49Mnlw


### Realização dos exercício no docker:

##### docker-compose.yml

```sh
version: '3.1'

services:

  mongo:
    image: mongo
    container_name: mongo
    restart: always
    ports:
      - 27017:27017
    volumes:
      - db:/data/db

  mongo-express:
    image: mongo-express
    container_name: mongo-express
    restart: always
    ports:
      - 8081:8081

volumes:
  db:
```
