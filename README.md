# Intro to Terraform
  
**Definition/Overview:** HashiCorp's [Terraform](https://www.terraform.io/) is a popular example of an Infrastructure-as-Code, or ‘IaC’, software solution that serves popular cloud infrastructure providers (such as AWS, Microsoft Azure, IBM Cloud, and many more). It is utilized to streamline and otherwise simplify infrastructure provisions and deployments, providing optimal management and scalability services. Terraform defines data center infrastructure through the use of JSON or [HashiCorp Configuration Language (HCL)](https://developer.hashicorp.com/terraform/language), making flexible and reusable declarative configurations plausible.
    
#### Table of Contents
  
1. [Terraform Commands](#cmds)
2. [Command Demonstrations](#demos)
3. [Supplemental Resource](#supplemental)
  
<hr />
  
## <a name="cmds">1. Terraform Commands</a>
  
| Commands | Usages |
| :----: | ---- |
| `terraform apply` | Executes the actions/changes defined in a configuration plan. |
| `terraform destroy` | Typically used to remove (destroy) temporary objects from a configuration. |
| `terraform fmt` | Rewrites Terraform configuration files to meet HCL conventions. |  
| `terraform init` | The first command to run after creating or cloning a configuration. Establishes a working directory, containing configuration files. |
| `terraform login` | Logs in to Terraform. User can provide a hostname to log in to. |  
| `terraform logout` | Logs out of Terraform Cloud. User can provide a hostname to log out of. |
| `terraform output` | Retrieves the output variables that have been defined within a configuration. |
| `terraform plan` | Creates an execution plan for previewing infrastructure changes. |
| `terraform providers ` | Displays information about supported providers. |
| `terraform show` | Displays human readable/'pretty printed' output from a plan or state file. |
| `terraform state` | Modifies Terraform states. Generally used for more advanced configurations only. Writes backup files. |
| `terraform state list` | Displays all Terraform state file resources (request can be specified by address). |  
| `terraform validate` | Checks whether configurations are syntactically valid and consistent within (does not consult remote services). |
| `terraform version` | Retrieves presently installed version of Terraform and prompts about available updates. |
| `terraform workspace list` | Retrieves list of every available workspace. |
  
## <a name="demos">2. Command Demonstrations</a>
  
<hr />

## <a name="supplemental">3. Supplemental Resource</a>
  
* [Terraform Official Website](https://www.terraform.io/)
  
<hr />
  
TODO: Add code and CLI screenshots.
