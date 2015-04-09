# Install-DockerUI-For-Docker-Management
도커 관리용 ui 설치

    docker run -d -p 9000:9000 --privileged -v /var/run/docker.sock:/var/run/docker.sock dockerui/dockerui

일단 위처럼 실행하면 <IP_address>:9000 으로 접속 가능
