FROM alpine:latest
RUN apk --update add openjdk8-jre
COPY hello-0.0.1-SNAPSHOT.jar hello.jar
CMD ["java", "-classpath","hello.jar","helloworld.hello.App"]

