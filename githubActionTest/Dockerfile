#FROM openjdk:11
#ARG JAR_FILE=build/libs/*.jar
#COPY ${JAR_FILE} app.jar
#ENTRYPOINT ["java","-jar","/app.jar"]


FROM openjdk:11
COPY ${build/libs/*.jar} app.jar
ENTRYPOINT ["java","-jar","/app.jar"]