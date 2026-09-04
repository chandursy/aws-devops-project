

\# AWS DevOps Project



\## 🚀 Project Overview



This project demonstrates the end-to-end hosting of a static web application on AWS using EC2, Nginx, Amazon Machine Image (AMI), Launch Template, Auto Scaling Group (ASG), and Application Load Balancer (ALB).



The project focuses on deploying a static website and configuring it for scalability and high availability.



\## ☁️ AWS Services \& Technologies Used



\- Amazon EC2

\- Nginx

\- Amazon Machine Image (AMI)

\- Launch Template

\- Auto Scaling Group (ASG)

\- Application Load Balancer (ALB)

\- Target Group

\- Security Groups

\- Availability Zones

\- Git \& GitHub



\## 🛠️ Project Implementation



\### 1. EC2 Instance \& Web Application



\- Launched an Ubuntu EC2 instance using the t3.micro instance type.

\- Configured Security Group rules for HTTP (Port 80) and SSH (Port 22).

\- Connected to the EC2 instance.

\- Installed and configured Nginx.

\- Deployed the static web application to `/var/www/html`.

\- Verified the application using the EC2 public IP.



\### 2. Custom AMI



Created a custom Amazon Machine Image (AMI) from the configured EC2 instance.



\### 3. Launch Template



Created a Launch Template using the custom AMI and configured the required instance settings.



\### 4. Auto Scaling Group



Created an Auto Scaling Group using the Launch Template.



\- Desired Capacity: 1

\- Minimum Capacity: 1

\- Maximum Capacity: 5

\- Target Tracking Policy: CPU Utilization at 50%

\- Configured across multiple Availability Zones



\### 5. Application Load Balancer



Configured an internet-facing Application Load Balancer with:



\- HTTP listener on Port 80

\- Target Group

\- Health checks

\- Multiple EC2 targets



\### 6. Application Verification



Verified the complete application flow through the Load Balancer DNS endpoint and confirmed healthy targets.



\## 📄 Project Documentation



The complete step-by-step implementation guide, screenshots, configurations, and verification evidence are available below:



\[View Project Documentation](./AWS-DevOps-Project.pdf)



\## 🎯 Key Learning Outcomes



\- AWS EC2 instance deployment

\- Linux server administration

\- Nginx web server configuration

\- AMI creation

\- Launch Template configuration

\- Auto Scaling implementation

\- Application Load Balancer configuration

\- Target Group and health checks

\- High availability concepts

\- Git and GitHub



\---



\## 👨‍💻 Author



\*\*Chandrashekar G\*\*



AWS \& DevOps Learner

