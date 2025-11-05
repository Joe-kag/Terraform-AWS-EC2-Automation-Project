Project Overview

This project demonstrates how to automate the deployment of EC2 instances on AWS using Terraform, an Infrastructure as Code (IaC) tool. 
The goal was to gain hands-on experience in writing Terraform configuration files and managing AWS resources efficiently and securely.

Project Structure

├── provider.tf     # AWS provider configuration
├── ec2.tf          # EC2 instance configuration


🔧 Tools & Technologies
🌩️ Terraform

☁️ Amazon Web Services (AWS)

🛠️ CLI (Command Line Interface)

💻 VS Code (Editor)

🧠 What I Learned
How to configure and initialize a Terraform project using terraform init

Validating and planning infrastructure changes using terraform validate and terraform plan

Deploying multiple EC2 instances with a single command using terraform apply

Safely tearing down infrastructure using terraform destroy

Writing clean and modular .tf files

ow to Use
Clone the repo:

git clone https://github.com/joe/terraform-ec2-project.git
cd terraform-ec2-project
Initialize Terraform:


terraform init

terraform plan
Apply the configuration:


terraform apply
Destroy resources when done:


terraform destroy

💡 Future Improvements

Add security groups for more control over traffic

Use variables and outputs for better flexibility

Deploy in multiple availability zones

Integrate with IAM roles and key pairs securely

🤝 Let’s Connect
If you're a recruiter, cloud enthusiast, or just someone who loves Terraform, feel free to connect with me here or on LinkedIn.

https://www.linkedin.com/in/joseph254/      
