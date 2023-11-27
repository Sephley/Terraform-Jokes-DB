# Terraform-Jokes-DB

All credentials are stored in the `.aws/credentials` file.  
Since this file is referenced in the `.gitignore`, you will have to create this yourself.

These credentials can be obtained from the AWS Learnerlab.

## Usage

1. Install Terraform on your local machine
2. Clone this repository
3. Create the file `.aws/credentials` and insert your credentials
4. Run `terraform init` to initialize the project (only do this once)
5. Use `terraform plan` and `terraform apply` to your hearts content