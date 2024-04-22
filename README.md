# Run go

 go run main.go

# Build docker image

docker build --tag goservice .

# Run image 

docker run -it --rm -p 8082:8081 --name firstgoservice goservice

# Go port

http://localhost:8081/service1

# Docker port

http://localhost:8082/service1