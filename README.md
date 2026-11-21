# Project 2: Host a Static Website on Amazon S3 Using Terraform

## Task 1: Implementation

1. Configured the AWS provider to use the `ap-south-1` region.
2. Created an Amazon S3 bucket using Terraform.
3. Created an `index.html` file containing the website homepage.
4. Enabled static website hosting on the S3 bucket.
5. Configured the bucket's public access settings.
6. Created an S3 bucket policy to allow public read access to website objects.
7. Uploaded `index.html` to the S3 bucket using Terraform.
8. Initialized Terraform using `terraform init`.
9. Formatted the configuration using `terraform fmt`.
10. Validated the configuration using `terraform validate`.
11. Reviewed the infrastructure changes using `terraform plan`.
12. Deployed the resources using `terraform apply`.
13. Retrieved the website endpoint from Terraform outputs.
14. Tested the website using `curl` and received an HTTP 200 OK response.

## Deployment Details

| Detail | Value |
|---|---|
| AWS Service | Amazon S3 |
| Region | ap-south-1 |
| Bucket Name | cloud-capstone-p2-static-website-1795251570 |
| Website File | index.html |
| Status | Successfully deployed |

## Website URL

http://cloud-capstone-p2-static-website-1795251570.s3-website.ap-south-1.amazonaws.com

## Evidence

Screenshot of the url attached
