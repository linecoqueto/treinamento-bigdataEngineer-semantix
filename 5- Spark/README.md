# Spark - Big Data Processing

- Uso do Jupyter Notebooks para a criação de projetos em Spark com Python; 
- Operações com RDD, Dataframe e Dataset em Spark para processamento de dados em batch; 
- Uso de Partições; 
- Comandos avançados com Dataframe e Dataset; 
- Uso do IntelliJ IDEA para a criação de projetos em Spark com Scala;
- Struct Streaming e Spark Streaming para leitura de dados do Kafka;
- Otimizações com uso de Variáveis Compartilhadas;
- Criações de User defined Function;
- Configurações de Tunning para o Spark Application;
- Desafiar os estudantes na utilização desses novos conhecimentos com exercícios práticos.

### Carga horária 20 horas

### Badge

https://badgr.com/public/assertions/7uqpcq9wRoWVPj-h92N2pA

### Realização dos exercício no docker:

```
---> baixar as imagens do Cluster de Big Data:
git clone https://github.com/rodrigo-reboucas/docker-bigdata.git spark
cd spark
docker-compose –f docker-compose-parcial.yml pull

---> Iniciar o cluster Hadoop através do docker-compose
docker-compose –f docker-compose-parcial.yml up -d

---> Acessar o Jupyter, através do link: http://localhost:8889
```
