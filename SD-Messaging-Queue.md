## Messaging Queue
Messaging Queues are widely use in asynchronous systems.
Message processing in an asynchronous fashion allows the client to relieve itself from waiting for a task to complete and, hence, can do other jobs during that time. 
It also allows a server to process it's jobs in the order it wants to.

Messaging Queues provide useful features such as persistence, routing and task management.

A system having a message queue can move to higher level requirements while abstracting implementation details of message delivery and event handling to the messaging queue.

The 'queue' is just a name for this data structure. In practice, it could be storing messages using any policy. Some examples of message queues are Kafka and RabbitMQ. They are widely used for various purposes such as command query request segregation (CQRS) and event sourcing
