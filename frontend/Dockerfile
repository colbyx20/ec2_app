FROM nginx:latest

RUN apt update
RUN apt install -y
RUN apt install nano -y

COPY ./ssl /etc/nginx/ssl
COPY default.conf /etc/nginx/conf.d/default.conf
