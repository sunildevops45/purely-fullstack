FROM eclipse-temurin:21-jdk

COPY target/*.jar service-registry.jar

ENTRYPOINT ["java","-jar","/service-registry.jar"]
