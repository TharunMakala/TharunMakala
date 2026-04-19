<h1 align="center">Tharun Makala</h1>
<p align="center">
  <b>Senior DevOps Engineer</b> · Azure · Kubernetes · GitOps · Infrastructure-as-Code
</p>

<p align="center">
  <a href="mailto:mtarun523@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-mtarun523%40gmail.com-informational?style=flat-square&logo=gmail&logoColor=white"></a>
  <a href="https://github.com/TharunMakala"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-TharunMakala-24292e?style=flat-square&logo=github"></a>
</p>

---

### About

I'm the person product teams quietly rely on between deploys. I build and operate the delivery platform that ships everything else — Azure DevOps pipelines, AKS clusters running Argo CD, Terraform-managed Azure footprints, and a steady layer of PowerShell glue that turns manual toil into self-service.

My bias: strong defaults, small composable modules, and failures that point at the fix instead of the person.

---

### What I do

- **Platform engineering** — self-service pipeline templates, shared Helm charts, and golden paths so product teams stop re-inventing CI/CD every sprint.
- **GitOps on AKS** — Argo CD app-of-apps across dev/staging/prod, progressive delivery, OPA Gatekeeper guardrails, and KEDA for event-driven autoscaling.
- **Infrastructure-as-Code** — reusable Terraform modules for the Azure services I reach for most (AKS, VNet, Key Vault, Storage, ACR), multi-environment stacks with remote state and locking.
- **Day-2 operations** — PowerShell and Python tooling for pipeline health, cost reporting, compliance auditing, and right-sizing workloads.
- **Security & compliance** — network policies, workload identity, Gatekeeper constraint templates, signed images, branch and pipeline policy-as-code.

---

### Tech stack

<table>
  <tr>
    <td><b>Cloud</b></td>
    <td>Azure (AKS, Key Vault, ACR, Storage, Monitor, Log Analytics, Application Gateway, Private Endpoints)</td>
  </tr>
  <tr>
    <td><b>CI / CD</b></td>
    <td>Azure DevOps Pipelines · GitHub Actions · Argo CD · Argo Rollouts</td>
  </tr>
  <tr>
    <td><b>Containers & orchestration</b></td>
    <td>Kubernetes · Helm · Kustomize · Docker · KEDA · Cert-manager · NGINX Ingress</td>
  </tr>
  <tr>
    <td><b>Infrastructure-as-Code</b></td>
    <td>Terraform · Terragrunt · Bicep (read-only)</td>
  </tr>
  <tr>
    <td><b>Policy & security</b></td>
    <td>OPA Gatekeeper · Azure Policy · Workload Identity · Trivy · Checkov · tfsec</td>
  </tr>
  <tr>
    <td><b>Observability</b></td>
    <td>Prometheus · Grafana · Loki · Azure Monitor · Application Insights</td>
  </tr>
  <tr>
    <td><b>Scripting & automation</b></td>
    <td>PowerShell (primary) · Python · Bash · Go (small CLIs)</td>
  </tr>
  <tr>
    <td><b>Source & registries</b></td>
    <td>Azure Repos · GitHub · Azure Container Registry · Artifactory</td>
  </tr>
</table>

---

### Selected work

| Repo | What's in it |
| --- | --- |
| [**azure-devops-utilites**](https://github.com/TharunMakala/azure-devops-utilites) | Pipeline templates (build / deploy / test), security scanning, k6 load tests, PowerShell + Python tooling (pipeline health reports, cost reporting, compliance checker, webhook server), Helm chart for self-hosted agents on AKS, branch & pipeline policies. |
| [**kubernetes-utilities**](https://github.com/TharunMakala/kubernetes-utilities) | AKS base manifests (RBAC, network policies, quotas, PDBs, HPA/VPA, ingress, cert-manager), in-house Helm charts (`microservice-base`, `api-gateway`), Argo CD app-of-apps for dev / staging / prod, OPA Gatekeeper constraints, KEDA scalers for Service Bus / Event Hub, Workload Identity configs. |
| [**terraform-utilities**](https://github.com/TharunMakala/terraform-utilities) | Azure Terraform modules (AKS with Workload Identity, VNet with subnets + NSGs, Key Vault with RBAC, Storage with lifecycle rules, ACR with private endpoint and geo-replication), multi-environment stacks with remote state, plan-summary tooling for PR gates. |

---

### Focus areas

- **Reliability** — error budgets that drive real decisions, not dashboards no one reads.
- **Cost engineering** — right-sizing before scaling out, spot pools for non-prod, tagging discipline that finally makes chargeback work.
- **Developer experience** — if a teammate has to read a wiki to deploy, the platform failed them. Pipelines should explain themselves.
- **Blast-radius control** — environment isolation, progressive rollouts, policy-as-code, and pre-merge plan review as defaults — not add-ons.

---

### How I like to build

- Small, composable modules over sprawling monorepos
- Strong defaults with clear escape hatches
- Pipeline failures should point at the fix, not the person
- Right-size before you scale out
- Document the *why*; the *what* is in the code

---

### Currently exploring

- eBPF-based network observability (Cilium Hubble)
- Signed images end-to-end with Notation + ORAS
- Backstage as an internal developer portal on top of existing Argo CD / ADO flows

---

### Contact

📧 **mtarun523@gmail.com**
🐙 **[github.com/TharunMakala](https://github.com/TharunMakala)**

<sub>Open to conversations about platform engineering, GitOps at scale, and Azure landing zones.</sub>
