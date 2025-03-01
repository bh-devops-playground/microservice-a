# microservice-a


docker build -t microservice-a .

docker run -p 8080:8080 microservice-a

curl http://localhost:8080



docker pull ghcr.io/bh-devops-playground/microservice-a:v1.0.0