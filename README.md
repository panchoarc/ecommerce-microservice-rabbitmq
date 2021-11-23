### Services:
  1. Auth Service
  2. Product Service
  3. Order Service

# APPLICATION DIAGRAMS

## Service Jobs
  
![Service jobs](https://ik.imagekit.io/09vbfltqtgx/COM_MICRO-Page-2_qT8AiOXYJ.png)




## FLOW Chart

![Flow Chart](https://ik.imagekit.io/09vbfltqtgx/COM_MICRO-Page-1_zQq3E_sKrD.png)





# DOCKER

If you don't want to install rabbitMQ and mongoDB, use docker instead to create a container with the following syntax in terminal CLI.

## MONGODB container

```docker
docker run -dp <externalMONGODBPORT>:<containerMONGODBPORT> --name <ContainerName> mongo:5
```

## RabbitMQ container

```docker
docker run -dp <EXTERNALrabbitMQPORT>:<CONTAINERrabbitMQPORT> --name <ContainerName> rabbitmq
```