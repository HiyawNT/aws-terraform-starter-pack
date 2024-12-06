<!-- PROJECT LOGO -->
<p align="center">
    <img src="https://logodix.com/logo/1686050.png" alt="minio-api" width="200">
  </a>

  <h3 align="center" style="font-weight: bold">AWS TERRAFORM STARTER-PACK</h3>

  <p align="center">
    A set of useful terraform templates to manage AWS resources
    <br />
    

  </p>
</p>


<!-- ABOUT THE PROJECT -->
## About The Project

Terraform templates provide a set of HCL templates to manage AWS resources using `IAC` concepts (Infraestructure As A Code). 

<!-- TECHNOLOGIES -->
### Built With

* [Terraform](https://www.terraform.io)

<!-- GETTING STARTED -->
## Getting Started

To apply terraform templates, `Terraform` must first be installed on your machine. Terraform is distributed as a binary package for all supported platforms and architectures.

### Prerequisites

Before running terraform templates, download [terraform client](https://www.terraform.io/downloads.html) and [install](https://learn.hashicorp.com/terraform/getting-started/install.html) acconding to your `OS`.

### Installation

1. Clone the repo:
```sh
git clone https://github.com/HiyawNT/aws-terraform-starter-pack.git
```
2. Access the desired terraform template and fill out all [variables](iam_roles/variables.tf):
```sh
cd terraform-templates/iam_roles
```
3. Init terraform provider:
```sh
terraform init
```
4. Verify all changes to be applied:
```sh
terraform plan
```
4. Check all changes and apply the template:
```sh
terraform apply
```
