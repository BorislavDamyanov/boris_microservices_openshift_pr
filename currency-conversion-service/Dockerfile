FROM openjdk:8-jre-alpine
WORKDIR /tmp
COPY   target/currency-conversion-service:0.0.1-SNAPSHOT.jar currency-conversion-service.jar
EXPOSE 8000
CMD ["java", "-jar", "currency-conversion-service.jar"]