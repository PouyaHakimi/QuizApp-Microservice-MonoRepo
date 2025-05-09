FROM openjdk:21-jdk
WORKDIR /quiz-app
ADD target/quiz-Service.jar quiz-service.jar
ENTRYPOINT ["java", "-jar", "quiz-service.jar"]
