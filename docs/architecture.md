\# Architecture (v1)



\## Components

\- Traffic Data Service (simulated/CSV input)

\- Web Dashboard (visualization)

\- Nginx (reverse proxy)

\- Kubernetes (orchestration + scaling)

\- Jenkins (CI/CD)

\- Prometheus + Grafana (monitoring)



\## Deployment Flow

Terraform -> AWS Infra

Ansible  -> Server setup

Docker   -> Build images

K8S      -> Deploy services + ingress + HPA

Jenkins  -> Automate build/deploy + rollback

Monitoring -> Metrics + alerts

