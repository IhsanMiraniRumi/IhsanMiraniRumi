# Hi, I'm Ihsan Mirani Rumi

**Platform Engineer · Kubernetes & GitOps · Go & gRPC**<br>
Dhaka, Bangladesh

[Portfolio](https://ihsanmiraniirumi.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/ihsanmiranirumi/) · [Email](mailto:hello@imrumi.dev)

I build and operate cloud-native infrastructure and develop backend services in Go. At **US-Bangla Group**, I work on **CarryBee**, a courier and logistics platform, across Kubernetes, deployment automation, databases, messaging, and production troubleshooting.

My work spans standing up environments, automating repeatable operations, integrating services, and investigating failures. I also contribute transport-service APIs using Go, gRPC, and REST. I'm particularly interested in how backend design and infrastructure decisions affect the reliability of distributed systems.

## Experience

**Platform Engineer I — CarryBee, US-Bangla Group**<br>
Platform Engineering Team · March 2026–Present

- Manage infrastructure automation and GitOps pipelines across CarryBee's microservices, and collaborate on production troubleshooting and cloud migrations.
- Rebuilt CarryBee's staging environment following its transfer to the Platform team, migrating service repositories and setting up deployments, observability, and custom Grafana dashboards.
- Implemented single, bulk, and batch transport-management APIs in Go with gRPC and REST interfaces; shipped to staging and resolved issues found during testing and rollout.

**Junior DevOps Engineer — TechnoNext, US-Bangla Group**<br>
DevOps Team · July 2025–March 2026

- Provisioned infrastructure and CI/CD pipelines for CarryBee, ERP, and an internal lunch-management application across multiple environments.
- Managed automated backups and production deployments, supporting application runtimes and troubleshooting infrastructure issues.

## Selected engineering work

Highlights from my work across these teams:

- **Kubernetes & GitOps:** Built development clusters with kubeadm, containerd, and Cilium, integrating ingress and persistent storage. Automated Argo CD application registration and synchronization from environment-specific Git paths.
- **Configuration automation:** Built Bash and Python tooling to distribute Consul KV configuration, validating YAML for duplicate keys before upload and handling retries and port-forward cleanup.
- **Cloud & ARM migrations:** Contributed migration automation and validation for the production move from GCP to AWS EC2. Prepared ARM container builds and migrated selected Kubernetes workloads; supported PostgreSQL migration using Patroni switchovers, etcd membership changes, and HAProxy routing.
- **Realtime & messaging:** Migrated Centrifugo to Redis-backed coordination in staging and production. Deployed and supported NATS JetStream and EMQX on Kubernetes with persistent storage and application connectivity.
- **Database operations:** Deployed a PostgreSQL warehouse on ARM Linux and troubleshot Airflow object ownership. Implemented incident diagnostics for query activity, lock contention, replication, and host load; maintained PostgreSQL, MongoDB, and etcd backup tooling.
- **Observability & recovery:** Configured Prometheus and Grafana monitoring for applications, databases, and Linux hosts. Built Python health alerts and recovered services affected by filesystem permissions, NFS volumes, Consul storage, and cluster API endpoint changes.
- **Developer infrastructure:** Configured GitLab CI container builds and deployments, prepared self-hosted runners, and resolved Docker permissions, private Go module access, and protobuf tooling issues. Administered self-hosted GitLab and Harbor.

## Tools I work with

| Area | Technologies |
| --- | --- |
| Backend & automation | Go, gRPC, Protocol Buffers, REST APIs, Python, Bash |
| Containers & GitOps | Kubernetes (AWS EKS & self-hosted), Docker, Helm, Argo CD, Cilium |
| CI/CD | GitLab CI/CD, GitHub Actions, self-hosted GitLab runners, Git |
| Cloud, IaC & Linux | AWS, GCP, Terraform, Ubuntu, Rocky Linux |
| Databases | PostgreSQL, Patroni, MongoDB, Redis, Qdrant |
| Messaging & realtime | NATS JetStream, MQTT/EMQX, Centrifugo |
| Observability | Prometheus, Grafana, Loki, Sentry, Promtail, Alloy |
| Networking & configuration | Envoy, NGINX, HAProxy, Consul |
| Storage & registries | Amazon S3, MinIO, NFS, Longhorn, Harbor |
| Data platform operations | Apache Airflow, Apache Superset |

## Labs & exploration

- Built a local **NATS JetStream testbed** with Vagrant and KVM to benchmark replicated publishing and durable-consumer fetching, and investigate batching and storage behavior.
- Integrated **Alloy and Tempo** in development labs to explore tracing pipelines alongside metrics and logs.
- Provisioned a containerized **PostGIS** development environment for spatial-query experimentation.

## Education & learning

**B.Sc. in Computer Science and Engineering**<br>
Shahjalal University of Science and Technology (SUST)<br>
Graduated July 2025 · CGPA: **3.48 / 4.00**

**AWS Academy courses · 2024**

- Cloud Foundations
- Cloud Developing
- Cloud Web Application Builder

<details>
<summary><strong>Research &amp; achievements</strong></summary>

<h3>Undergraduate thesis</h3>

<p><strong>Comparative Analysis of Emotional Expressions: KDEF vs Bengali Dataset</strong><br>
Supervisor: Dr. Sadia Sultana, Associate Professor, CSE, SUST</p>

<ul>
  <li>Developed hybrid action-unit-based and image-based emotion recognition systems.</li>
  <li>Trained and compared ResNet-18, ViT-B/16, and EfficientNet-B0 under structured noise conditions.</li>
  <li>Explored differences in emotion recognition across Western and Bengali facial-expression datasets.</li>
</ul>

<h3>Achievements</h3>

<ul>
  <li><strong>SUST CSE Hackathon 2024:</strong> Finalist from 100+ teams with a full-stack e-commerce application integrating AI.</li>
  <li><strong>ICPC Asia Dhaka Regional 2021:</strong> Ranked 267 out of 1,272 teams with SUST_IronClad.</li>
</ul>

</details>

---

Interested in platform engineering, Go services, or distributed systems? [Let's connect](https://www.linkedin.com/in/ihsanmiranirumi/) or reach me at **[hello@imrumi.dev](mailto:hello@imrumi.dev)**.
