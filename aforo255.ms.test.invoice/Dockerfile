FROM openjdk:11
EXPOSE 2002
##EXPOSE 80
ADD ./target/aforo255.ms.invoice-0.0.1-SNAPSHOT.jar ms-invoice.jar
ENTRYPOINT ["java","-jar","/ms-invoice.jar"]
##ENTRYPOINT ["java","-Dspring.profiles.active=docker","-jar","/ms-historical.jar"]
