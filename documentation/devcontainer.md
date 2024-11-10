# .devcontainer

Used to provide a standardized development environment across machines / contributors.

This Dev Container is built on Ubuntu Jammy and comes pre-configured with various tools and extensions for infrastructure development, particularly focused on Terraform in AWS and Azure environments.

## Installed Software

### Infrastructure as Code Tools

  - Terraform (latest)
  - Terraform Sentinel
  - TFsec
  - Terraform Docs
  - TFLint
  - Terragrunt
  - Terratag
  - Infracost
  - Azure Bicep

### Cloud Provider Tools

  - AWS CLI
  - Azure CLI

### Development Tools

  - GitHub CLI
  - Pre-commit
  - JSON/YAML Processing Tools (jq-likes):
    - jq
    - yq
    - gojq
    - xq
    - jaq

## VS Code Extensions

### Cloud Development
  - AWS Toolkit
  - Azure Resource Groups
  - CloudFormation Linter

### AI Assistance

  - GitHub Copilot
  - GitHub Copilot Chat

### Source Control

  - GitLens
  - GitHub Codespaces

### Development Tools

  - Go Language Support
  - Terraform
  - Shell Format
  - YAML Support
  - GitHub Actions
  - Better Comments
  - Colorful Comments
  - Remote Containers

## Notable VS Code Settings

### Editor Configuration

  - Format on Save: Enabled
  - Tab Size: 2 spaces
  - Font Size: 24px (editor and terminal)
  - Line Length Ruler: 80 characters
  - Insert Mode: Replace

### Git Settings

  - Auto Fetch: Enabled

### AWS Settings

  - Telemetry: Disabled