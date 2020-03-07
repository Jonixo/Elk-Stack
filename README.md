# Elk-Stack

A simple Elk-Stack with some additions, mainly to use in my future projects.

## Getting Started

This docker-compose file isn't meant to be run in this shape. I created this so I can 
just copy the services I need to a new file or delete the services I don't need in any
project. 
But if you just want to run all of the services at once, there is nothing stopping you
all of them works together without any problem.

## Current Services 

- Elasticsearch
- Logstash
- Kibana
- Zookeeper
- Kafka
- MongoDb
- RabbitMq
- Mqtt
- Portainer


## Deployment

Just do a good old

```
docker-compose up --build 
```

and you are good to go. Images will automaticly download and containers will start.


## Configuration

To configure Kibana, ElasticSearch and Logstash you may use the .yml inside their folder.

For any other service look into their environmental variables.

##### Authors

**B. Furkan Ibili**

I'm keeping the right to add even more services to this in the future.


