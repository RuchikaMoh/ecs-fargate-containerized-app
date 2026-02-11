
# Containerized Web Application on AWS ECS (Fargate)

## Overview
This project demonstrates deploying a Dockerized web application on AWS ECS using Fargate.
It covers containerization, ECS task definitions, VPC networking, security groups, and
monitoring using AWS CloudWatch.

## Architecture
- Dockerized Flask application
- Amazon ECR for container image storage
- AWS ECS with Fargate launch type
- Public subnet with security group rules
- CloudWatch Logs for monitoring

## Tech Stack
- Docker
- AWS ECS (Fargate)
- Amazon ECR
- VPC, Security Groups
- CloudWatch Logs
- Python (Flask)

## Deployment Steps
1. Build Docker image locally
2. Push image to Amazon ECR
3. Create ECS task definition using Fargate
4. Configure networking and security groups
5. Deploy ECS service and verify public access

## Troubleshooting
- Resolved container startup failures due to incorrect port mapping
- Fixed security group inbound rules to allow application traffic
- Verified application logs using CloudWatch log streams

## Screenshots
![ECS Service](screenshots/ecs-service.png)
![CloudWatch Logs](screenshots/cloudwatch-logs.png)
![Application Running](screenshots/app-running.png)
