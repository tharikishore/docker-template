# docker-template
Docker and Compose templates for learners of programming 
Cloned file from remote repository using: $ git pull https://github.com/tharikishore/docker-template.git
Find the status: $ git status
Start the container using docker-compose:
$ docker-compose up -d
We can see the running container:$ docker ps
CONTAINER ID        IMAGE               COMMAND               CREATED             STATUS              PORTS                                            NAMES
662ef6cb9fd4        ubuntu              "/bin/bash"           57 minutes ago      Up 57 minutes                                                        networktest
cb84a25d45e2        open-image-jdk      "tail -f README.md"   19 hours ago        Up 4 minutes        0.0.0.0:8080->8080/tcp, 0.0.0.0:7005->5005/tcp   container-jdk
Get into the container and launches a bash shell inside our container.
$ docker exec -it container-jdk /bin/bash
Execute the code using gradlew
./gradlew run
Exit from the Container.
Find the git status.

