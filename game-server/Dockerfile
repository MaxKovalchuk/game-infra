FROM openjdk:17

WORKDIR /app

COPY game-server-0.0.1-SNAPSHOT.jar .

ENTRYPOINT ["java", "-jar", "-Dspring.profiles.active=dev", "game-server-0.0.1-SNAPSHOT.jar"]