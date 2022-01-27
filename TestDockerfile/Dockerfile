# first test Dockerfile
FROM nginx:1.19.0-alpine

RUN echo "Test Run im Dockerfile"

COPY index.html /usr/share/nginx/html

EXPOSE 80

#hält Container am Laufen: hier nginx -g daemon off;
CMD ["nginx", "-g", "daemon off;"]