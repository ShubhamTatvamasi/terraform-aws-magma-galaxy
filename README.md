# terraform-aws-magma-galaxy

Initalize Terraform:
```bash
terraform init
```

Create a VM:
```bash
export TF_VAR_spot_instance=true
terraform apply -auto-approve
```

Destroy the VM:
```bash
terraform destroy -auto-approve
```
