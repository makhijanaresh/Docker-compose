FROM openjdk:17-alpine
LABEL maintainer="test_user@gmail.com"
EXPOSE 8080
COPY target/demo-0.0.4-SNAPSHOT.jar demo-0.0.4-SNAPSHOT.jar
ENTRYPOINT ["java","-jar","/demo-0.0.4-SNAPSHOT.jar"]