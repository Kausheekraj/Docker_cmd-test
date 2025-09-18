
---

🚀 Docker on AWS EC2 – Assignment

🛠️ Tech Stack

AWS EC2 (Amazon Linux)

Docker Engine

Bash Shell

SSH



---

📚 References

Docker Documentation – Get Started

AWS EC2 User Guide

Linux CLI tutorials



---

✅ Tasks Performed

1. EC2 Instance Provisioning

Launched Amazon Linux EC2 instance.

Configured inbound rules for SSH (22) and ICMP (ping).

Verified public IP connectivity.


2. Docker Installation & Permissions

Installed Docker using Amazon Linux Extras.

Started and enabled Docker service.

Added ec2-user to the Docker group for non-root access.


3. Docker CLI Exploration

Listed Docker images:

docker images

Listed all containers:

docker ps -a

Listed volumes and networks:

docker volume ls
docker network ls

Ran hello-world container to verify Docker functionality:

docker run hello-world

(Optional) Deployed an nginx test server:

docker run -d --name webserver nginx
docker ps -a


4. Verification

Attached screenshots for every step: installation, verification, Docker usage, and troubleshooting.



---

💻 Example Commands

# System update
sudo yum update -y  

# Install Docker
sudo amazon-linux-extras install docker  

# Start Docker service
sudo systemctl enable docker  
sudo systemctl start docker  

# Add user to docker group
sudo usermod -aG docker ec2-user  

# Docker usage
docker images  
docker ps -a  
docker volume ls  
docker network ls  
docker run hello-world  
docker run -d --name webserver nginx


---

🔎 Summary

This project demonstrates:

✅ Provisioning and configuring AWS EC2

✅ Installing and managing Docker Engine

✅ Exploring Docker images, containers, volumes, and networks

✅ Running test containers (hello-world, nginx)

✅ Capturing troubleshooting and verification evidence


📸 All required screenshots have been included in this repository as proof of completion.


---
