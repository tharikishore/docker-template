# docker-template

  Docker and Compose templates for learners of programming 

* Clone file from remote repository using: $ git pull https://github.com/tharikishore/docker-template.git
* Find the status: $ git status
* Start the container using docker-compose: `docker-compose up -d`

>We can see the running container:$ docker ps
>CONTAINER ID        IMAGE               COMMAND               CREATED             STATUS              PORTS                                            NAMES
cb84a25d45e2        open-image-jdk      "tail -f README.md"   19 hours ago        Up 4 minutes        0.0.0.0:8080->8080/tcp, 0.0.0.0:7005->5005/tcp   container-jdk

* To interact with the container: `docker exec -it container-jdk /bin/bash`
* Launch the application: `./gradlew run`


