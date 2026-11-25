# Hi, I'm Gaurav Anand 👋

### Site Reliability & Platform Engineer · Dublin, CA (Bay Area)

**13+ years in IT infrastructure and production operations, including 6+ years in DevOps, platform engineering and SRE.**

I build and run reliable cloud platforms: self-service infrastructure that lets developers ship quickly and safely, and SLO-based observability that pages people only when users are hurting. I've also led cloud migrations of legacy enterprise workloads from on-prem data centers to AWS, so I know how to modernize systems without breaking what depends on them.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Gaurav%20Anand-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gaurav-anand-92767312a)
![Open to Work](https://img.shields.io/badge/Status-Open%20to%20Work-2ea44f)
![CKA](https://img.shields.io/badge/CKA-certified-326CE5?logo=kubernetes&logoColor=white)
![CKAD](https://img.shields.io/badge/CKAD-certified-326CE5?logo=kubernetes&logoColor=white)
![AWS SAA](https://img.shields.io/badge/AWS%20Solutions%20Architect-Associate-FF9900?logo=amazonaws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-Associate-7B42BC?logo=terraform&logoColor=white)

---

## 📂 Featured projects

### [observability-platform](https://github.com/GauravAnand90/observability-platform) &nbsp; [![ci](https://github.com/GauravAnand90/observability-platform/actions/workflows/ci.yml/badge.svg)](https://github.com/GauravAnand90/observability-platform/actions/workflows/ci.yml) [![e2e](https://github.com/GauravAnand90/observability-platform/actions/workflows/e2e.yml/badge.svg)](https://github.com/GauravAnand90/observability-platform/actions/workflows/e2e.yml)

SLO-driven observability you can run with one command: **multi-window burn-rate alerts** (unit-tested with promtool), **OpenTelemetry** tracing through a Collector with **tail sampling** into **Grafana Tempo**, page/ticket routing with runbooks, and an **end-to-end CI test that breaks the service and checks that the page arrives**.

<a href="https://github.com/GauravAnand90/observability-platform"><img src="https://raw.githubusercontent.com/GauravAnand90/observability-platform/main/docs/images/slo-overview.png" alt="SLO overview dashboard during an injected outage" width="720"></a>

### [terraform-aws-platform](https://github.com/GauravAnand90/terraform-aws-platform) &nbsp; [![terraform-ci](https://github.com/GauravAnand90/terraform-aws-platform/actions/workflows/terraform-ci.yml/badge.svg)](https://github.com/GauravAnand90/terraform-aws-platform/actions/workflows/terraform-ci.yml)

Reusable Terraform modules for a **three-tier VPC, a private EKS cluster and Aurora PostgreSQL**, with separate dev and prod environments. Every PR runs fmt, validate, **tflint, Checkov** and mocked tests, then posts dev and prod plans; merges apply behind a prod approval using **GitHub OIDC** (no stored AWS keys). Design decisions are recorded as ADRs.

---

## 💼 Experience highlights

**Capital Group: Site Reliability Engineer / Platform Engineer (2023 – 2026)**
- Member of the platform engineering team behind a **self-service platform for 100+ developers**: reusable Terraform modules, Helm/ArgoCD deployment standards and Prometheus/Grafana monitoring.
- Led the **migration of legacy enterprise workloads from on-prem to AWS**.
- Operated Kubernetes/OpenShift and **EKS**, with CI/CD on GitHub Actions (OIDC to AWS), Azure DevOps and Jenkins.

**SDG Software India: DevOps / Platform Engineer (2016 – 2023)**
- Built CI/CD with Jenkins and Nexus and infrastructure as code with Terraform and Ansible; supported the move to Docker and Kubernetes.
- Ran production Java application platforms with HA clustering, failover, DR and Prometheus/Grafana monitoring.

---

## 🛠️ Tech stack

**Cloud:** AWS (EKS, ECS, Lambda, RDS Aurora, VPC, IAM) · Azure
**Containers & GitOps:** Kubernetes · OpenShift · Docker · Helm · ArgoCD
**IaC & CI/CD:** Terraform · Ansible · GitHub Actions · Azure DevOps · Jenkins
**Observability:** Prometheus · Alertmanager · Grafana · OpenTelemetry · Tempo · Datadog · Splunk
**SRE practice:** SLOs / SLIs / error budgets · incident response · blameless RCA · capacity planning
**Languages:** Python · Shell · Go (basic)
**Data:** PostgreSQL · MySQL
**Messaging & app platforms:** Kafka · RabbitMQ · IBM MQ · WebLogic · JBoss · Tomcat · MuleSoft

---

## 🧭 How I work

- **Automate the toil.** If I do it twice, it becomes a module, a pipeline or a runbook.
- **Measure what matters.** I alert on SLOs and user impact, not on CPU graphs.
- **Paved roads over gates.** Good defaults make the secure, reliable path the easy one for developers.

## 📈 Currently exploring

Go · Crossplane · Backstage · AI-assisted incident triage
