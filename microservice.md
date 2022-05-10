Independently releasable service that are modeled around a [[business domain]]. One service may represent inventory, one shipping, another order management but together they constitute a complex system.

Microservices are a type of [[service oriented architecture]] that opinionated around how service boundries should be drawn.

From the outside, a single microservice is treated as a black box. You can reach a microservice via a queue or REST api or grpc protocol. Internal details are entirely hidden from the outside world.

### Key concepts
* Independent deployability (Single most important): To ensure this, you need to make sure the services are loosely coupled.
* Modeled around a business domain: Techs like [[domain driven design]] can allow you to structure your software based on real world domains.
* Owning their own state: Microservices should avoid the use of shared databases. If a microservice wants to access data of another service, it should go and ask.
* Size: Should be kept to the size at which it can be easily understood.
* Flexibility
* Alignment of Architecture and Organization: Changing from silos to functional teams.

### Enabling technology
* Log aggregation and distributed tracing: Essential for beginning a microservice journey. You can use correlation IDs. IDs that is used for related set of service calls.
* Containers and Kubernetes: For isolated execution.
* Streaming.
* Public Cloud and Serverless.