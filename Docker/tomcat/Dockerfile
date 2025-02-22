FROM ubuntu:latest
RUN apt update -y
RUN apt install openjdk-11-y
ADD https://dlcdn.apache.org/tomcat/tomcat-9/v9.0.98/bin/apache-tomcat-9.0.98.tar.gz /opt
WORKDIR /opt
RUN tar -xzf apache-tomcat-9.0.98.tar.gz 
WORKDIR /opt/apache-tomcat-9.0.98/
COPY student.war webapps/student.war
EXPOSE 8080
ENTRYPOINT [ "bin/catalina.sh", "run" ]
