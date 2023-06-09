# Hugo App for FortiDevSec/FortiDAST Demo

### To run the Dockerized Hugo 

Prequisite: Docker 

To build and run via docker locally:
```sh
docker build -t devsec-dast-demo .
docker run -p 1313:1313 devsec-dast-demo:latest
```
In a browser, navigate to: http://localhost:1313/DevSecDASTDemo/

### GitHub Actions Runner

To spin up a GitHub Actions runner on an EC2 instance (you will need an AWS account and an existing VPC), you may clone the repo and follow the instructions found [here](https://github.com/rob-40net-test/cft-utility-templates/tree/main/GHA).

### ECS App

To create an ECS cluster to host the containerized app, see [here](https://github.com/rob-40net-test/cft-utility-templates/tree/main/ecs-stack).

