FROM openjdk:17-jdk-slim

WORKDIR /app

# JAR 파일은 volume으로 마운트되므로 복사 생략
EXPOSE 8080

ENTRYPOINT ["java", "-jar", "/app/app.jar"]