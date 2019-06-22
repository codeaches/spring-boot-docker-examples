FROM codeaches/openjdk:12-jdk
ADD target/hello-world-ws-0.0.1-SNAPSHOT.jar hello-world-ws.jar
EXPOSE 80
ENTRYPOINT ["java", "-jar", "hello-world-ws.jar"]
