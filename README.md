# DevOps Bootcamp - Learning and Hands-on Labs Repository

Welcome to my **DevOps Bootcamp** repository! This repository showcases my journey through the **DevOps Bootcamp** course from **Udemy** ([The Complete DevOps Bootcamp](https://www.udemy.com/course/the-complete-devops-bootcamp)) and the associated hands-on labs available on **KodeKloud** ([KodeKloud Labs for Udemy's DevOps Bootcamp](https://learn.kodekloud.com/user/courses/udemy-labs-the-complete-devops-bootcamp)). 

In this repository, I document the key DevOps concepts, tools, hands-on exercises, and labs that I've completed as part of this comprehensive course. The following sections will walk you through the tools I’ve learned, practical use cases, and my progress in mastering DevOps practices.

## Table of Contents

1. [Overview of DevOps](#overview-of-devops)
2. [Linux Basics](#linux-basics)
3. [Networking Basics](#networking-basics)
4. [Git Basics](#git-basics)
5. [Docker and Containers](#docker-and-containers)
6. [Kubernetes Concepts](#kubernetes-concepts)
7. [Learn IaC with Terraform](#learn-iac-with-terraform)
8. [Basic Python Programming](#basic-python-programming)
9. [Hands-on Labs](#hands-on-labs)
10. [Conclusion](#conclusion)
11. [How to Use This Repo](#how-to-use-this-repo)

---

## 1. **Overview of DevOps**

### **Theory:**
DevOps is a set of practices, cultural philosophies, and tools that bring together development and operations teams to deliver software faster and more reliably. The main focus of DevOps is automation, collaboration, and continuous improvement.

### **Key Concepts**:
- **Continuous Integration (CI)**: Automated testing and integration of code changes into a shared repository.
- **Continuous Delivery (CD)**: Ensuring that software is always in a deployable state and can be pushed to production at any time.
- **Automation**: Automating repetitive tasks like deployment, testing, and infrastructure management.
- **Collaboration**: Bridging the gap between development and operations teams to improve communication and collaboration.

### **Tools and Technologies**:
- Jenkins, GitLab CI, CircleCI, Docker, Kubernetes, Terraform, Ansible, Python

---

## 2. **Linux Basics**

### **Theory:**
Linux is the backbone of most server and cloud infrastructures. DevOps professionals need to be proficient in Linux to manage servers, configure applications, and troubleshoot issues effectively.

### **Key Commands and Use Cases**:
- `sudo apt update`: Update the package list on a Debian-based system.
- `sudo apt install <package_name>`: Install a software package.
- `cd <directory>`: Change the current directory.
- `ls`: List the contents of the current directory.
- `pwd`: Print the current working directory.
- `rm -r <directory>`: Remove a directory recursively.
- `chmod <permissions> <file>`: Change file permissions.

### **Use Case**:
- Managing servers and configuring infrastructure.
- Automating server setup with shell scripting.

---

## 3. **Networking Basics**

### **Theory:**
Networking is essential for the configuration and management of distributed systems, containers, and cloud-based services. A strong understanding of networking helps to ensure reliable and secure communication between applications.

### **Key Commands and Use Cases**:
- `ping <ip_address>`: Test network connectivity.
- `curl <url>`: Fetch data from a URL.
- `ifconfig` or `ip addr`: Display and configure network interfaces.
- `netstat`: Display open network connections and ports.

### **Use Case**:
- Configuring and troubleshooting network connectivity in multi-server environments.
- Ensuring communication between containers and cloud resources.

---

## 4. **Git Basics**

### **Theory:**
Git is a distributed version control system that allows developers to track changes, collaborate on code, and maintain version history. It is essential for managing code in DevOps.

### **Key Commands and Use Cases**:
#### **Repository Operations**:
- `git init`: Initialize a Git repository.
- `git status`: Show the status of the repository (staged, unstaged, untracked files).
- `git add <file>`: Stage a file for commit.
- `git commit -m "message"`: Commit staged changes with a custom message.
- `git log`: View the commit history.
- `git log --oneline`: View a simplified version of the commit history.

#### **Branching and Merging**:
- `git branch <branch_name>`: Create a new branch.
- `git checkout <branch_name>`: Switch to a branch.
- `git merge <branch_name>`: Merge a branch into the current branch.
- **Conflict Resolution**: Git marks conflicts in files with `<<<<<<<`, `=======`, and `>>>>>>>`.

#### **Remote Operations**:
- `git remote add origin <repo_url>`: Add a remote repository.
- `git push <remote_name> <branch_name>`: Push local changes to the remote repository.
- `git pull <remote_name> <branch_name>`: Fetch and merge changes from the remote repository.

---

## 5. **Docker and Containers**

### **Theory:**
Docker is a platform used to automate the deployment of applications in lightweight containers. These containers package applications with all necessary dependencies, making them portable across different environments.

### **Key Commands and Use Cases**:
#### **Container Operations**:
- `docker run <image_name>`: Run a container from an image.
- `docker ps`: List all running containers.
- `docker exec -it <container_name> bash`: Access a running container’s shell.
- `docker stop <container_name>`: Stop a running container.
- `docker rm <container_name>`: Remove a container.

#### **Image Operations**:
- `docker build -t <image_name> .`: Build a Docker image from a Dockerfile.
- `docker pull <image_name>`: Pull a Docker image from a repository.

#### **Volumes and Networks**:
- `docker network ls`: List Docker networks.
- `docker volume ls`: List Docker volumes.

### **Use Case**:
- Containerizing applications for consistent execution across development, staging, and production environments.

---

## 6. **Kubernetes Concepts**

### **Theory:**
Kubernetes is an open-source container orchestration platform that automates the deployment, scaling, and management of containerized applications.

### **Key Commands and Use Cases**:
- `kubectl get pods`: List all pods in the Kubernetes cluster.
- `kubectl apply -f <file>.yaml`: Create or update a Kubernetes resource.
- `kubectl scale deployment <deployment_name> --replicas=<number>`: Scale the application.
- `kubectl describe pod <pod_name>`: Display detailed information about a specific pod.
- `kubectl logs <pod_name>`: View logs of a specific pod.

### **Use Case**:
- Orchestrating containers across a cluster of servers.
- Automating deployment and scaling of applications.

---

## 7. **Learn IaC with Terraform**

### **Theory:**
Terraform is an Infrastructure as Code (IaC) tool that allows you to define and provision cloud infrastructure using configuration files. With Terraform, you can manage infrastructure in a version-controlled, repeatable way.

### **Key Commands and Use Cases**:
- `terraform init`: Initialize Terraform configuration.
- `terraform plan`: Show the changes Terraform will make to your infrastructure.
- `terraform apply`: Apply the Terraform configuration to provision resources.
- `terraform destroy`: Destroy the infrastructure created by Terraform.

### **Use Case**:
- Automating cloud infrastructure provisioning such as virtual machines, networking, and databases.

---

## 8. **Basic Python Programming**

### **Theory:**
Python is a versatile, easy-to-learn programming language used in DevOps for scripting, automation, and configuration management.

### **Key Commands and Use Cases**:
- `python <script.py>`: Run a Python script.
- `pip install <package_name>`: Install Python packages.
- `pip freeze`: Generate a list of installed Python packages in requirements.txt format.
- `def <function_name>()`: Define a function.

### **Use Case**:
- Writing automation scripts for infrastructure tasks such as server setup and log analysis.

---

## 9. **Hands-on Labs**

These labs were provided through **KodeKloud** and accessible after purchasing the course on Udemy. They reinforce all concepts discussed in the course with practical, hands-on exercises.

### **Lab 1: Git Version Control**
- **Objective**: Initialize a Git repository, commit code changes, and create branches to manage features or fixes.
- **Commands**: `git init`, `git add`, `git commit -m "message"`, `git branch`, `git merge`

### **Lab 2: Docker Containers**
- **Objective**: Build a custom Docker image, run a container, and interact with the container’s shell.
- **Commands**: `docker build`, `docker run`, `docker ps`, `docker exec`

### **Lab 3: Kubernetes Cluster Management**
- **Objective**: Set up a Kubernetes cluster, deploy applications, and scale pods in the cluster.
- **Commands**: `kubectl apply -f`, `kubectl scale`, `kubectl get pods`

### **Lab 4: Terraform Cloud Infrastructure Deployment**
- **Objective**: Use Terraform to provision resources such as EC2 instances, S3 buckets, or networking components.
- **Commands**: `terraform init`, `terraform plan`, `terraform apply`, `terraform destroy`

### **Lab 5: Python Scripting for Automation**
- **Objective**: Write Python scripts to automate tasks like file management, network checks, and cloud configurations.
- **Commands**: `python`, `pip install`, `pip list`, `pip freeze`

---

## 10. **Conclusion**

This repository reflects my learning journey through the **DevOps Bootcamp**. By completing the course, I’ve developed proficiency in essential DevOps tools such as **Linux**, **Git**, **Docker**, **Kubernetes**, **Terraform**, and **Python**. Through practical labs on **KodeKloud**, I’ve gained hands-on experience in deploying cloud infrastructure, managing containerized applications, and automating tasks.

---

## 11. **How to Use This Repo**

1. Clone the repository:
   ```bash
   git clone https://github.com/JaninduPremathilaka/Devops-bootcamp-kodecloud.git

---

## 📌 Connect with Me

- 💼 [LinkedIn – Janindu Premathilaka](https://www.linkedin.com/in/janindupremathilaka)

---
