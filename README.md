  This repository is a workbench designed to encapsulate most of the best practices I've learned during my backend developer career. It integrates a diversity of Spring Cloud services that proove my ability to design secure and reliable microservice based architectures.
  
AuthService
- eureka-client client
- config-service client
- database users fetching

GatewayService
- eureka-client client
- config-service client
- system entrypoint
- request routing to: resource-service, database-service (NOT WORKING)
- TODO: authentication and service level authorization


DatabaseService
- eureka-service client
- config-service client
- API Controller containing
- Eureka client
- basic database interractions based on JpaRepository like CRUD operations or filtered querying
- loose coupling between controller, service and repository layers
- TODO: api authorization, unit testing, integration testing
- TODO: gateway routed requests

EurekaService
- service discovery

ConfigService
- eureka-service client

ResourceService
- eureka-client client
- config-service client

Database - MySQL
- running on Docker container
