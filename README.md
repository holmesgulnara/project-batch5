Setup Instructions
To get started, follow these steps:

Create AWS Access and Secret Key

Ensure you have the right permissions to create a VPC and EC2 instances.
Set Environment Variables Run the following commands in your terminal to set up the necessary environment variables:

export AWS_ACCESS_KEY_ID="your_access_key"
export AWS_SECRET_ACCESS_KEY="your_secret_access_key"

Create terraform.tfvars in terraform folder

region = "us-east-2"
vpc_cidr = "10.0.0.0/0"
subnet1_cidr = "10.0.1.0/0"
subnet2_cidr = "10.0.2.0/0"
subnet3_cidr = "10.0.3.0/0"
ip_on_launch = true
instance_type = "t2.micro"
Run ./script.sh
