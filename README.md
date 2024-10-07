This repository is a workbench designed to encapsulate most of the best practices I've learned during my backend developer career. It integrates a diversity of Spring Cloud services that proove my ability to design secure and reliable microservice based architectures.

DatabaseService
- API Controller containing
- Eureka client
- basic database interractions based on JpaRepository like CRUD operations or filtered querying
- loose coupling between controller, service and repository layers
- TODO: api authorization, unit testing, integration testing

EurekaService
- service discovery

GatewayService
- TODO: authentication and service level authorization

ResourceService
