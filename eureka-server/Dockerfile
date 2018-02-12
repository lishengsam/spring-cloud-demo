FROM java:8

ADD target/eureka-server.jar app.jar

EXPOSE 8761

ENTRYPOINT [ "java", "-jar", "app.jar" ]