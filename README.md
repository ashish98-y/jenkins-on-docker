# jenkins-on-docker

docker build -t jenkins-container .

 docker run -d --rm -p 9090:8080 -p 50000:50000 -v jenkins-data:/var/jenkins_home --name jenkins-container --network mynet jenkins/jenkins:latest

docker-compose up

docker exec -it --user root <CONTAINER_ID>

service docker start
better site to download docker and docker compose
https://gist.github.com/npearce/6f3c7826c7499587f00957fee62f8ee9
