FROM openjdk:21-jdk
WORKDIR /quiz-app
ADD target/quizService-jar.jar quizservice.jar
ENTRYPOINT ["java", "-jar", "quizservice.jar"]
