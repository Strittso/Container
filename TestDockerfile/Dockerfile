# first test Dockerfile
FROM nginx:1.19.0-alpine

RUN echo "Test Run im Dockerfile"
RUN apk update
RUN apk add --no-cache python2 py3-pip

COPY index.html /usr/share/nginx/html

EXPOSE 2000

#hält Container am Laufen: hier nginx -g daemon off;
CMD ["nginx", "-g", "daemon off;"]
