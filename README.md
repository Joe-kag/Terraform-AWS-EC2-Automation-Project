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

<img width="879" height="707" alt="Screenshot From 2025-04-19 11-24-50" src="https://github.com/user-attachments/assets/c7647f75-ce05-4d15-9a5c-4857cb6aca9d" />


Deploying multiple EC2 instances with a single command using terraform apply

Safely tearing down infrastructure using terraform destroy

Writing clean and modular .tf files

<img width="1918" height="882" alt="Screenshot From 2025-04-08 14-42-44" src="https://github.com/user-attachments/assets/5dc71ea6-b00f-414a-9b4f-ca37e6eb4d61" />


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

<img width="1918" height="882" alt="Screenshot From 2025-04-19 12-50-22" src="https://github.com/user-attachments/assets/1a6e6fc8-8530-4fe2-a1eb-18ca704a658b" />


Integrate with IAM roles and key pairs securely
<img width="1918" height="882" alt="Screenshot From 2025-04-19 12-50-53" src="https://github.com/user-attachments/assets/a478c6e6-0620-4821-a0c5-e428ce0bd062" />
   
