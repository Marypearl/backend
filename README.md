# Getting Started with the Server side of the Node Docker todo app

## Prerequisites
Ensure that you have Docker installed 
visit docker official documentation to install

- check t


edit the connection string to match the credentials on the `mongo-db.sh` file

- build image using the Dockerfile
```sh
docker build -t backend-node .
```

- rum the built image using CLI
```sh
docker run --name backend-node -d -p 5000:5000 backend-node
```
