FROM openjdk:15 
EXPOSE 8888
ADD ./target/ms.configserver-0.0.1-SNAPSHOT.jar micro-configserver.jar
ENTRYPOINT ["java","-Dspring.profiles.active=docker","-jar","/micro-configserver.jar"]
