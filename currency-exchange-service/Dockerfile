
FROM openjdk:8-jre-alpine
WORKDIR /tmp
COPY   target/currency-exchange-service-0.0.1-SNAPSHOT.jar currency-exchange-service.jar
EXPOSE 8000
CMD ["java", "-jar", "currency-exchange-service.jar"]

