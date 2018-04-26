## Terraform Configuration for One t2.micro Instance

In order to use this configuration you must already have an AWS account set up.
You will also need your access keys to put in the configuration file, `plan.tf`.
Keys can be found [here](https://console.aws.amazon.com/iam/home?#security_credential).

After entering your keys in `plan.tf` you can launch the t2.micro instance via `terraform init` then `terraform apply`.
