# *AWS Project: Jenkins and Docker on EC2*

### *About the Project*
This project demonstrates the integration of various tools and technologies in a cloud environment to set up a CI/CD pipeline. It highlights the following:
- Setting up *EC2 Instances*.
- Installing and configuring *Jenkins* and *Docker* on Linux servers.
- Using *Terraform* for infrastructure management.
- Creating a custom *Docker image* for deployments.

---

### *Features*
1. *EC2 Instances*: Provisioned and configured for SSH access.
2. *Jenkins*: Installed on a Linux server to enable CI/CD workflows.
3. *Docker*: Used for containerizing applications.
4. *Terraform*: Infrastructure automation to manage AWS resources.

---

### *Architecture*
Here’s a high-level view of the workflow:

![Architecture Diagram](images/architecture-diagram.png)

The architecture demonstrates the interaction between AWS EC2, Jenkins, Docker, and Terraform to automate deployments.

---

### *Screenshots*
#### EC2 Instance Creation
The following screenshot shows the EC2 instances configured for the project:
![EC2 Instances](images/ec2-instance.png)

#### Jenkins Setup
Jenkins running successfully on a Linux server:
![Jenkins Setup](images/jenkins-setup.png)

#### Docker Image
A custom Docker image created for deployment:
![Docker Image](images/docker-image.png)

---

### *Technologies Used*
- *AWS EC2*: Compute resources for hosting services.
- *Jenkins*: CI/CD tool for automating tasks.
- *Docker*: Containerization for application isolation.
- *Terraform*: Infrastructure as Code (IaC) for automating AWS resources.
- *Linux*: Server operating system for all configurations.

---

### *Getting Started*
Follow these steps to replicate the project:

1. *Provision EC2 Instances*: Use the AWS Management Console or Terraform scripts.
2. *Connect via SSH*: Access instances and configure the environment.
3. *Install Jenkins and Docker*: Follow the setup steps provided in the documentation.
4. *Create a Docker Image*: Use the Docker CLI to build and run the image.

---

### *Project Outcomes*
- A fully functional Jenkins pipeline configured on AWS EC2.
- Dockerized application ready for deployment.
- Automated infrastructure management using Terraform.

---

### *Future Enhancements*
- Integrate Kubernetes for container orchestration.
- Automate deployments further with Terraform modules.

---

### *Repository Structure*
