This is a small homework project (exercise 1.15).

After cloning the Ex.1.15 folder, you can run the application by
1. building the image by
```
docker build -t webserver .
```
2. running it with 
```
docker run -it -d -p 8080:80 --name web webserver
```
3. Navigating to localhost:8080 on your browser will show you the webpage.

The link to the image on Dockerhub is:
https://hub.docker.com/repository/docker/ounisk/website_container/general