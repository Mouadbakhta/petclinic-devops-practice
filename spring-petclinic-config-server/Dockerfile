FROM eclipse-temurin:21-jre


WORKDIR spring-petclinic-config-server
WORKDIR .

COPY target/spring-petclinic-config-server-4.0.1.jar app.jar



ENTRYPOINT ["java","-jar" ,"app.jar"]
