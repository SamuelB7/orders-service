# orders-service

Responsible for order creation, lifecycle state, seller order groups, order history, and order events.

NestJS boilerplate with `@nestjs/microservices` and Kafka. This phase does not implement business rules for this service yet.

## Project Origin

This microservice is part of the [ecommerce-eda](https://github.com/SamuelB7/ecommerce-eda) event-driven marketplace platform.

## Endpoints

- `GET /health`
- `POST /events/demo`

## Demo Topic

- `orders.demo.event.v1`
