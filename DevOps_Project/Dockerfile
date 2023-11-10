FROM alpine:3.14
RUN apk --no-cache add openjdk11
RUN apk --no-cache add curl
RUN curl -u admin:admin -o DevOps_Project-2.1.jar "http://172.17.0.1:8081/repository/maven-releases/tn/esprit/DevOps_Project/2.1/DevOps_Project-2.1.jar" -L
ENTRYPOINT ["java","-jar","DevOps_Project-2.1.jar"]

