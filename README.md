This repo contains all codes for the ECommerce freelance marketplace application.

> ## Jobber Client
* The `jobber-client` folder contains the frontend code.
* The frontend application is built using `React`, `Typescript` and `Tailwindcss`.
* The mobile application is built using `React Native`, `Typescript` and `NativeBase`.
<br /><br/>

> ## Kubernetes
* The `jobber-k8s` folder contains the objects code needed to deploy the microservices to kubernetes.
* The microservices are deployed to both `Minikube` and `AWS EKS Cluster`.
<br /><br/>

> ## Microservices
* The `microservices` folder contains all the backend code for the application's services.
* The services can be started either individually from the terminal or via docker compose.
* [Microservices README file](https://github.com/vynnydev/jobberapp-microservices/blob/main/microservices/README.md)
<br /><br/>

> ## Microservices Architecture:
![alt text](./infraestructure/images/project-architecture.png "Microservices on AWS")
<br />

> ## Messaging Broker Architecture:
![alt text](./infraestructure/images/messaging-architecture.png "Messaging Broker Architecture")
<br /><br />

> ## Infraestructure
* The `volumes` folder contains files that are used to run services for local development.
* [Volumes README file](https://github.com/vynnydev/jobberapp-microservices/blob/main/infraestructure/volumes/README.md)
* The `terraform` folder contains files that are used to build infraestructure in AWS cloud to run services
<br /><br/>


> ## Microservices on AWS:
![alt text](./infraestructure/images/aws-infra.png "Microservices on AWS")
