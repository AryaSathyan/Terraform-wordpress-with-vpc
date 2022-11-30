# terraform-wordpress-provision

In this document, we will discuss how to create infra and deploy WordPress on it using Terraform. We are going to create one VPC with three subnets: two private and one public, as well as 1 NAT gateway, 1 Internet gateway, and 2 route tables.

As you can see, we are creating 3 instances - a bastion, a frontend, and a backend. WordPress frontend is installed and a MariaDB backend instance is installed. By sshing to bastion server, we are only able to connect to the frontend and backend instances.

This code will lead us to the WordPress installation page after we run it.
