FROM openjdk:11-stretch
WORKDIR /
ADD SpringJettyEx-1.0-SNAPSHOT-jar-with-dependencies.jar hello-jetty.jar
EXPOSE 9290
CMD ["java", "-jar", "hello-jetty.jar"]