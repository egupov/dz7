FROM alpine:latest
WORKDIR /usr/local/tomcat
RUN apk --no-cache --update add git maven
RUN git clone https://github.com/boxfuse/boxfuse-sample-java-war-hello.git && \
    cp /usr/local/tomcat/boxfuse-sample-java-war-hello/target/classes/hello-1.0.war /usr/local/tomcat/webapps