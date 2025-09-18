docker_task
🛠️ Tech Stack
AWS EC2 (Amazon Linux)

Docker Engine

Bash Shell

SSH (Command Line Access)

📚 References
Docker Documentation – Get Started

AWS Documentation: EC2 User Guide, Docker on Amazon Linux

General Linux CLI Practices

📸 Screenshots
All outputs and verification steps, including Docker installation, permissions, image/container/volume/network listings, and sample runs, are included as screenshots for evidence and submission compliance.

📝 Submission
Submitted for GUVI DevOps AWS + Docker Assignment.
All required files and screenshots have been uploaded to my GitHub repository as per assignment guidelines.

✅ Tasks Performed
Provisioned AWS EC2 Instance

Launched Amazon Linux EC2, configured networking and inbound rules for SSH/ICMP.

Verified public IP and connectivity.

Installed Docker

Enabled and installed Docker using Amazon Linux Extras.

Started and enabled Docker service.

Configured Docker User Permissions

Added ec2-user to the docker group.

Resolved access issues by reconnecting SSH and using newgrp docker.

Explored Docker CLI Commands

Listed available images:

text
docker images
Listed all containers (active and inactive):

text
docker ps -a
Listed Docker volumes:

text
docker volume ls
Listed Docker networks:

text
docker network ls
Ran a sample container to show usage:

text
docker run hello-world
Verified after running: images and containers populating command outputs.

(Optional) Deployed a Demo Web Server

Ran a persistent nginx container for extra demonstration:

text
docker run -d --name webserver nginx
docker ps -a
Verification and Logging

Included full screenshots of each step, showing commands, results, and successful completion.

💡 Example Commands Used
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
🔎 Summary
This assignment demonstrates end-to-end Docker installation and command usage on an AWS EC2 Linux instance, covering setup, troubleshooting, container operations, and evidence documentation for DevOps practice and validation
