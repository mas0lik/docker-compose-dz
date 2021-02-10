FROM ubuntu:20.04
RUN apt update
RUN apt-get install -y default-jdk git maven
WORKDIR /home/pkhramchenkov/
RUN git clone https://github.com/boxfuse/boxfuse-sample-java-war-hello.git
RUN mvn package -f ./home/pkhramchenkov/boxfuse-sample-java-war-hello/