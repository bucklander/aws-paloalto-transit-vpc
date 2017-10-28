# aws-transit-vpc for Palo Alto Firewalls
Source code for the AWS Transit VPC customized to use Palo Alto VM appliances versus Cisco's CSR. The goal with this project is to insert NGFW inspection and ultimatey better visibility into all inter-VPC communication.  
Forked from https://github.com/awslabs/aws-transit-vpc  

*Disclaimer: This project is in no way associated, officially or unofficially, with Palo Alto Networks. Use at your own risk.*

## Cloudformation templates

- transit-vpc-primary-account.template
- transit-vpc-second-account.template

## Lambda source code

- transit-vpc-poller.py
- transit-vpc-push-paloalto-config.py
