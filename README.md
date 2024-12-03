# Intro to Terraform
  
**Definition/Overview:** HashiCorp's [Terraform](https://www.terraform.io/) is a popular example of an Infrastructure-as-Code, or ‘IaC’, software solution that serves popular cloud infrastructure providers (such as AWS, Microsoft Azure, IBM Cloud, and many more). It is utilized to streamline and otherwise simplify infrastructure provisions and deployments, providing optimal management and scalability services. Terraform defines data center infrastructure through the use of JSON or [HashiCorp Configuration Language (HCL)](https://developer.hashicorp.com/terraform/language), making flexible and reusable declarative configurations plausible.
<br /><br />
**Some commands to know when navigating the command line interface...**

| Commands | Usages |
| ---- | ---- |
| **terraform apply** | Executes the actions/changes defined in a configuration plan. |
| **terraform destroy** | Typically used to remove (destroy) temporary objects from a configuration. |
| **terraform fmt** | Rewrites Terraform configuration files to meet HCL conventions. |  
| **terraform init** | The first command to run after creating or cloning a configuration. Establishes a working directory, containing configuration files. |
| **terraform plan** | Creates an execution plan for previewing infrastructure changes. |
| **terraform show** | Displays human readable/'pretty printed' output from a plan or state file. |
| **terraform state** | Modifies Terraform states. Generally used for more advanced configurations only. Writes backup files. |
| **terraform state list** | Displays all Terraform state file resources (request can be specified by address). |  
| **terraform validate** | Checks whether configurations are syntactically valid and consistent within (does not consult remote services). |
