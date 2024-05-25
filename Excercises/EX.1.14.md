#### Answer:

Backend Dockerfile:
\
![image](https://github.com/ounisk/DevOps-with-Docker-I/assets/78747844/00dee36b-8954-4f09-b966-39d570dc0362)

Build  & Start Backend command: 
sudo docker build . -t hello-backend && sudo docker run -p 8080:8080 hello-backend

Frontend Dockerfile:
\
![image](https://github.com/ounisk/DevOps-with-Docker-I/assets/78747844/db7407ae-8e9b-4bdd-8a7f-89720bfec315)

Build & Start Frontend command:
sudo docker build . -t hello-frontend && sudo docker run -p 5000:5000 hello-frontend
