# Main Commands

### docker
 - list containers running ```docker ps```
 - to connect one container ```docker exec -it ${CONTAINER_ID} mysql -uquarkus -pquarkus quarkus```
 - To run a database by docker-composer ```docker compose up -d database```

### Maven
 
- executing integrations Test with Maven ``` ./mvnw verify -DskipITs=false -Dquarkus.log.handler.gelf.enabled=false -Dquarkus.openlemetry.enable=false -Dquarkus.datasource.jdbc.driver=org.mariadb.jdbc.Driver```