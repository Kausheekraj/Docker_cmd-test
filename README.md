docker_task
🛠️ Tech Stack
AWS EC2 (Amazon Linux)

Docker Engine

Bash Shell

SSH

📚 References
Docker Documentation: Get Started

AWS EC2 User Guide

Linux CLI tutorials

📸 Screenshots
All outputs (installation, verification, Docker usage, and troubleshooting) are included as screenshots in this repository.

📝 Submission
Submitted for GUVI DevOps AWS & Docker Assignment.
All required evidence and instructions have been uploaded according to guidelines.

✅ Tasks Performed
EC2 Instance Provisioning

Launched Amazon Linux EC2 and configured inbound rules for SSH and ICMP.

Verified public IP connectivity.

Docker Installation and Permissions

Installed Docker via Amazon Linux Extras.

Started Docker service and enabled non-root access for ec2-user.

Docker CLI Exploration

Listed Docker images:

text
docker images
Listed all containers:

text
docker ps -a
Listed volumes and networks:

text
docker volume ls
docker network ls
Ran hello-world container to verify functionality:

text
docker run hello-world
(Optional) Launched nginx test server:

text
docker run -d --name webserver nginx
docker ps -a
Verification

Screenshots attached for every command’s output and proof of completion.

💡 Example Commands
text
sudo yum update -y
sudo amazon-linux-extras install docker
sudo systemctl enable docker
sudo systemctl start docker
sudo usermod -aG docker ec2-user

docker images
docker ps -a
docker volume ls
docker network ls
docker run hello-world
docker run -d --name webserver nginx
   ------
🔎 Summary
This project demonstrates complete Docker setup and usage on AWS EC2, covering installation, troubleshooting, basic container management, and CLI output documentation for DevOps readiness.
