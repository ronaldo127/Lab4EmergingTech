# Lab4EmergingTech

# Prerequisites

- This readme is assuming you were able to run Ilia's example on docker.

# Installing and running mongo

```bash
docker run -it -d --network=host mongo mongod
```
# Test mongo connection
```bash
docker run -it --network=host --rm mongo mongo
```
# Install and Run the project
```bash
docker run -it --network=host --rm -v /your/local/folder/:/app centos-microservices:1.0 /bin/bash
cd app/
npm i
npm start
```
