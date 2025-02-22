# Instruction arg

FROM ubuntu:latest
RUN apt update -y
RUN apt install apache2 git -y
RUN echo "<h1> Hello World" > /var/www/html/index.html
WORKDIR /var/www/html
# COPY ./index.html /var/www/html/index.html
# ADD <URL> <DEST>
EXPOSE 80
CMD apache2ctl start
