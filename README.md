<div align="center">

<!-- ================================================================= -->
<!-- 1. DYNAMIC ANIMATED HEADERS (100% GITHUB PROXY COMPATIBLE)        -->
<!-- ================================================================= -->

<a href="https://github.com/swachhasaha">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=36&duration=3000&pause=1000&color=38BDF8&center=true&vCenter=true&width=850&height=70&lines=Swachha+Prodip+Saha;Senior+Cloud+%26+DevOps+Engineer;Enterprise+Platform+Architect" alt="Swachha Prodip Saha" />
</a>

<br/>

<a href="https://github.com/swachhasaha">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&duration=2500&pause=800&color=0EA5E9&center=true&vCenter=true&width=850&height=40&lines=Azure+Platform+%7C+AWS+%7C+Kubernetes+(AKS%2FEKS);Terraform+IaC+%7C+GitOps+(Argo+CD)+%7C+CI%2FCD;Zero-Trust+Security+%7C+Shift-Left+DevSecOps" alt="Tech Stack Typing" />
</a>

<br/>

<!-- ================================================================= -->
<!-- 2. PROFILE METRIC BADGES                                          -->
<!-- ================================================================= -->

<p align="center">
  <a href="https://www.linkedin.com/in/swachha-prodip-saha-7a6645190/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://github.com/swachhasaha">
    <img src="https://img.shields.io/badge/GitHub-Profile-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <img src="https://img.shields.io/badge/Experience-5%2B%20Years-0284C7?style=for-the-badge" alt="Experience" />
  <img src="https://img.shields.io/badge/Cloud-Azure%20%7C%20AWS-F59E0B?style=for-the-badge" alt="Cloud" />
  <img src="https://img.shields.io/badge/Orchestration-Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubernetes" />
  <img src="https://img.shields.io/badge/Security-DevSecOps-10B981?style=for-the-badge" alt="DevSecOps" />
</p>

</div>

---

### 👨‍💻 Executive Summary

```yaml
engineer:
  name: Swachha Prodip Saha
  role: Senior Cloud & DevOps Engineer
  experience: 5+ Years
  core_stack:
    - Microsoft Azure & AWS
    - Kubernetes (AKS / EKS)
    - Terraform (IaC Modular Architecture)
    - GitOps (Argo CD & Helm)
    - DevSecOps & Shift-Left Gating
  status: Automating, Scaling, and Fortifying Cloud-Native Platforms
```

I am an architecture-first **Senior Cloud & DevOps Engineer with 5+ years of production experience** delivering high-availability cloud platforms, zero-downtime deployment pipelines, declarative infrastructure, and automated security controls. 

My work bridges enterprise operations and developer experience: transforming manual, error-prone workflows into repeatable Infrastructure as Code (IaC), GitOps-managed Kubernetes clusters, and hardened DevSecOps pipelines.

---

### 🛠️ Core Technical Arsenal

<div align="center">

#### Cloud Platforms & Infrastructure as Code
<p align="center">
  <img src="https://skillicons.dev/icons?i=azure,aws,terraform,ansible&perline=4" alt="Cloud and IaC" />
</p>

#### Containers, Orchestration & Service Mesh
<p align="center">
  <img src="https://skillicons.dev/icons?i=kubernetes,docker&perline=2" alt="Containers" />
</p>

#### CI/CD, GitOps & Automation
<p align="center">
  <img src="https://skillicons.dev/icons?i=githubactions,jenkins,argocd,git&perline=4" alt="CI/CD and GitOps" />
</p>

#### Security, Operating Systems & Scripting
<p align="center">
  <img src="https://skillicons.dev/icons?i=linux,ubuntu,redhat,bash,python,powershell&perline=6" alt="OS and Scripting" />
</p>

#### Monitoring, Telemetry & Observability
<p align="center">
  <img src="https://skillicons.dev/icons?i=prometheus,grafana,vscode&perline=3" alt="Monitoring and Tools" />
</p>

</div>

---

### 🏛️ Engineering Architecture & Capabilities

| Domain | Core Focus Areas | Production Practices & Technologies |
| :--- | :--- | :--- |
| **Cloud Infrastructure** | High Availability & Network Security | Azure Hub-and-Spoke Topology, Azure Virtual WAN, AWS Multi-AZ VPCs, Route53, Transit Gateways, Direct Connect/ExpressRoute. |
| **Infrastructure as Code** | Scalable, Modular Automation | Terraform Remote State Locking (Azure Blob / S3 with DynamoDB), Terragrunt, Dynamic Blocks, Drift Detection, Sentinel Policies. |
| **Container Platforms** | Cluster Administration & Scaling | AKS & EKS cluster deployments, Horizontal Pod Autoscaling (HPA), Cluster Autoscaler, Ingress-NGINX, cert-manager, Cilium CNI. |
| **GitOps & Delivery** | Declarative Continuous Delivery | Argo CD ApplicationSets, Helm 3 packaging, automated rollbacks, Blue-Green deployments, Canary rollouts via Flagger. |
| **Shift-Left DevSecOps** | Vulnerability Gating & Compliance | Static Analysis (SonarQube), Container CVE Scanning (Trivy, Aqua), IaC Linting & Policies (tfsec, Checkov), HashiCorp Vault. |
| **Observability & SRE** | Telemetry, Metrics & SLI/SLO | Prometheus operator, Grafana dashboards, Azure Monitor, Log Analytics Workspaces, Distributed Tracing, Alertmanager. |
| **Database DevOps** | Declarative Schema Migrations | Azure SQL DACPAC automated deployment pipelines, Liquibase, Flyway, automated stateful backups and point-in-time recovery. |

---

### 🔄 End-to-End Enterprise DevSecOps Pipeline

```mermaid
flowchart LR
    subgraph SCM["1. Source Control"]
        A[Developer Commit] -->|Pull Request| B[GitHub / Azure Repos]
    end

    subgraph CI["2. CI & Security Gates"]
        B --> C[CI Pipeline Triggered]
        C --> D[SAST: SonarQube]
        C --> E[IaC Lint: tfsec / Checkov]
        C --> F[Docker Build & Trivy Scan]
        D & E & F --> G{Quality Gate Pass?}
        G -- No --> H[Fail PR & Alert Dev]
        G -- Yes --> I[Push to ACR / ECR]
    end

    subgraph CD["3. GitOps & Continuous Delivery"]
        I --> J[Update Manifest Repo]
        J --> K[Argo CD Auto-Sync]
        K --> L[Blue/Green Deployment]
    end

    subgraph K8S["4. Production Runtime (AKS/EKS)"]
        L --> M[Pods & Ingress Health Checks]
        M --> N[Prometheus / Grafana Alerting]
        N --> O[Telemetry to Log Analytics]
    end

    style SCM fill:#0F172A,stroke:#38BDF8,stroke-width:2px,color:#fff
    style CI fill:#1E293B,stroke:#0284C7,stroke-width:2px,color:#fff
    style CD fill:#0F172A,stroke:#10B981,stroke-width:2px,color:#fff
    style K8S fill:#1E293B,stroke:#F59E0B,stroke-width:2px,color:#fff
```

---

### 📦 Production Architecture Highlights

<details>
<summary><b>1. Enterprise Multi-Tier Azure Landing Zone (Terraform)</b></summary>
<br/>

- **Hub-and-Spoke Topology:** Centralized firewall inspection, VPN gateways, and private endpoints preventing public exposure.
- **State Architecture:** Fully secured remote backends using encrypted Azure Blob Storage with lease state locking.
- **Resource Tagging & Cost Controls:** Automated tags enforced via Azure Policy for department billing, environment tiers, and lifecycle governance.
- **Secrets Management:** Integrated Azure Key Vault with Workload Identity and RBAC-controlled secret rotation.

</details>

<details>
<summary><b>2. Production-Grade Kubernetes Orchestration (AKS & EKS)</b></summary>
<br/>

- **Compute & Node Pools:** Dedicated system and user node pools utilizing spot instances for elastic batch processing and on-demand nodes for critical APIs.
- **Resilience Engineering:** Strict resource requests/limits, Pod Disruption Budgets (PDBs), liveness/readiness probes, and topology spread constraints.
- **Network & Ingress:** Calico / Azure CNI with Network Policies, NGINX Ingress Controller, TLS termination via Let's Encrypt / Cert-Manager.
- **Observability:** Prometheus Operator stack exporting cluster metrics to unified Grafana dashboards with slack-alert routing.

</details>

<details>
<summary><b>3. GitOps Delivery Engine (Argo CD & Helm)</b></summary>
<br/>

- **Single Source of Truth:** All infrastructure configuration and Kubernetes deployment manifests tracked declaratively in Git.
- **Drift Detection:** Automated reconciliation loops running every 3 minutes to auto-heal cluster drift back to Git state.
- **Zero-Downtime Rollouts:** Integrated Argo Rollouts for canary deployments with automated rollback on increased HTTP 5xx error spikes.

</details>

<details>
<summary><b>4. Shift-Left DevSecOps & Automated Security Gates</b></summary>
<br/>

- **Static Application Security Testing (SAST):** SonarQube quality gates embedded in pull request verification pipelines.
- **Container Vulnerability Management:** Trivy and Aqua Security scanning base layers and runtime packages during CI build stages.
- **Infrastructure Security:** Checkov and tfsec scans stopping hardcoded keys, overly permissive security groups, and unencrypted volumes prior to pull request merge.

</details>

---

### 💻 Production Shell & Automation Snippet

```bash
#!/usr/bin/env bash
# ==============================================================================
# Script: cluster-health-audit.sh
# Purpose: Pre-deployment health check for production AKS/EKS clusters
# ==============================================================================

set -euo pipefail

NAMESPACE="${1:-default}"
THRESHOLD_RESTARTS=5

echo "======================================================================"
echo " Starting Cluster Node and Pod Health Audit: [Namespace: ${NAMESPACE}]"
echo "======================================================================"

echo -e "\n[*] Checking Node Readiness Status..."
kubectl get nodes --no-headers | awk '{
    if ($2 != "Ready") {
        print "[-] UNHEALTHY NODE: " $1 " is in status " $2;
        exit 1;
    } else {
        print "[+] Node " $1 " is Ready.";
    }
}'

echo -e "\n[*] Auditing High Pod Restart Counts (Threshold: > ${THRESHOLD_RESTARTS})..."
UNSTABLE_PODS=$(kubectl get pods -n "${NAMESPACE}" --no-headers | awk -v limit="${THRESHOLD_RESTARTS}" '$4 > limit {print $1, "Restarts: " $4}')

if [[ -n "${UNSTABLE_PODS}" ]]; then
    echo "[-] WARNING: Unstable pods detected in namespace [${NAMESPACE}]:"
    echo "${UNSTABLE_PODS}"
else
    echo "[+] All pods within normal restart thresholds."
fi

echo -e "\n[*] Validating Cluster Ingress Controller Status..."
kubectl get svc -n ingress-nginx ingress-nginx-controller --no-headers | awk '{
    if ($4 == "<pending>" || $4 == "<none>") {
        print "[-] Ingress External IP pending!";
    } else {
        print "[+] Ingress Controller running on Public IP: " $4;
    }
}'

echo -e "\n======================================================================"
echo " Cluster Health Audit Finished Successfully."
echo "======================================================================"
```

---

### 📊 GitHub Activity & Metrics

<div align="center">

<table border="0">
  <tr>
    <td align="center" width="50%">
      <img src="https://github-readme-stats.vercel.app/api?username=swachhasaha&show_icons=true&include_all_commits=true&count_private=true&theme=tokyonight&hide_border=true&rank_icon=github" alt="GitHub Global Stats" />
    </td>
    <td align="center" width="50%">
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=swachhasaha&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top Languages Stats" />
    </td>
  </tr>
</table>

<br/>

<img width="98%" src="https://github-readme-activity-graph.vercel.app/graph?username=swachhasaha&theme=tokyo-night&hide_border=true&area=true" alt="Contribution Graph" />

</div>

---

### 🌟 Featured Repositories

<div align="center">

<table border="0">
  <tr>
    <td width="50%" align="center">
      <a href="https://github.com/swachhasaha/devops_workspace">
        <img width="100%" src="https://github-readme-stats.vercel.app/api/pin/?username=swachhasaha&repo=devops_workspace&theme=tokyonight&hide_border=true" alt="DevOps Workspace" />
      </a>
    </td>
    <td width="50%" align="center">
      <a href="https://github.com/swachhasaha/aws-devops-zero-to-hero">
        <img width="100%" src="https://github-readme-stats.vercel.app/api/pin/?username=swachhasaha&repo=aws-devops-zero-to-hero&theme=tokyonight&hide_border=true" alt="AWS DevOps Project" />
      </a>
    </td>
  </tr>
</table>

<p align="center">
  <a href="https://github.com/swachhasaha?tab=repositories">
    <img src="https://img.shields.io/badge/View_All_Repositories-2563EB?style=for-the-badge&logo=github&logoColor=white" alt="All Repos" />
  </a>
</p>

</div>

---

### 🎯 Engineering Horizons

- 🌐 **Cloud Landing Zones:** Advanced Azure CAF (Cloud Adoption Framework) modular blueprints using Bicep & Terraform.
- ⚙️ **Platform Engineering:** Standardizing internal developer platforms (IDP) with Backstage and Kubernetes operators.
- 🛡️ **Zero-Trust Network Mesh:** Implementing Istio mTLS authentication and Open Policy Agent (OPA/Gatekeeper) governance.
- 🤖 **MLOps & AI Infrastructure:** Building GPU-accelerated Kubernetes nodes and scalable inference pipelines.

---

### 🤝 Get in Touch & Collaborate

I am always interested in discussing large-scale cloud transformations, Kubernetes operations, and modern DevOps engineering.

<div align="center">

<a href="https://www.linkedin.com/in/swachha-prodip-saha-7a6645190/">
  <img src="https://img.shields.io/badge/LinkedIn-Swachha%20Prodip%20Saha-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="Connect on LinkedIn" />
</a>
<a href="https://github.com/swachhasaha">
  <img src="https://img.shields.io/badge/GitHub-Follow%20%40swachhasaha-181717?style=for-the-badge&logo=github&logoColor=white" alt="Follow GitHub" />
</a>

<br/><br/>

<sub>Designed with high precision • Automation • Resilience • Zero-Downtime Architecture</sub>

</div>