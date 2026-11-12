# Spring Boot : Application PetClinic

## Features  

### 1.  Unit Test  --> Tag v1.0.0
### 2.  Integration Test  --> Tag v2.0.0
mvn clean test -Dspring.profiles.active=h2

## Integración continua del laboratorio 13

Repositorio del equipo Barzola y Huanco conectado al pipeline
`Petclinic-Barzola-Huanco` de Jenkins. Los cambios enviados a la rama `main`
activan el webhook de GitHub y ejecutan las etapas Checkout, Build, Test y Package
definidas en el archivo `Jenkinsfile`.
