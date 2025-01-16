FROM openjdk:17
EXPOSE 9090
ADD target/docker-url-shortener.jar.jar docker-url-shortener.jar
ENTRYPOINT ["java", "-jar", "/docker-url-shortener.jar"]
