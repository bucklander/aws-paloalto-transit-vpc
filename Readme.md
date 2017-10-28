# aws-transit-vpc for Palo Alto Firewalls
Source code for the AWS Transit VPC customized to use Palo Alto VM appliances versus Cisco's CSR. The goal with this project is to insert NGFW inspection and ultimately better network visibility into all inter-VPC communication, something lacking in with the existing design.  
Forked from https://github.com/awslabs/aws-transit-vpc  

*Disclaimer: This personal project is in no way associated, officially or unofficially, with Palo Alto Networks. Use at your own risk.*

## Cloudformation templates

- transit-vpc-primary-account.template
- transit-vpc-second-account.template

## Lambda source code

- transit-vpc-poller.py
- transit-vpc-push-paloalto-config.py
