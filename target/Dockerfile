FROM java:8
EXPOSE 8092
ADD target/microservices-0.0.1-SNAPSHOT.war microservices.war
ENTRYPOINT ["java","-jar","microservices.war"]