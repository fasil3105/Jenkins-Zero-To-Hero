# You can change this base image to anything else
# But make sure to use the correct version of Java
FROM maven:3.9.9-eclipse-temurin-17

RUN apt-get update && \
    apt-get install -y docker.io git && \
    apt-get clean

WORKDIR /app

RUN java -version && mvn -v && docker -v && git --version

