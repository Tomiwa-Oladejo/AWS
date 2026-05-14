# AWS CloudFormation Infrastructure Automation Lab

This project demonstrates Infrastructure as Code (IaC) concepts using AWS CloudFormation. 

The lab deploys a networking layer and application layer using reusable CloudFormation templates, while also demonstrating stack updates, infrastructure visualisation, and resource lifecycle management.

## Architecture

### Network Diagram
![Network Diagram](../Screenshots/Networking_infrastructure.png)

### Application Diagram]
![Application Diagram](../Screenshots/Application_infrastructure.png)




## Technologies Used

- AWS CloudFormation
- Amazon VPC
- Amazon EC2
- Security Groups
- AWS Infrastructure Composer
- Amazon EBS

## Key Tasks Completed

- Deployed a VPC networking layer using CloudFormation
- Created an EC2 application layer referencing exported stack values
- Updated infrastructure by modifying stack templates
- Added HTTPS access through security group updates
- Explored templates using AWS Infrastructure Composer
- Implemented EBS snapshot retention with DeletionPolicy

## Concepts Learned

### Infrastructure as Code (IaC)
Infrastructure can be deployed consistently and repeatedly using templates instead of manual configuration.

### Stack Outputs and Imports
CloudFormation outputs were exported from the networking stack and imported into the application stack using Fn::ImportValue.

### Change Sets and Stack Updates
CloudFormation updates only modified resources instead of rebuilding the entire environment.

### Resource Lifecycle Management
Deletion policies can preserve important resources such as EBS snapshots after stack deletion.

## Key Takeaways

This project improved my understanding of AWS CloudFormation, infrastructure automation, and layered cloud architecture. It also demonstrated the benefits of repeatable deployments and infrastructure versioning.
