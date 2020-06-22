# Terraform
## Characteristics of IaC:
	* Defined in code
	* Stored in source control, versioned (GIT etc)
	* Declarative instead of imperative
	* Idempotent and consistent (Knows the state)
	* Push instead of pull based

## Infrastructure as Code benefits: (We can use icons)
	Automated Deployment
	Consistent environments
	Repeatable process
	Reusable components (DRY Dont repeat yourself)
	Documented architecture

Automating infrastructure
## Terraform Components
	Terraform executable
	Terraform files
	Terraform plugins (to interact with providers for eg AWS, GCP)
	Terraform state file (Tracks the current state of the configuration, 
	    while updating Terraform compares your new configuration to what is in the state file
	    and then makes the necessary changes so that the state matches your desired configuration.)
	Credentials to login
	Define variables
	Provider
	Data source (get some information from provider)
	Resource
	Output
	terraform init (Downloads the plugin if not present)
	terraform plan
	terraform apply
	terraform destroy
