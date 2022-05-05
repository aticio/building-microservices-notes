Independently releasable service that are modeled around a [[business domain]]. One service may represent inventory, one shipping, another order management but together they constitute a complex system.

Microservices are a type of [[service oriented architecture]] that opinionated around how service boundries should be drawn.

From the outside, a single microservice is treated as a black box. You can reach a microservice via a queue or REST api or grpc protocol. Internal details are entirely hidden from the outside world.