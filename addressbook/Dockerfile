FROM openjdk:17-jdk-alpine
WORKDIR /app
COPY target/addressbook-0.0.1-SNAPSHOT.jar addressbook.jar
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "addressbook.jar"]
