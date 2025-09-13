# Class-7

1. Start by configuring a provider.tf file, then run "terraform init" in the CLI to start your working directory.
2. After terraform innit is complete, create a main.tf file and use a data block to retrieve information from your default VPC.
3. In the Same main.tf file use a resource block for an Ec2 instance configuration along with a security group and security group rules.
4. Next make sure your files are saved and run a terraform init command to access the latest terraform update and provider plugins.
5. After your files are saved and terraform/plugins are up-to-date, run a terraform plan to see what resources you are creating.
6.After terraform has planned your new configuration run terraform apply to create the real world resources.
7.Once terraform has created the resources you wanted and you are satisfied with the creation use terraform destroy to destroy your your real world resources through the CLI.
