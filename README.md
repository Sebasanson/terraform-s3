# terraform-s3

My first Terraform project: creates an S3 bucket on AWS from code.

## What I learned
- Infrastructure as code: describe what should exist, preview it with `terraform plan`, create it with `terraform apply`, and remove it with `terraform destroy`
- Keeping Terraform state files out of Git with a `.gitignore`

## How to run it
1. Install Terraform and the AWS CLI, and log in to AWS
2. Change the bucket name in `main.tf` (names must be unique worldwide)
3. `terraform init`, then `terraform plan`, then `terraform apply`
4. Clean up with `terraform destroy`
