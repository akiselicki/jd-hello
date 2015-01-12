FROM ubuntu:latest

RUN apt-get -qq update
RUN apt-get -y install openjdk-7-jdk

ADD jdhello-0.0.1-SNAPSHOT.jar /
ADD infinity.sh /

CMD java -jar jdhello-0.0.1-SNAPSHOT.jar && bash ./infinity.sh
#CMD java -cp jdhello-0.0.1-SNAPSHOT.jar com.levi9.test.jdhello.App && bash ./infinity.sh