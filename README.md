# Spring-Cloud-Data-Flow-Local
Setup and run Spring Cloud Data Flow Server 2.8.1 local

# Download and install JARs

- spring-cloud-dataflow-server-2.8.1.jar: https://mvnrepository.com/artifact/org.springframework.cloud/spring-cloud-dataflow-server/2.8.1
- spring-cloud-dataflow-shell-2.8.1.jar: https://mvnrepository.com/artifact/org.springframework.cloud/spring-cloud-dataflow-shell/2.8.1
- spring-cloud-skipper-server-2.7.1.jar: https://mvnrepository.com/artifact/org.springframework.cloud/spring-cloud-skipper-server/2.7.1

wget https://repo1.maven.org/maven2/org/springframework/cloud/spring-cloud-dataflow-server/2.8.1/spring-cloud-dataflow-server-2.8.1.jar<br>
wget https://repo1.maven.org/maven2/org/springframework/cloud/spring-cloud-dataflow-shell/2.8.1/spring-cloud-dataflow-shell-2.8.1.jar<br>
wget https://repo1.maven.org/maven2/org/springframework/cloud/spring-cloud-skipper-server/2.7.1/spring-c
loud-skipper-server-2.7.1.jar<br>

Install Messaging Middleware RabbitMQ:

docker run -d --hostname rabbitmq --name rabbitmq -p 15672:15672 -p 5672:5672 rabbitmq:3.7.14-management

# Reference

- https://dataflow.spring.io/
- https://www.youtube.com/watch?v=rvAr0KYXBhk
