## **Online Store application**
This is the main repository of the Online Store application.

The application consists of 10 microservices:

3 microservices are needed to ensure the operation of the system:
1. [Spring Cloud Config Server](https://github.com/turaevdv/OnlineStoreMicroserviceCloudConfig)
2. [Spring Cloud Eureka Server](https://github.com/turaevdv/OnlineStoreMicroserviceEurekaServer)
3. [Spring Cloud Gateway](https://github.com/turaevdv/OnlineStoreMicroservicesGatewayServer)

In addition, since the application uses a remote configuration, there is [a git repository that stores the configuration](https://github.com/turaevdv/OnlineStoreMicroserviceConfigRepository)

7 microservices directly execute business logic:
1. [Address microservice](https://github.com/turaevdv/OnlineStoreMicroserviceAddress)
2. [Storehouse microservice](https://github.com/turaevdv/OnlineStoreMicroserviceStorehouse)
3. [Pickup point microservice](https://github.com/turaevdv/OnlineStoreMicroservicePickupPoint)
4. [Goods microservice](https://github.com/turaevdv/OnlineStoreMicroserviceGoods)
5. [User microservice](https://github.com/turaevdv/OnlineStoreMicroserviceUser)
6. [Order microservice](https://github.com/turaevdv/OnlineStoreMicroservicesOrder)
7. [Report microservice](https://github.com/turaevdv/OnlineStoreMicroserviceReport)

The application, on the one hand, allows its owner to do business, on the other hand, provides an opportunity for customers to order products and cancel orders.
You can read more about the role of each microservice in the file README.md microservice repository.