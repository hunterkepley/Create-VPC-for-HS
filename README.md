# Create VPC for HyperShift Terraform Script

To run, download Terraform for your distro

Then, run `terraform init` in the root directory of this project

Finally, run `terraform apply` to run the script. Type `yes` at the end and hit enter to apply the AWS changes.

## Site name

The "site name" is going to be the prefix of your vpc and resources. Please name it something useful so you can find it later.

## Region

Change your AWS region using `aws configure` to change the region for this script. Same goes for your AWS credentials.
