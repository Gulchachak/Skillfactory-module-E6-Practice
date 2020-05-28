# flask_in_docker (Fibonacci)

sudo git clone git@github.com:tomasmor42/flask_in_docker.git

cd flask_in_docker

sudo docker build -t flask_in_docker:v0.1 .
sudo docker images
sudo docker run flask_in_docker:v0.1
sudo docker run  -p 8081:8081 flask_in_docker:v0.1
sudo docker-compose build
sudo docker-compose up
