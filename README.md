# Challenge of FullCycle Docker course 
## First step
> Clone the project with the command ahead

 ```git clone https://github.com/vitoremerique/full-cycle-docker-challenge.git```

## Go Docker [Challenge](go_challenge/)
_The challenge was print "Full cycle Rocks!!"_

To acess the image in docker hub click [Here](https://hub.docker.com/repository/docker/vitoremerique/go/general)

To run and test the container you just need run on terminal tow commands:
>```docker build -t [nameImage] . ```

>```docker run -d [nameImage] ```

The command will work if you have **docker** installed in your computer.

## Node + Mysql + Nginx [Challenge](node-nginx//)
_The challenge here is acess ```localhost:8080``` on navigator and show again "Full cycle Rocks!!" but complete with a list of names shohwing together, that need be inserted in a table of database Mysql._

> Before run the container inside the [folder](node-nginx//) create another folder called "mysql"

To run and test the container you jst need run on terminal one command:
> ```docker compose up --build -d```
