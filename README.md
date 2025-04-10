https://start.spring.io/
sudo docker container run --rm -it -v /hellocd:/app -p 8080:8080 maven:3.9.8-eclipse-temurin-21-alpine mvn spring-boot:run -f /app/pom.xml
