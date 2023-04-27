# searxng
Searxng for yt



1. sudo apt update && sudo apt upgrade
2. sudo apt install docker-compose
3. cd /usr/local
4. git clone https://github.com/searxng/searxng-docker.git
5. cd searxng-docker
6. sudo sed -i "s|ultrasecretkey|$(openssl rand -hex 32)|g" searxng/settings.yml
7. sudo docker-compose up
8. sudo docker-compose up -d
9. Goto http://localhost:8080 or http://localhost/
