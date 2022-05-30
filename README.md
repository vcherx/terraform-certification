# terraform-certification
A repo with the resources I have used to get ready for the terraform associate cert. 

## Learn about Iac
### What is IaC?
- IaC stands for Infrastructure as Code. It is a way to define Infrastructure resources (CPUS, memory, disk, firewalls...) in code files that can be versioned. 
- With IaC, we can automate manual processes and gives a way to improve cloud adoption. 

### IaC and the Infrastructure Lifecycle.
- IaC can be applied on the initial life of the infrastructure or throught the lifecycle. 
- Day 0 -  Code that provision and configures the initial infrastructure. 
- Day 1 - OS and application configuration you apply after you have the initially built infrastructure. This can be applied to Day N configurations.

### Benefits of IaC
- Keep track of the changes with version control tools. 
- Easy to provision and saving time. We can replicate the infrastructure as needed. 
- Human readable (talking about a tool as terraform). 
- Makes changes idempotent, consistent, repeatable and pradictable. 
- We can test the code before applying the changes (terraform plan). 

### IaC tools. 
- [Hashicorp Terraform 🌎](terraform.io)
- [AWS Cloudformation](aws.amazon.com/cloudformation)
- [Azure Resource Manager ARM](azure.microsoft.com)
- [Pulumi](pulumi.com)

## Manage Infrastructure 

