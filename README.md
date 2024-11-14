# Terraform Infrastructure Pipeline

This repository automates the process of managing and deploying infrastructure using Terraform and integrates with Google Cloud Build for continuous deployment. Every change to the repository triggers a pipeline that runs `terraform init`, `terraform plan`, and `terraform apply` to provision and manage resources in Google Cloud Platform (GCP).

## Prerequisites

To use this pipeline, ensure you have the following:

- **Google Cloud Platform** (GCP) account with a project and the necessary permissions.
- **Terraform** installed locally (optional for local testing).
- **Cloud Build** API enabled for GCP.
- **Google Cloud SDK** installed and authenticated if using CLI for testing.
- **GitHub** repository where the code is stored.
- An active **Google Cloud Billing account** for provisioning infrastructure.

## Repository Setup

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/terraform-infrastructure-pipeline.git
   cd terraform-infrastructure-pipeline
