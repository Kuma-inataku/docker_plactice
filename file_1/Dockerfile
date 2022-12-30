FROM ubuntu:latest

RUN apt-get update && apt-get install -y -q nginx

RUN echo "hello"

COPY index.html /usr/share/nginx/html/

CMD ["nginx", "-g", "daemon off;"]