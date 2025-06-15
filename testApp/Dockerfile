FROM openjdk:17-jdk-alpine

# create a work dir.
WORKDIR /app

# copy a jvm app.
COPY target/myproject-0.0.1-SNAPSHOT.jar app.jar

# open port 8080 for a jvm app.
EXPOSE 8080

# startup a jvm app.
ENTRYPOINT ["java","-jar","app.jar"]

