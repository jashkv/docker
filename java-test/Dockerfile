FROM ubuntu:latest
RUN apt-get update && apt-get install -y openjdk-11-jdk
WORKDIR /app
COPY HelloWorld.java /app
RUN javac HelloWorld.java
ENV NAME hello-world
CMD ["java", "HelloWorld"]

