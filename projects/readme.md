
## Author
This project is maintained by '[end-to-end Solution Architect](https://e2esolutionarchitect.com/)'. Please feel free to drop a note to contactus@e2eSolutionArchitect.com for any queries

## Permission
end-to-end Solution Architect forum is contributing this as knowledge sharing. You are free to use and modify this.

## How to execute
- Step 1: terraform init
- Step 2: terraform validate
- Setp 3: terraform plan -var-file="app.tfvars" -var="createdby=e2esa"
- Setp 4: terraform apply -var-file="app.tfvars" -var="createdby=e2esa"
- Setp 5: terraform destroy -var-file="app.tfvars" -var="createdby=e2esa"

every project and module has separate readme file and tf-spec.md. Please read that for specific instructions. 

Rename app_tfvars file name to as app.tfvars and then execute  below command
```
 terraform apply -var-file="app.tfvars" -var="createdby=e2esa"
```

## Run terraform-docs to generate tf document
browse inside your terraform project directory and run the below command 

```
terraform-docs markdown table . > tf-spec.md
```

