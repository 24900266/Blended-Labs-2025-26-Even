# Lab 6 – Scale and Load Balance Your Architecture

## Title
Scale and Load Balance Your Architecture
# Author : Preetha K 
# Reg no : 212224100044
# Date   : 18.03.2026


## Objective

The objective of this lab is to understand how to design a scalable and highly available architecture on AWS using Auto Scaling and Elastic Load Balancing. This experiment focuses on distributing incoming traffic across multiple EC2 instances, automatically scaling resources based on demand, and validating fault tolerance.

---

## Prerequisites

* Basic knowledge of Amazon EC2 and VPC
* Completion of previous labs (IAM, EC2, EBS, Database Server)
* AWS Academy Lab access
* Stable internet connection

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Elastic Load Balancer (ELB / ALB)
* Auto Scaling Groups (ASG)
* Amazon CloudWatch

---

## Tasks Performed

### Task 1: Review Existing Architecture

Students review the existing EC2-based application architecture created in previous experiments.

### Task 2: Create a Launch Template

Students create a launch template that defines the EC2 instance configuration including AMI, instance type, security group, and user data.

### Task 3: Create an Auto Scaling Group

Students create an Auto Scaling Group using the launch template and configure minimum, maximum, and desired instance capacity.

### Task 4: Configure an Application Load Balancer

Students create an Application Load Balancer and configure target groups for routing traffic to EC2 instances.

### Task 5: Register Auto Scaling Group with Load Balancer

Students attach the Auto Scaling Group to the target group of the load balancer.

### Task 6: Configure Scaling Policies

Students configure scaling policies based on CPU utilization using Amazon CloudWatch alarms.

### Task 7: Test Load Balancing and Scaling

Students test the setup by generating traffic and observing automatic scaling and load distribution.

---

## Workflow (To be filled by Student)

1.Launch multiple servers.

2.Deploy the application on each server.

3.Create a load balancer.

4.Add servers to the load balancer.

5.Configure auto-scaling.

6.Test load distribution.

## Output Screenshots 

<img width="1824" height="764" alt="image" src="https://github.com/user-attachments/assets/00c103d9-a9aa-4d0f-b24b-773022ffd8db" />

<img width="1845" height="763" alt="image" src="https://github.com/user-attachments/assets/df6e2a6f-bc39-40fb-aa38-4f1bbb1f7e46" />

<img width="1258" height="537" alt="image" src="https://github.com/user-attachments/assets/62c82b38-3a1c-44e3-b599-c8e4db2952ec" />

<img width="1260" height="544" alt="image" src="https://github.com/user-attachments/assets/4f84d8bc-8118-4096-a6be-def5e181783e" />

<img width="1249" height="526" alt="image" src="https://github.com/user-attachments/assets/a899fd09-8ee0-411c-8d30-a4abe833de14" />

<img width="1256" height="523" alt="image" src="https://github.com/user-attachments/assets/6d4a4122-8828-470f-825d-de2a91b3f257" />

<img width="1187" height="484" alt="image" src="https://github.com/user-attachments/assets/bcc192be-0130-4734-a3d0-2448ad129748" />

<img width="1246" height="533" alt="image" src="https://github.com/user-attachments/assets/623bbc6a-c4d6-4c72-82d5-ee9dee10b941" />

## Result

This experiment demonstrated how to build a scalable and fault-tolerant cloud architecture using Auto Scaling Groups and Elastic Load Balancing. The system automatically adjusted resources based on workload and ensured continuous service availability by distributing traffic across multiple instances.
