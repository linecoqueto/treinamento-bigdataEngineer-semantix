# Redis - Básico

- Entendimento de conceitos e arquitetura NoSQL e Redis; 
- Instalação de cluster Redis através de container;
- Manipulação de diversos tipos de estrutura de dados com Redis-CLI;
- Implementar paradigma de mensagens Pub/Sub;
- Configurações básicas de persistência de dados;
- Desafiar os estudantes na utilização desses novos conhecimentos com exercícios práticos.

### Carga horária 12 horas

### Badge

https://badgr.com/public/assertions/eiFNNEynRVCiMa_YeDD-Jg


### Realização dos exercício no docker:

##### docker-compose.yml

```sh
version: '3.1'

services:

  redis:
    container_name: redis
    image: redis
    ports:
      - 6379:6379
    volumes:
      - data:/data
    entrypoint: redis-server --appendonly yes
    restart: always      

volumes:
  data:
```
