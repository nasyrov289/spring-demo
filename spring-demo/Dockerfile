FROM java:8
FROM maven:alpine

WORKDIR /app

COPY . /app

RUN mvn -v
RUN mvn clean install -DskipTests
EXPOSE 8080
LABEL maintainer='nasyrov289@gmail.com'
ADD ./target/spring-demo-0.0.1-SNAPSHOT.jar spring-demo-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java", "-jar", "spring-demo-0.0.1-SNAPSHOT.jar"]
