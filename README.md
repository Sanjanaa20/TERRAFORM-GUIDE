# TERRAFORM
HashiCorp created the well-known IAC tool Terraform, which is free and open source and installs as a single program and enables us to create, maintain, and destroy infrastructure.

Provisioning tools - TERRAFORM 
- Deploys immutable infrastructure resources

How Terraform manages infrastructure on many different platforms ?
It is achieved through providers, helps to manage third party platforms through API.Terraform uses HCL which stands for HashiCorp Configuration Language which is simple,declarative language
to define infrastructure resources to a provisioned as block of code.
Every object that the terraform manage is called RESOURCE.

EXTENSION: .tf file extension
## PHASES:
INIT
PLAN
APPLY

**HASHICORP CONFIGURATION LANGUAGE**
_Syntax_
```
<block> <parameters> {
key1 = value1
key2 = value2
}
```
Define the resource block as main.tf in any platform suck as Visual Studio VScode.

- Use `terraform init` to initiate the configuration file.
- Use `terraform plan` to start the actions carried out by terraform file (+) indicated created.
- Use `terraform apply` to apply the creation of the file.

### We can deploy resources in AWS cloud, Azure , Ali Cloud , GCP etc
