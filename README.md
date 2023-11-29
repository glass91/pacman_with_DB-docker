## Pacman with mongoDB##
Run the classic Pacman game using Docker Compose. This setup includes a Node.js-based Pacman application connected to a MongoDB database.

Prerequisites
Docker: Ensure Docker and Docker Compose are installed on your machine.
Initialization Script: A mongo-init-db directory must exist in the same directory as your docker-compose-deployment-pacman-and-mongo.yaml. It should contain the init_user_db.js script for initializing the MongoDB database.
Setup Instructions
## start deployment 
1. docker compose -f docker-compose-deployment-pacman-and-mongo.yaml up -d
## stop deployment
2. docker compose -f docker-compose-deployment-pacman-and-mongo.yaml down
