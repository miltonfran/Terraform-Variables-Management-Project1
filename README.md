<h1>Terraform Variables Management Project</h1>

<h2>Description</h2>
This project demonstrates the implementation of variables in Terraform for better infrastructure code management and reusability. It organizes Terraform configurations using separate files for variables, providers, and resources while showcasing different variable types including simple variables and maps. The project emphasizes best practices for managing configuration values and sensitive data in infrastructure as code.
<br />


<h2>Languages and Utilities Used</h2>

- Terraform (HashiCorp Configuration Language - HCL)
- AWS CLI
- Git Bash

<h2>Environments Used </h2>

- <b>AWS Cloud Platform
- EC2 (Elastic Compute Cloud)
- IAM (Identity and Access Management)
- VPC Security Groups</b> 
- Windows Operating System (compatible with Linux/MacOS)

<h2>Program walk-through:</h2>

<p align="center">
1. Project Structure Setup
Create Directory Structure <br/>
- mkdir terraform-scripts
- cd terraform-scripts
- mkdir exercise2
- cd exercise2
<br />
<br />

2. Create Variables File (vars.tf)
Define Basic Variables
- Add Map Variable for AMIs <br/>
<img src="https://res.cloudinary.com/dk3bkl3ji/image/upload/v1736447492/Screenshot_2025-01-08_193603_iidos8.png"/>
<br />
<br />

3. Create Provider File (provider.tf): <br/>
Configure AWS Provider
<img src="https://res.cloudinary.com/dk3bkl3ji/image/upload/v1736452020/Screenshot_2025-01-09_144638_fnjlvu.png"/>
<br />
<br />

4. Create Instance File (instance.tf):<br/>
Define EC2 Instance Resource
<img src="https://res.cloudinary.com/dk3bkl3ji/image/upload/v1736455380/Screenshot_2025-01-08_193617_rgvunr.png"/>
<br />
<br />

5. Initialize Terraform
- Run Terraform Init
6. Validate Configuration
- Run Validation
terraform validate
7. Format Configuration
- Run Terraform Format
- terraform fmt
  8. Plan Deployment
- Review Planned Changes
- terraform plan
9. Apply Configuration
- Deploy Infrastructure
- terraform apply
<br />
<br />

10. Clean Up
- Destroy Infrastructure
- bashCopyterraform destroy
