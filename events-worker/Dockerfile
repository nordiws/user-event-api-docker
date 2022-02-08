FROM openjdk:11-ea-11-slim
LABEL Pablo González
COPY EventsWorker-0.0.1-SNAPSHOT.jar app.jar
EXPOSE 8090
ENTRYPOINT ["java","-jar","app.jar"]