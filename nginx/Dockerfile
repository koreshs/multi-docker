FROM nginx
COPY ./default.conf /etc/nginx/conf.d/default.conf
RUN apt-get update && apt-get install -y iputils-ping telnet
