FROM openjdk:8-jdk-alpine
VOLUME /tmp
ADD litemall-all-0.1.0-exec.jar app.jar
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]
