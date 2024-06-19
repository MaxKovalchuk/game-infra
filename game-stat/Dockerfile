FROM openjdk:17

WORKDIR /app

COPY game-stat-0.0.1-SNAPSHOT.jar .

ENTRYPOINT ["java", "-jar", "-Dspring.profiles.active=dev", "game-stat-0.0.1-SNAPSHOT.jar"]