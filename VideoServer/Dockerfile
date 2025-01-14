FROM openjdk:8-jdk

WORKDIR /app

COPY . .

RUN ./gradlew shadowJar

CMD ["java", "-jar", "/app/build/libs/VideoServer-1.0-SNAPSHOT.jar"]
