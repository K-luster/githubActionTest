FROM openjdk:11
ARG JAR_FILE=githubActionTest/githubActionTest/build/libs/*.jar
COPY ${JAR_FILE} app.jar
ENTRYPOINT ["java","-jar","/app.jar"]

