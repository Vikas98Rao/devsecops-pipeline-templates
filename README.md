# DevSecOps Pipeline Templates

> Reusable, production-ready CI/CD pipeline templates with security baked in at every stage.
> Supports Azure DevOps YAML and GitHub Actions for Terraform, Docker, and Kubernetes workloads.

---

## Security Gates in Every Pipeline

`
git push -> Lint/Validate -> Secret Scanning -> SAST/SCA -> Cost Gate -> Plan/Approval -> Deploy
`

## Available Templates

| Template | Platform | Use Case |
|---|---|---|
| terraform-devsecops.yml | Azure DevOps | Full IaC pipeline |
| docker-build-scan.yml | GitHub Actions | Container security pipeline |
| kubernetes-gitops.yml | GitHub Actions | ArgoCD + Helm deployment |
| python-sast.yml | GitHub Actions | Python app security pipeline |

## Tools Integrated

- Secret Scanning: GitLeaks, truffleHog
- IaC Security: Checkov, tfsec, Trivy config
- Container Security: Trivy image scan, Snyk
- Code Quality: SonarQube, Semgrep
- Cost Control: Infracost with PR comments
- Dependency Check: OWASP Dependency-Check

---
Senior DevOps Engineer - Vikas Rao