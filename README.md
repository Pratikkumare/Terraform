# terraformcode

Terraform AWS Setup Guide

Prerequisites
- Install Terraform: https://developer.hashicorp.com/terraform/downloads
- Configure AWS CLI with your credentials:

aws configure

Enter:
- AWS Access Key
- AWS Secret Access Key
- Default region (e.g., ap-south-1)
- Output format (e.g., json)

Common Terraform Commands

Initialize Terraform
terraform init
Initializes the working directory and downloads required provider plugins.

Validate Syntax
terraform validate
Checks whether the Terraform configuration is syntactically valid.

Preview the Plan
terraform plan
Shows the changes that will be applied without actually making them.

Apply Configuration
terraform apply

Creates or updates the infrastructure as per the configuration.
Destroy Infrastructure
terraform destroy

Removes all resources created by Terraform.
Refresh State
terraform refresh

Updates the Terraform state file with the real infrastructure state.
Using Workspaces
Workspaces allow you to manage multiple environments (e.g., dev, qa, prod).
List all workspaces
terraform workspace list
Create a new workspace
terraform workspace new pratik

Switch to an existing workspace
terraform workspace select pratik
✅ Always run 'terraform plan' before 'terraform apply' to verify the changes.
