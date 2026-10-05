<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:050505,60:0B1020,100:1A1535&height=230&section=header&text=ROHIT%20MAHAJAN&fontColor=F5F5F5&fontSize=54&fontAlignY=40&desc=DevOps%20Engineer&descColor=A1A1AA&descSize=18&descAlignY=62&animation=fadeIn" alt="Rohit Mahajan, DevOps Engineer" width="100%"/>

<a href="https://github.com/Rohit-1920"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=15&duration=3200&pause=1400&color=7AA2FF&center=true&vCenter=true&width=720&height=30&lines=AWS+Cloud+%E2%80%A2+Kubernetes+%E2%80%A2+GitOps+%E2%80%A2+Infrastructure+Automation;git+push+%E2%86%92+build+%E2%86%92+deploy+%E2%86%92+observe;no+long-lived+credentials.+no+manual+releases.;SYSTEM+STATUS%3A+OPERATIONAL" alt="Typing status line"/></a>

<br/>

<code>PUNE, INDIA</code> &nbsp;·&nbsp; <code>AWS</code> &nbsp;·&nbsp; <code>EKS</code> &nbsp;·&nbsp; <code>GITOPS</code> &nbsp;·&nbsp; <code>IaC</code>

</div>

<br/>

<table align="center" width="100%">
<tr>
<td width="50%" valign="top">

**`SYSTEM STATUS`** &nbsp; `● OPERATIONAL`

<code>CLOUD</code> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;AWS<br/>
<code>ORCHESTRATION</code> &nbsp;EKS · Fargate · ECS<br/>
<code>DELIVERY</code> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;GitHub Actions · ArgoCD<br/>
<code>INFRA</code> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Terraform · Ansible<br/>
<code>OBSERVE</code> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Prometheus · Grafana · ELK<br/>
<code>SECURITY</code> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;IAM · OIDC · IRSA

</td>
<td width="50%" valign="top">

**`WHAT I DO`**

I design, automate, deploy, secure and troubleshoot cloud infrastructure, from the VPC up to the pipeline that ships onto it.

**`WHERE TO START`**

[Projects](#projects) · [Impact](#engineering-impact) · [Field notes](#things-ive-broken-and-fixed) · [Contact](#contact)

</td>
</tr>
</table>

<br/>

---

## Statement

<div align="center">

### Infrastructure should be boring on a Friday evening.

</div>

I build AWS platforms that stay up when traffic spikes, deployments go sideways, and someone fat-fingers a security group. Releases are push-to-deploy, credentials are short-lived or absent, and drift is reverted by the system rather than discovered by a person.

Most of what I know comes from the moment a diagram and reality disagree, and from fixing it.

---

## Engineering Philosophy

<table align="center" width="100%">
<tr>
<td align="center" width="20%"><br/><code>01</code><br/><b>ARCHITECT</b><br/><sub>Multi-AZ, private by default, no single points of failure</sub><br/><br/></td>
<td align="center" width="20%"><br/><code>02</code><br/><b>AUTOMATE</b><br/><sub>If it's done twice, it becomes code</sub><br/><br/></td>
<td align="center" width="20%"><br/><code>03</code><br/><b>SECURE</b><br/><sub>Least privilege, federated identity, audited changes</sub><br/><br/></td>
<td align="center" width="20%"><br/><code>04</code><br/><b>OBSERVE</b><br/><sub>Metrics, logs and audit trails before the incident</sub><br/><br/></td>
<td align="center" width="20%"><br/><code>05</code><br/><b>OPTIMIZE</b><br/><sub>Right-size compute, cache at the edge, share what can be shared</sub><br/><br/></td>
</tr>
</table>

<div align="center">
<sub><code>RELIABILITY</code> · <code>REPRODUCIBILITY</code> · <code>SECURITY</code> · <code>OBSERVABILITY</code> · <code>SCALABILITY</code> · <code>COST EFFICIENCY</code></sub>
</div>

---

## Stack

<table width="100%">
<tr>
<td width="22%" valign="top"><b><code>CLOUD</code></b></td>
<td><code>EC2</code> <code>VPC</code> <code>IAM</code> <code>S3</code> <code>RDS</code> <code>EFS</code> <code>Route 53</code> <code>CloudFront</code> <code>Lambda</code> <code>API Gateway</code> <code>ALB</code> <code>Auto Scaling</code> <code>Service Quotas</code> <code>Bedrock</code></td>
</tr>
<tr>
<td valign="top"><b><code>CONTAINERS</code></b></td>
<td><code>Docker</code> <code>Kubernetes</code> <code>EKS</code> <code>ECS</code> <code>Fargate</code> <code>ECR</code> <code>Helm</code> <code>Ingress</code> <code>HPA</code></td>
</tr>
<tr>
<td valign="top"><b><code>INFRASTRUCTURE</code></b></td>
<td><code>Terraform</code> <code>Ansible</code> <code>AWS CLI</code> <code>eksctl</code> <code>boto3</code></td>
</tr>
<tr>
<td valign="top"><b><code>CI/CD</code></b></td>
<td><code>GitHub Actions</code> <code>Jenkins</code> <code>CircleCI</code></td>
</tr>
<tr>
<td valign="top"><b><code>GITOPS</code></b></td>
<td><code>ArgoCD</code></td>
</tr>
<tr>
<td valign="top"><b><code>OBSERVABILITY</code></b></td>
<td><code>Prometheus</code> <code>Grafana</code> <code>ELK</code> <code>CloudWatch</code> <code>CloudTrail</code></td>
</tr>
<tr>
<td valign="top"><b><code>SECURITY</code></b></td>
<td><code>IAM</code> <code>OIDC</code> <code>IRSA</code> <code>AWS WAF</code> <code>Cloudflare</code> <code>TLS</code> <code>Security Groups</code> <code>Private Subnets</code></td>
</tr>
<tr>
<td valign="top"><b><code>LANGUAGES</code></b></td>
<td><code>Python</code> <code>Bash</code> &nbsp;·&nbsp; <code>Linux</code> <code>Nginx</code> <code>Git</code> <code>Certbot</code></td>
</tr>
</table>

---

## Architecture Map

How my delivery path and platform pieces connect.

```mermaid
flowchart LR
    DEV([Developer]) --> GH[GitHub]
    GH --> CI["GitHub Actions<br/>OIDC, keyless"]
    CI --> BUILD[Docker build]
    BUILD --> ECR[(Amazon ECR)]
    CI --> S3[("Private S3<br/>static build")]
    ECR --> ARGO["ArgoCD<br/>auto-sync / self-heal"]
    ARGO --> EKS[["Amazon EKS<br/>Fargate"]]
    S3 --> CF["CloudFront<br/>OAC"]
    EKS --> ALB[ALB]
    CF --> ALB
    CF --> USER([Users])
    EKS --> OBS["Prometheus<br/>Grafana<br/>CloudWatch"]
```

<table width="100%">
<tr>
<td width="25%" valign="top"><b><code>TERRAFORM</code></b><br/><sub>Declarative AWS infrastructure</sub></td>
<td width="25%" valign="top"><b><code>ARGOCD</code></b><br/><sub>Git as the source of truth for the cluster</sub></td>
<td width="25%" valign="top"><b><code>PROMETHEUS · GRAFANA</code></b><br/><sub>Metrics and dashboards</sub></td>
<td width="25%" valign="top"><b><code>IAM · OIDC · IRSA</code></b><br/><sub>Identity without static keys</sub></td>
</tr>
</table>

### Delivery timeline

<div align="center">

<code>IDEA</code> → <code>CODE</code> → <code>BUILD</code> → <code>SHIP</code> → <code>RUN</code> → <code>OBSERVE</code> → <code>IMPROVE</code>

</div>

```mermaid
flowchart LR
    A[Commit] --> B[GitHub Actions]
    B --> C[Docker build]
    C --> D[ECR]
    D --> E[GitOps repo]
    E --> F[ArgoCD]
    F --> G[EKS]
    G --> H["Prometheus / Grafana / CloudWatch"]
    H -. feedback .-> A
```

---

## Projects

Three case studies. Open each one for the build, the failures, and the fixes.

<br/>

### `CASE 01` &nbsp; Push-to-Deploy on EKS Fargate

> **Objective:** replace manual deployments with a pipeline that builds, ships and verifies on every push.

<code>EKS</code> <code>Fargate</code> <code>ECR</code> <code>ALB Ingress</code> <code>RDS MariaDB</code> <code>VPC</code> <code>NAT Gateway</code> <code>IRSA</code> <code>Docker</code> <code>GitHub Actions</code> <code>Helm</code>

<details>
<summary><b>Open the case study: Containerized Web Application Deployment on Amazon EKS Fargate with GitHub Actions CI/CD</b></summary>

<br/>

```mermaid
flowchart LR
    GH[Push to GitHub] --> GA["GitHub Actions<br/>parallel image builds"]
    GA --> ECR[(ECR)]
    GA --> K["Apply manifests<br/>verify rollout"]
    K --> EKS[["EKS Fargate<br/>multiple replicas"]]
    EKS --> ALB["Multi-AZ ALB<br/>path-based routing"]
    EKS --> RDS[(Private RDS MariaDB)]
    EKS --> NAT[Shared NAT Gateway]
```

<table width="100%">
<tr>
<td width="33%" valign="top">

**`BUILT`**

- Push-to-deploy workflow: parallel image builds, ECR push, manifest apply, rollout verification
- VPC prepared for Fargate with a NAT Gateway and a private pod subnet
- Private RDS MariaDB, security group scoped to the VPC CIDR
- AWS Load Balancer Controller with an IRSA role limited to one service account
- Frontend and API behind one multi-AZ ALB with path-based routing

</td>
<td width="33%" valign="top">

**`BROKE, THEN FIXED`**

- CoreDNS issues
- Fargate pods stuck in `Pending`
- `ImagePullBackOff` from a missing NAT route
- Backend `CrashLoopBackOff` from RDS security group rules
- ALB `502`, traced through target health and logs

</td>
<td width="33%" valign="top">

**`OUTCOME`**

~80% less manual deployment effort

~50% lower networking cost for non-production traffic, via one shared NAT Gateway

</td>
</tr>
</table>

</details>

<br/>

### `CASE 02` &nbsp; Keyless GitOps Delivery with CloudFront

> **Objective:** ship to production with zero stored AWS credentials and a cluster that heals its own drift.

<code>EKS</code> <code>Fargate</code> <code>ECR</code> <code>S3</code> <code>CloudFront</code> <code>ALB</code> <code>ArgoCD</code> <code>GitHub Actions OIDC</code> <code>IRSA</code> <code>CloudTrail</code> <code>Bedrock</code> <code>Python</code>

<details>
<summary><b>Open the case study: Production GitOps Delivery on Amazon EKS Fargate with CloudFront and Keyless CI/CD</b></summary>

<br/>

```mermaid
flowchart LR
    GA[GitHub Actions] -- "OIDC federation: one repo, one branch" --> IAM[AWS IAM role]
    IAM --> ECR[(ECR images)]
    IAM --> S3[("Private S3<br/>static build")]
    ECR --> ARGO["ArgoCD<br/>auto-sync, prune, self-heal"]
    ARGO --> EKS[[EKS Fargate]]
    EKS -- "IRSA, least privilege" --> BR[Amazon Bedrock]
    U([Users]) -- "HTTPS only" --> CF[CloudFront]
    CF -- OAC --> S3
    CF -- "API path" --> ALB[ALB]
    ALB --> EKS
    CT[CloudTrail] -. audit .-> IAM
```

<table width="100%">
<tr>
<td width="33%" valign="top">

**`BUILT`**

- GitHub Actions federates into AWS via OIDC, trust policy restricted to one repository and branch
- Images pushed to ECR; static build synced to private S3
- ArgoCD with auto-sync, prune and self-heal; configuration drift reverts automatically
- IRSA with a least-privilege Bedrock policy for the backend pod
- CloudFront with a private S3 origin (Origin Access Control), ALB as the API origin, HTTPS-only

</td>
<td width="33%" valign="top">

**`BROKE, THEN FIXED`**

- OIDC `AccessDenied`, diagnosed through CloudTrail
- Fargate profile immutability
- `runAsNonRoot` UID errors
- ArgoCD CRD size limits, solved with server-side apply
- A failing admission webhook
- EKS access policy errors

</td>
<td width="33%" valign="top">

**`OUTCOME`**

100% of long-lived AWS credentials eliminated

~85% less manual release effort

~30% lower compute spend via Fargate sizing and edge caching

</td>
</tr>
</table>

</details>

<br/>

### `CASE 03` &nbsp; Docker Compose to Kubernetes

> **Objective:** move a multi-service application off a single EC2 host without breaking the cutover.

<code>EKS</code> <code>eksctl</code> <code>ECR</code> <code>Kubernetes</code> <code>ALB Ingress</code> <code>IRSA</code> <code>HPA</code> <code>NAT Gateway</code> <code>Route 53</code> <code>Certbot</code> <code>Docker</code>

<details>
<summary><b>Open the case study: Microservices Migration from Docker Compose to Kubernetes on Amazon EKS</b></summary>

<br/>

```mermaid
flowchart LR
    EC2["Single EC2 host<br/>Docker Compose"] -. staged cutover .-> R53["Route 53 + Certbot SSL"]
    R53 --> ALB[ALB Ingress]
    ALB --> FE["React / Vite frontend"]
    ALB --> S1[Spring Boot service 1]
    ALB --> S2[Spring Boot service 2]
    ALB --> S3[Spring Boot service 3]
    HPA[HPA] -. scales .-> S1
    HPA -. scales .-> S2
    HPA -. scales .-> S3
    S1 --> NAT["NAT Gateway<br/>stable egress IP"]
    S2 --> NAT
    S3 --> NAT
```

<table width="100%">
<tr>
<td width="50%" valign="top">

**`BUILT`**

- Three Spring Boot microservices and a React/Vite frontend moved to EKS
- Namespace, ConfigMap, Deployment, Service, ALB Ingress and HPA manifests
- Cluster provisioned with `eksctl`; images published to ECR
- Load Balancer Controller installed with IRSA
- Outbound traffic via NAT Gateway for a stable egress IP
- Idempotent bootstrap script that seeds organizations and users

</td>
<td width="50%" valign="top">

**`THE CUTOVER`**

Rolled out in stages from the EC2 host to EKS, with Route 53 for DNS and Certbot for SSL. Configuration defects and hostname mismatches surfaced during the switch and were fixed along the way.

**`OUTCOME`**

~70% less environment setup effort

</td>
</tr>
</table>

</details>

---

## Engineering Impact

<table align="center" width="100%">
<tr>
<td align="center" width="33%"><br/><h1>80%</h1><sub>less manual deployment effort</sub><br/><br/></td>
<td align="center" width="33%"><br/><h1>85%</h1><sub>less manual release effort</sub><br/><br/></td>
<td align="center" width="33%"><br/><h1>100%</h1><sub>long-lived AWS credentials eliminated</sub><br/><br/></td>
</tr>
<tr>
<td align="center"><br/><h1>50%</h1><sub>networking cost reduction<br/>for selected non-production traffic</sub><br/><br/></td>
<td align="center"><br/><h1>30%</h1><sub>compute spend reduction<br/>via sizing and edge caching</sub><br/><br/></td>
<td align="center"><br/><h1>70%</h1><sub>less environment setup effort</sub><br/><br/></td>
</tr>
</table>

<div align="center"><sub>Figures are approximate and come from the case studies above.</sub></div>

---

## Things I've Broken and Fixed

<div align="center"><i>Production doesn't care about your YAML.</i></div>

<br/>

<table width="100%">
<tr>
<th align="left">SYMPTOM</th>
<th align="left">WHERE REALITY DISAGREED</th>
</tr>
<tr><td><code>CoreDNS failing</code></td><td>Cluster DNS on Fargate needed attention before anything could resolve</td></tr>
<tr><td><code>Pods stuck in Pending</code></td><td>Fargate scheduling and profile behavior</td></tr>
<tr><td><code>ImagePullBackOff</code></td><td>The private subnet had no NAT route</td></tr>
<tr><td><code>CrashLoopBackOff</code></td><td>RDS security group rules blocked the backend</td></tr>
<tr><td><code>ALB 502</code></td><td>Found through target health and logs</td></tr>
<tr><td><code>OIDC AccessDenied</code></td><td>Traced in CloudTrail</td></tr>
<tr><td><code>ArgoCD CRD too large</code></td><td>Solved with server-side apply</td></tr>
<tr><td><code>Admission webhook failures</code></td><td>A failing webhook blocked deployments</td></tr>
<tr><td><code>EKS access policy errors</code></td><td>Cluster access had to be granted explicitly</td></tr>
<tr><td><code>Fargate profile immutability</code></td><td>Profiles can't be edited in place, so the approach had to adapt</td></tr>
<tr><td><code>runAsNonRoot UID errors</code></td><td>Container user IDs didn't satisfy the policy</td></tr>
</table>

<br/>

I don't just deploy infrastructure. I debug it when the architecture diagram turns out to be a suggestion.

---

## Security as a Design Constraint

<table width="100%">
<tr>
<td width="33%" valign="top">

**`IDENTITY`**

IAM least privilege<br/>
OIDC federation for CI/CD<br/>
IRSA scoped to one service account<br/>
No long-lived pipeline credentials

</td>
<td width="33%" valign="top">

**`NETWORK`**

Private subnets<br/>
Private databases<br/>
Restricted security groups<br/>
Private S3 behind CloudFront OAC

</td>
<td width="33%" valign="top">

**`EDGE & AUDIT`**

AWS WAF · Cloudflare WAF<br/>
HTTPS only<br/>
CloudTrail for change tracking

</td>
</tr>
</table>

---

## Observability

```mermaid
flowchart LR
    M[METRICS] --> P[Prometheus] --> G[Grafana]
    L[LOGS] --> E["ELK / CloudWatch"]
    A[AUDIT] --> C[CloudTrail]
```

<div align="center"><sub>Metrics tell me something is wrong. Logs tell me where. Audit trails tell me who changed it.</sub></div>

---

## Currently Exploring

<div align="center">

<code>Platform Engineering</code> &nbsp; <code>Kubernetes</code> &nbsp; <code>AWS</code> &nbsp; <code>GitOps</code> &nbsp; <code>Cloud Security</code> &nbsp; <code>Infrastructure as Code</code>

<code>AI / GenAI Infrastructure</code> &nbsp; <code>Amazon Bedrock</code> &nbsp; <code>DevOps Automation</code> &nbsp; <code>Observability</code> &nbsp; <code>Cost Optimization</code> &nbsp; <code>Production Reliability</code>

</div>

---

## GitHub Activity

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Rohit-1920&show_icons=true&hide_title=true&hide_border=true&bg_color=08090A&text_color=A1A1AA&icon_color=7AA2FF&title_color=F5F5F5&rank_icon=github" alt="GitHub stats" height="150"/>
&nbsp;
<img src="https://streak-stats.demolab.com?user=Rohit-1920&hide_border=true&background=08090A&stroke=1F2330&ring=7AA2FF&fire=7AA2FF&currStreakNum=F5F5F5&sideNums=F5F5F5&currStreakLabel=A1A1AA&sideLabels=A1A1AA&dates=71717A" alt="GitHub streak" height="150"/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Rohit-1920&bg_color=08090A&color=A1A1AA&line=7AA2FF&point=F5F5F5&area=true&area_color=7AA2FF&hide_border=true&hide_title=true" alt="Contribution activity graph" width="100%"/>

</div>

---

<br/>

<div align="center">

<sub>· · ·</sub>

<br/><br/>

### *"Do you understand the violence it took to become this gentle?"*

<br/>

<sub>— Nitya Prakash</sub>

<br/><br/>

<sub>· · ·</sub>

</div>

<br/>

---

## Contact

<div align="center">

### Let's build something that survives production.

<br/>

<a href="https://linkedin.com/in/rohit-m-934a66222"><img src="https://img.shields.io/badge/LINKEDIN-rohit--m--934a66222-0D1117?style=for-the-badge&labelColor=0D1117&color=1F2937&logo=linkedin&logoColor=7AA2FF" alt="LinkedIn"/></a>
<a href="https://github.com/Rohit-1920"><img src="https://img.shields.io/badge/GITHUB-Rohit--1920-0D1117?style=for-the-badge&labelColor=0D1117&color=1F2937&logo=github&logoColor=7AA2FF" alt="GitHub"/></a>
<a href="mailto:mahajanrohit759@gmail.com"><img src="https://img.shields.io/badge/EMAIL-mahajanrohit759%40gmail.com-0D1117?style=for-the-badge&labelColor=0D1117&color=1F2937&logo=gmail&logoColor=7AA2FF" alt="Email"/></a>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:050505,60:0B1020,100:1A1535&height=100&section=footer" alt="" width="100%"/>
