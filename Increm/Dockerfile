FROM openjdk:8-jdk-alpine
VOLUME /tmp
ADD target/demo-0.0.1-SNAPSHOT.jar demo-0.0.1-SNAPSHOT.jar
EXPOSE 8086
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom.","-jar","/demo-0.0.1-SNAPSHOT.jar"]