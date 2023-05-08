
# Demo sobre live coding da digital innovation one - spring webflux - criando seu gerenciador de herois

## Stack utilizada

  * Java8
  * spring webflux
  * Spring data
  * dynamodb
  * junit
  * sl4j
  * reactor
  
  

### Slides de palestra: 
https://speakerdeck.com/kamilahsantos/live-coding-dio-api-de-herois-com-spring-webflux

### Palestra gravada: 
https://www.youtube.com/watch?v=1VllPZYn6RI&t=3257s

### Executar dynamo: 

 Na pasta em que o jar está baixado:
 ```
 java -Djava.library.path=./DynamoDBLocal_lib -jar DynamoDBLocal.jar -sharedDb
 ```
Para listar as tabelas criadas:
```
aws dynamodb list-tables --endpoint-url http://localhost:8000
```
Documentação gerada pela aplicação:

swagger: http://localhost:8080/swagger-ui-heroes-reactive-api.html
