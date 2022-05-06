# VPC implementation

## Description

This implementation deploys a VPC into the dev and prod accounts

## How to deploy

The following demonstrates how to deploy the VPC implementations into the respective AWS accounts

### Command line

#### Dev

    TERRAFORM_ROOT_MODULE=vpc TERRAFORM_WORKSPACE=vpc-apse2-main-dev make apply

#### Prod

    TERRAFORM_ROOT_MODULE=vpc TERRAFORM_WORKSPACE=vpc-apse2-main-prod make apply