FROM openjdk:11.0.3-jre-slim-stretch
LABEL Pablo González
ADD UserEventsAPI-0.0.1-SNAPSHOT.jar app.jar
EXPOSE 8080
ENTRYPOINT ["java","-jar","app.jar"]