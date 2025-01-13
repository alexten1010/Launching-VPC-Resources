# Launching-VPC-Resources

## Launching VPC Resources is a project designed to automate and manage the creation of essential resources within an AWS Virtual Private Cloud (VPC). This includes subnets, route tables, internet gateways, NAT gateways, and security groups to build a fully functional networking environment in AWS.

## Features

* Automated Resource Creation: Easily launch VPCs and associated networking components.

* Customizable Architecture: Specify CIDR blocks, subnet configurations, and routing policies.

* High Availability: Deploy resources across multiple availability zones.

* Secure Networking: Set up security groups and network ACLs for traffic control.

* Scalable: Add additional resources as required to support growing applications.

 ## Setup and Installation
 * Configure Environment Variables**:

* Copy the example environment file:
cp .env.example .env

* Update .env with your AWS Region, CIDR blocks, and other configuration parameters.

* Run Deployment Scripts:

* Install dependencies:
pip install -r requirements.txt

* Launch VPC resources:
python launch_vpc_resources.py

* Verify Resources:

Check the AWS Management Console under VPC to confirm resource creation.

Use AWS CLI commands to inspect the resources:
* aws ec2 describe-vpcs
* aws ec2 describe-subnets
