# Steps to start kafka
 
  1 - start zookeeper
   
    zookeeper-server-start ./config.properties
  
  2 - start kafka server
   
    kafka-server-start ./server.properties

# start rabbitmq as a docker container
 
    docker run --name rabbitmq -p 8081:15672 -p 5672:5672 rabbitmq:3-management


   
  