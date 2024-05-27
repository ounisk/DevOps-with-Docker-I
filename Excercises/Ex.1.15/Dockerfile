#Using NGINX image from Dockerhub
FROM nginx:latest

# Copy index.html file to NGINX Html directory
COPY ./index.html /usr/share/nginx/html/index.html

# Give permission to NGINX to read file (otherwise might get 403 error)
RUN chmod 644 /usr/share/nginx/html/index.html