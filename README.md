#Software Dependency
- pika for rabbitMQ

# RabitMQ setup
Referene link: https://www.architect.io/blog/2021-01-19/rabbitmq-docker-tutorial

Rerfer to docker-compose.yml as setting up
docker pull rabbitmq:3-management
docker run --rm -it -p 15672:15672 -p 5672:5672 rabbitmq:3-management
Raibbit MQ admin console: http://localhost:15672 
