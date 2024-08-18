
FROM openjdk11:alpine-jre-slim


ARG JAR_FILE=target/spring-boot-web.jar

WORKDIR /opt/app

COPY ${JAR_FILE} app.jar


ENTRYPOINT ["java","-jar","app.jar"]
