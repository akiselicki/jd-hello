FROM ubuntu:latest

RUN apt-get -qq update
RUN apt-get -y install openjdk-7-jdk

ADD ${project.build.finalName}.jar /
WORKDIR /
CMD java -jar ${project.build.finalName}.jar
