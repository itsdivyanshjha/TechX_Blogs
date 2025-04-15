# TechX Blogs

A modern tech blog platform built with Next.js and hosted on AWS. This project serves as both a demonstration of Terraform infrastructure provisioning and a platform for sharing technical content.

## Project Structure

```
.
├── terraform/           # AWS infrastructure as code
├── nextjs-app/         # Next.js blog application
└── README.md           # Project documentation
```

## Features

- Modern, responsive UI
- Light and dark mode support
- Customizable reading experience (font sizes, styles)
- Static site generation for optimal performance
- AWS-hosted with Terraform-managed infrastructure

## Infrastructure

The AWS infrastructure is managed using Terraform and includes:
- S3 bucket for static website hosting
- CloudFront distribution for CDN
- Route 53 for DNS management (optional)
- ACM for SSL certificate

## Getting Started

### Prerequisites

- Node.js 18+ and npm
- Terraform 1.0+
- AWS CLI configured with appropriate credentials

### Local Development

1. Clone the repository
2. Install dependencies:
   ```bash
   cd nextjs-app
   npm install
   ```
3. Run the development server:
   ```bash
   npm run dev
   ```

### Infrastructure Deployment

1. Navigate to the terraform directory:
   ```bash
   cd terraform
   ```
2. Initialize Terraform:
   ```bash
   terraform init
   ```
3. Apply the infrastructure:
   ```bash
   terraform apply
   ```

## Blog Content

The platform includes a detailed blog post about:
- System Provisioning Management Tools
- Terraform and its 5 popular commands for AWS cloud provisioning
- Step-by-step guide with screenshots

## License

MIT