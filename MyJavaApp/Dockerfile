FROM openjdk:17-jdk-slim
WORKDIR /app
COPY /src/master/java/com/example/App.java .
RUN javac App.java
CMD ["java", "App"]
