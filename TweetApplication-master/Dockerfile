FROM openjdk:8
EXPOSE 8090
ADD target/tweet-app-springboot-docker.jar tweet-app-springboot-docker.jar
ENTRYPOINT ["java","-jar","tweet-app-springboot-docker.jar"]