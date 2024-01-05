FROM eclipse-temurin:17-jdk-alpine

LABEL authors="prashant"

ARG artifact=target/cicd-0.0.1-SNAPSHOT.jar

WORKDIR /opt/app

COPY ${artifact} app.jar

EXPOSE 8010

ENTRYPOINT ["java", "-jar", "app.jar"]


