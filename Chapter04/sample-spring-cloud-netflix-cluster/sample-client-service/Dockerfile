FROM openjdk:10-jre-slim
COPY ./target/sample-client-service-1.0-SNAPSHOT.jar /usr/src/hola/
WORKDIR /usr/src/hola
EXPOSE 9120
CMD ["java", "-jar","-Dspring.profiles.active=orders" ,"sample-client-service-1.0-SNAPSHOT.jar"]