# Terraform Code Challenge

This is a terraform code to deploy a web server and a database, including network configuration, security management, monitoring, and best practices. The code can be divided into multiple sections:

### Network Infrastructure

- Create a VPC with CIDR block
- Create subnets
- Create an internet gateway
- Create a route table and route table association

### Application and Database Infrastructure

- Create EC2 instance for the web server
- Create RDS instance for the database

### Monitoring

- Create CloudWatch Logs for the web server
- Create CloudWatch alarms for CPU utilization
- Add SNS topic to send notifications

### Security

- Create security groups for the web server and database, and allow only HTTP and HTTPS traffic to the web server, and MySQL traffic to the database only through the server.
- Create private subnet for the database and public subnet for the web server.

# Results

run `terraform plan` to see a dry-run of the terraform code. You can check the `plan_output.txt` file to see the output of the plan.
