FROM adoptopenjdk/openjdk17:alpine

WORKDIR /app

COPY target/eureka-server.jar /app/eureka-server.jar

EXPOSE 8761

CMD ["java", "-jar", "eureka-server-1.0.0.jar"]