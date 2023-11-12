FROM openjdk:21-ea-1-oracle
VOLUME /tmp
COPY target/*.jar app.jar
ENTRYPOINT ["java" ,"-jar" ,"app.jar"]