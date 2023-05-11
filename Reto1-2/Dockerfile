FROM openjdk:17-alpine
WORKDIR /app
COPY ./target/Reto1-2-0.0.1-SNAPSHOT.jar  app.jar
EXPOSE 8001
ENTRYPOINT ["java","-jar","app.jar"]