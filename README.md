# SPASIBO DENIZA
![Alt text](https://github.com/nasyrov289/spring-demo/blob/master/whale.png)
# WEEK 5 TASK
## About Task
The Week 5 Task was:
```
Download some sample Java web service.
Follow tutorials on Docker in order to containerize the service and run it using a simple Tomcat Server.

What to submit:
Submit a link to your repository where you must have the following:
1. Dockerfile
2. Docker-compose
3. Instructions on which commands to use to run your service in a container (i.e. compile, build image, run container)
4. A simple .txt file describing your methodology and how you tested that your service API still works in the container.

Note: if you don't use Docker-compose, but your solution works, then that is ok. Just document what commands the user must run.
```
## HOW TO USE IT
1. Clone my repository from my Week 4 Task project, import project by using IntelliJ Idea
2. Open directory in terminal
3. Input next commands:
```
mvn clean install -DskipTests

sudo docker build -f Dockerfile -t spring-demo .

sudo docker-compose up
```
4. Launch browser and enter http://localhost:8080/admin
5. Launch POSTMAN and use CRUD methods to test API
## :3
## Author
```
Nasyrov Alymzhan, Java/Kotlin Backend Engineer/
email: nasyrov289@gmail.com
```
## Created 
```
Monday, 15 July, 2019, 16:06
```
