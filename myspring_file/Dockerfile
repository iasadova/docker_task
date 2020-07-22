
FROM openjdk:8-jdk-alpine
ADD app/ /spring-petclinic/
WORKDIR /spring-petclinic
RUN ./mvnw package && mv target/*jar app.jar
EXPOSE 8080
CMD ["java","-jar","app.jar"]
