docker-rabbitmq
===============

Builds a docker image for RabbitMQ.

```docker build -t <user>/rabbitmq```

Run the container:

```docker run -d -h localhost -p 5672:5672 -p 15672:15672 jplock/rabbitmq```
