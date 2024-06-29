# AWS Load Balancer Terraform Project

This project uses Terraform to create an Application Load Balancer (ALB) with EC2 instances on AWS.

## Description

This Terraform configuration sets up the following resources:
- 2 EC2 instances running Apache web server
- A security group for the EC2 instances and ALB
- An Application Load Balancer
- A target group for the ALB
- Necessary VPC and subnet configurations

## Files

- `variables.tf`: Declares input variables
- `terraform.tfvars`: Sets values for input variables (make sure to add your AWS credentials)
- `main.tf`: Main configuration file that creates all AWS resources
- `output.tf`: Defines output values

## Usage

1. Ensure you have Terraform installed
2. Clone this repository
3. Navigate to the project directory
4. Update `terraform.tfvars` with your AWS credentials


## License

[MIT License](LICENSE)
