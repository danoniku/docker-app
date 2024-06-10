

In this project, I developed a JavaScript application in my local development environment that interacts with a MongoDB database. To maintain consistency, Docker was used to encapsulate and run MongoDB as a container alongside the application. To manage version control effectively, I initiated Git to commit application's code to a Git repository.

After thoroughly developing and testing the application locally, I created a Docker image encompassing the application code, its dependencies, and the MongoDB container.
For secure storage and access control of my Docker images, I stored them in a private Docker repository, specifically the AWS Elastic Container Registry (ECR). 
My Docker images were kept in a personal Docker repository, specifically the AWS Elastic Container Registry (ECR), for safekeeping and access control.
Last but not least, I successfully used Docker Compose to deploy everything to a development server. 
