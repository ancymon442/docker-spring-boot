# docker-spring-boot
1. Install maven and jdk 8 .
2. Clone repo from git.
3. Go to cloned repo in directory docker-spring-boot invoke:
mvn clean install
4. Run docker command to build image:
docker build -t ancymon/docker-spring-boot .
5. Run built image:
docker run -p 8080:8080 ancymon/docker-spring-boot
6. Verify that service is working:
Run
curl http://localhost:8080

or go to webbrowser and type:
http://localhost:8080

It should display in both cases:
Greetings from Ancymon

7. You can skip those steps and download prepared docker image from repository mentioned below.


Docker Hub Link: ancymon442/spring-boot/docker-spring-boot
https://cloud.docker.com/repository/registry-1.docker.io/ancymon442/spring-boot/tags

Github Link with Dockerfile: https://github.com/ancymon442/docker-spring-boot.git