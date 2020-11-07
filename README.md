# -spring-microservices-config-repository
## Business Services
Creating microservice using dependences: lambok,jpa,show SGBD, jpaRepository,Client Config,Eureka actuator
Save a few elements in the database for do a test

## Create Config Service
Creating config Service using ConfigServer dependence 
    -Attivate ConfigService in the App using @EnableConfigServer annotation
    -Configure Config Service in his configuration file bootstrap.properties by defining(server.port, path git repository)
## Renomer les fichier de configuration 
    -chaque fichier de configuration des microservices au niveau du projet est 
    - est nommer bootstrap.properties au lier de application.properties et on defini son nom et chemin du microservice de configuration comme suit:
        -- Spring.Application.name et Spring.cloud.config.uri
##In the repository Git
Declaration of all parameters common to microservices in application.properties file
Declaration of   parameters specific linked to each service int its file serviceName.properties 


