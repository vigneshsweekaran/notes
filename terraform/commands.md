# Terraform commands

### terraform init
will read the .tf files, and download the providers mentioned in the .tf files

### terraform plan
It a dry-run and will show the output, what will be created, deleted or modified

### terraform apply
Will execute the the .tf file and create, delete or modify the resource mentioned in the .tf file

### terraform destroy
Will destroy the resources defined in .tf, if it was created before using terrform apply

### To skip typing 'yes' during terraform apply and destroy
terraform apply --auto-approve