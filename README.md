Creating ECS Infrastructure
To build the architecture described in the solution overview, you will need the following ECS components:

ECR Repository: store versioned application container images
ECS Cluster: provides compute power to run application container instances
ECS Task Definition: specifies application container image version and environment considerations
ECS Service: specifies how task definition will be deployed onto underlying compute resources
To build this infrastructure, we will be use the AWS Cloud Development Kit (CDK). If you are new to the CDK, see Getting Started with the AWS CDK. In this post, we will be using the CDK with Python 3.7.
