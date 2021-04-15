FROM openjdk:17-jdk-alpine
EXPOSE 8080
WORKDIR /usr/src/app
COPY . .
RUN ./mvnw package
ENTRYPOINT java -jar ./target/docker-example-1.1.3.jar
