# Landing-Zone-Github-Actions
Landing-Zone-Github-Actions

🏗️ **Project Overview**

This project builds a production-ready Azure Landing Zone using:
✔️ Modular Terraform architecture
✔️ Environment-specific deployments (dev & prod)
✔️ Automated CI/CD using self-hosted GitHub Actions runner
✔️ Secure, scalable, and reusable components


🔧 **Key Features**

🧩 **1. Fully Modular Terraform Design:**
Each major component is packaged as a reusable module:
🔐 Key Vault
☁️ Storage Account
🖥️ Virtual Machines
🌐 VNet + Subnets + NSGs
🧱 Resource Groups
🗄️ SQL Server + SQL Database
🛰️ Bastion Host
📦 Azure Container Registry (ACR)

🌍 **2. Environment-Based Deployment (dev / prod):**
Independent variables:
- Independent backend/state configuration
- Easy promotion from dev → prod

🤖 **3. GitHub Actions (Self-Hosted Runner):**
The CI/CD pipeline automates:
🚀 Terraform Init
🚀 Terraform Validate
🚀 Terraform Plan
🚀 Terraform Apply (with approval gates for prod)
📦 Artifact generation
- A self-hosted runner ensures speed, control, and flexibility.

  🔐 **4. Security Focused Architecture:**
- RBAC & IAM roles
- Azure Key Vault for secrets
- Segmented VNets
- NSG-controlled traffic
- No hard-coded credentials
- GitHub Secrets for secure automation

  ⚙️ **5. One-Click Deployment Workflow:**
- Push code / raise a PR
- GitHub Actions auto-starts
- Terraform validate + plan
- Manual approval step for production
- Azure Landing Zone gets deployed automatically

🧪 **6. Enterprise-Ready Implementation:**

- Multi-environment support
- Scalable & modular
- Cloud-native best practices
- Easy to extend with new modules
- Ideal for teams adopting IaC
  
