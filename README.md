# AWS-EKS
What is Amazon EKS?


Amazon Elastic Kubernetes Service is a fully managed service of kubernetes, you can also call it kubernetes as a service. EKS is the best place to run Kubernetes for several reasons.
1. You can choose to run your EKS clusters using AWS Fargate, which is serverless compute for containers. Fargate removes the need to provision and manage servers, lets you specify and pay for resources per application, and improves security through application isolation by design.
2. EKS is deeply integrated with services such as Amazon Auto Scaling Groups, AWS Identity and Access Management (IAM), CloudWatch, Amazon Virtual Private Cloud (VPC), etc. providing you a seamless experience to monitor, scale, and load-balance your applications.EKS gives Serverless Option (Farget), Security and built with the community.
3. EKS provides a scalable and highly-available control plane that runs across multiple availability zones to eliminate a single point of failure.


What is Docker?

Docker is a containerization tool. Using Docker we can launch the entire environment for our application server just in 1 second. Docker run in a isolation world so it is very secure to deploy our application on top of docker container.


What is Kuberntes?


Kubernetes is a management (orchestration) tool of container. Kubernetes doesn’t launch the container, it ask/contact the docker/podman/cri-o behind the scene to launch the container if requirement comes. Kubernetes is meant for only one thing to manage the container. Here in EKS in these practical we are using docker to launch our application on docker container.

What is Joomla?

Joomla is a free and open source content management system (CMS) for publishing web content, developed by Open Source Matters, Inc. It is built on a model view controller web application framework that can be used independently of the CMS. Joomla is written in PHP, uses object oriented programming techniques (since version 1.5) and software design patterns, stores data in a MYSQL, MSSQL (since version 2.5), or PostgrsSQL (since version 3.0) database.
In this practical I have used MYSQL database.

Prerequisites:

1. AWS CLI : Use to manage the aws services.
2. Kubectl: Use for communication with master cluster API server.
3. Eksctl: Use to create and manage entire kubernetes cluster on aws eks.

Steps to be followed are:

Step1 → Creating an AWS IAM role account.

Step2 → Create EKS Cluster using EKSCTL

Step4 →Create EFS Server and install amazon-efs-utils in every worker node/instance.

Step5 →Deploy Joomla


