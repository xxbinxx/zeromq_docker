# Microservice Architecture in Python with ZeroMQ & Docker

## Sample Microservice With Docker And Python

#### 1. Build the publisher first

`sudo docker build -t zmq-docker-pub .`

`docker run --name docker-pub-server -p 9000:9000 -p 8888:8888 -t zmq-docker-pub`

#### 2. Run the Client
`python zmqclient.py`
