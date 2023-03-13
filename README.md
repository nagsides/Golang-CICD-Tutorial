# Golang-CICD-Tutorial
A simple Golang CI/CD Tutorial

Building and pushing to docker hub
sudo docker buildx build --platform=linux/amd64 -t docker.io/nagsides/golang-cicd:1.0 --push -f ./Dockerfile .

Running docker locally
sudo docker run -it --rm -p 8080:8080 --name mygolang nagsides/golang-cicd:1.0 

Then, localhost/8080, to display Hello World
