# Scalable Web Application on AWS

This project demonstrates how to build a highly available and scalable web application using Amazon Web Services (AWS).

## Project Overview
The application automatically scales based on traffic demand and remains available across multiple Availability Zones.

## AWS Services Used
- Amazon EC2
- Auto Scaling Group
- Launch Template
- Application Load Balancer (ALB)
- Target Group
- VPC
- Security Groups
- CloudWatch

## Architecture
- EC2 instances deployed across multiple Availability Zones
- ALB distributes traffic
- Auto Scaling adjusts instance count automatically
- CloudWatch monitors performance

## Implementation Steps
1. Created Launch Template with Apache installed using user data
2. Configured Auto Scaling Group with min, max, and desired capacity
3. Integrated ASG with Application Load Balancer and Target Group
4. Implemented health checks for fault tolerance
5. Tested scaling by generating load
6. Verified instance replacement on failure

## Outcome
Successfully deployed a fault-tolerant and scalable web application on AWS.

## Screenshots
Screenshots are attached in the screenshots folder.
