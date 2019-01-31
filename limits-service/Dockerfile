
FROM openjdk:8-jre-alpine
WORKDIR /tmp
COPY   target/limits-service-0.0.1-SNAPSHOT.jar limits-service.jar
EXPOSE 8080
CMD ["java", "-jar", "limits-service.jar"]

