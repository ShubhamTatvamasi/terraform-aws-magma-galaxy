# terraform-aws-magma-galaxy

Update your region in `main.tf` file.

Initalize Terraform:
```bash
terraform init
```

Create a VM:
```bash
# Set this if you want to use this for testing, so it will be you temp VM with 70% discount.
export TF_VAR_spot_instance=true

# Set this if you want to use this for production.
export TF_VAR_instance_type=t3a.xlarge

terraform apply -auto-approve
```

Destroy the VM:
```bash
terraform destroy -auto-approve
```
