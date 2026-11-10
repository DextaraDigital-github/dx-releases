# Dextara Digital CI/CD Engine Binary Distribution

This repository hosts official release binaries of the **Dextara Digital Salesforce CI/CD Engine (`dx-deploy`)**.

## Installation

In your CI/CD runner (e.g. GitHub Actions, GitLab CI, Azure Pipelines), install the latest release via:

```bash
# Linux x86_64 (Standard GitHub Actions Runner)
curl -sSL -o /usr/local/bin/dx-deploy \
  https://github.com/DextaraDigital-github/dx-releases/releases/latest/download/dx-deploy-linux-x64
chmod +x /usr/local/bin/dx-deploy
```

Verify installation:
```bash
dx-deploy --version
dx-deploy --help
```

## Security & Licensing

All binaries are cryptographically signed and require a valid `DEXTARA_LICENSE_KEY` issued by Dextara Digital Private Limited.  
For licensing inquiries or enterprise support, please contact your Dextara Digital account manager.

---
© 2026 Dextara Digital Private Limited. All rights reserved.
