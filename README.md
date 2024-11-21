# My-Docker-Ec2-setup
The main objective of this project is to set up a Docker environment using an EC2 instance and deploy web applications using containerization.
An important step in setting up this environment is the deployment of the EC2 instance.

## My Challenge
Deploying the instance, installing Docker on it, and configuring the instance **manually** was less efficient and tedious for me.

## My Solution
Since IaC is a skill that I try to constantly practice and build on, I decided to create an AWS CloudFormation template that automatically launches an EC2 instance with Docker installed, and the appropriate security group needed. All I or anyone that decides to use this method has to do is deploy the stack in CloudFormation. 
Also since this was going to be a repetitive task for me, it was best I automated it. 

# Step-by-Step Guide
If you'd like to follow a step-by-step how to set up your Docker environment using this method, here's the link to my project https://medium.com/devops-dev/containerization-with-docker-the-basics-5d159e0d665d
