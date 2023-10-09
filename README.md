# AzureLab
Just playing around with Terraform nothing much
File : Vnet and NSG
This Terraform script does the following:

Configures the Azure provider.
Creates a resource group in the specified Azure region.
Defines a Virtual Network with an address space and associates it with the resource group.
Creates a subnet within the Virtual Network.
Defines a Network Security Group (NSG) and associates it with the resource group.
Sets up a security rule in the NSG to allow incoming SSH traffic (you can customize this rule as needed).
Outputs the IDs of the VNet and NSG for reference.
Make sure to customize the values such as the resource group name, location, address spaces, and security rule settings according to your requirements. To apply this script, run terraform init followed by terraform apply in the directory containing the .tf file.
