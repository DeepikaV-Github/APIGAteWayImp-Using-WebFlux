FROM eclipse-temurin:24-jre
WORKDIR /app
COPY build/libs/APIGateway-0.0.1-SNAPSHOT.jar app.jar
EXPOSE 8900
ENTRYPOINT ["java","-jar","app.jar"]
