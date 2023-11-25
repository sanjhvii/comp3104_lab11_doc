
# Run following command on terminal

docker build --tag=101370217_hello_docker .

docker build -t 101370217_hello_docker .

docker image ls

docker run -p 4000:80 101370217_hello_docker

docker run -d --name=lab11Devops -p 4000:80 101370217_hello_docker

docker container stop CONTAINER_ID

docker container ls