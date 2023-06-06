ITI-Terraform-Project
This is a project associated with terraform course in the Intensive Code Camp program Systems Administration track at ITI.
In this project we implement this design
What is state and why is it important in Terraform?
Terraform must store state about your managed infrastructure and configuration. This state is used by Terraform to map real world resources to your configuration, keep track of metadata, and to improve performance for large infrastructures. This state file is extremely important; it maps various resource metadata to actual resource IDs so that Terraform knows what it is managing. This file must be saved and distributed to anyone who might run Terraform.
