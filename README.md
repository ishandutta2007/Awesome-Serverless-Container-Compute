# Awesome-Serverless-Container-Compute

## Top Serverless Container Compute Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Containerized Serverless, Scale-to-Zero Runtimes & Self-Hosted Platforms*  

**Last updated: October 2026**



This repository tracks notable **commercial serverless container platforms** and **open-source projects** that run containers without managing servers — scaling to zero when idle and automatically scaling up with demand. These tools bridge the gap between Kubernetes complexity and function-as-a-service simplicity.



**Examples** include AWS Fargate, Google Cloud Run, Azure Container Apps, Fly.io, Railway, Render, DigitalOcean App Platform, Heroku, Serverless Framework, and Koyeb (the category leaders).



**Open-source emphasis**: Serverless container compute is a rapidly maturing open-source domain. **Knative** leads as the Kubernetes-native serverless platform, **OpenFaaS** delivers functions and containers, **KEDA** provides event-driven autoscaling, and **Kourier** offers a lightweight Knative ingress. **Firecracker** and **gVisor** provide secure container isolation. **Coolify**, **Dokploy**, and **Kamal** simplify deployment. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[AWS Fargate](https://aws.amazon.com/fargate/)**  

  **AWS's serverless compute for containers** — run ECS and EKS tasks without managing EC2 instances . **Pay per vCPU and memory per second** . **Best for AWS-native containerized workloads** .



- **[Google Cloud Run](https://cloud.google.com/run)**  

  **Google's fully managed serverless container platform** — scale to zero with request-based billing . **The easiest container deployment on GCP** . **Best for stateless containerized applications** .



- **[Azure Container Apps](https://azure.microsoft.com/en-us/products/container-apps/)**  

  **Microsoft's serverless container service** — built on Kubernetes with KEDA autoscaling and Dapr integration . **Best for Azure-native microservices** .



- **[Fly.io](https://fly.io/)**  

  **Edge-first container platform** — deploy containers close to users with global distribution . **Best for latency-sensitive applications** .



- **[Railway](https://railway.app/)**  

  **Developer-first container deployment** — instant deployments with managed databases . **Best for rapid prototyping** .



- **[Render](https://render.com/)**  

  **Modern Heroku alternative** — containers, cron jobs, and managed databases . **Best for startups** .



- **[DigitalOcean App Platform](https://www.digitalocean.com/products/app-platform)**  

  **DigitalOcean's managed container platform** — simple, predictable pricing . **Best for DigitalOcean ecosystem users** .



- **[Heroku](https://www.heroku.com/)**  

  **The original PaaS** — containerized deployments with add-ons marketplace . **Best for established Heroku workflows** .



- **[Serverless Framework](https://www.serverless.com/)**  

  **Framework for deploying serverless functions and containers** — multi-cloud support . **Best for serverless-first teams** .



- **[Koyeb](https://www.koyeb.com/)**  

  **Serverless platform for containers and functions** — global edge deployment . **Best for modern serverless workloads** .



## Open-Source GitHub Projects



### Kubernetes-Native Serverless



- **[Knative](https://github.com/knative/serving)**  

  **The leading Kubernetes-native serverless platform**, Apache-2.0 licensed with **5,000+ GitHub stars** . **Scale to zero with request-driven autoscaling** . **Knative Serving for containerized workloads** and **Knative Eventing for event-driven architectures** . **The foundation for Google Cloud Run** . **Best for Kubernetes-native serverless containers** .



- **[OpenFaaS](https://github.com/openfaas/faas)**  

  **The most widely adopted open-source FaaS platform**, MIT licensed with **25,000+ GitHub stars** . **Deploy functions and containers as Docker images** . **faasd** provides lightweight single-node deployment without Kubernetes . **The standard for self-hosted serverless** . **Best for functions and containers on Kubernetes** .



- **[KEDA](https://github.com/kedacore/keda)**  

  **Kubernetes Event-driven Autoscaling**, Apache-2.0 licensed with **8,000+ GitHub stars** . **Scale workloads based on events** — queue depth, Kafka lag, Prometheus metrics, and 60+ scalers . **The autoscaling engine behind Azure Container Apps** . **Best for event-driven autoscaling** .



- **[Kourier](https://github.com/knative-extensions/net-kourier)**  

  **Lightweight Knative ingress**, Apache-2.0 licensed . **Envoy-based ingress for Knative Serving** . **Simpler alternative to Istio for Knative** . **Best for lightweight Knative deployments** .



- **[OpenFunction](https://github.com/OpenFunction/OpenFunction)**  

  **Cloud-native FaaS platform**, Apache-2.0 licensed . **Build, deploy, and manage functions on Kubernetes** . **Best for Kubernetes-native functions** .



- **[Fission](https://github.com/fission/fission)**  

  **Kubernetes-native serverless framework**, Apache-2.0 licensed . **100msec cold starts** via warm containers . **Supports NodeJS, Python, Go, and any Linux executable** . **Best for fast cold-start serverless** .



### Container Isolation & Runtimes



- **[Firecracker](https://github.com/firecracker-microvm/firecracker)**  

  **Secure and fast microVM for serverless**, Apache-2.0 licensed with **25,000+ GitHub stars** . **Lightweight VMs with ~125ms boot times** . **The isolation technology behind AWS Lambda and Fargate** . **Best for secure multi-tenant container isolation** .



- **[gVisor](https://github.com/google/gvisor)**  

  **Application kernel for containers**, Apache-2.0 licensed with **16,000+ GitHub stars** . **Sandboxed container runtime** — stronger isolation than standard containers . **The security layer for Google Cloud Run** . **Best for secure container isolation** .



- **[Kata Containers](https://github.com/kata-containers/kata-containers)**  

  **Secure container runtime with VM isolation**, Apache-2.0 licensed with **5,000+ GitHub stars** . **Hardware virtualization for container security** . **Best for secure multi-tenant containers** .



- **[containerd](https://github.com/containerd/containerd)**  

  **The industry-standard container runtime**, Apache-2.0 licensed with **17,000+ GitHub Stars** . **The runtime behind Docker, Kubernetes, and most cloud platforms** . **Best for container runtime foundation** .



### Deployment & PaaS



- **[Coolify](https://github.com/coollabsio/coolify)**  

  **The leading open-source self-hosted PaaS**, Apache-2.0 licensed with **40,000+ GitHub stars** . **Turns any VPS into a Heroku/Vercel alternative** — deploy applications, databases, and services . **Git-based deployments, automatic SSL, and preview environments** . **Best for self-hosted PaaS** .



- **[Dokploy](https://github.com/Dokploy/dokploy)**  

  **Modern open-source PaaS** — "Vercel alternative, but open source" . Apache-2.0 licensed . **Beautiful UI with Git deployments, previews, and automatic SSL** . **Best for modern UX on VPS** .



- **[Kamal](https://github.com/basecamp/kamal)**  

  **Deploy containers anywhere from bare metal to cloud VMs**, MIT licensed with **12,000+ GitHub stars** . **No Kubernetes, no PaaS** — Docker containers over SSH . **Zero-downtime deployments** . **Best for simple container deployments** .



- **[Dokku](https://github.com/dokku/dokku)**  

  **The smallest PaaS implementation** — Docker-powered Heroku alternative in ~100 lines of bash . MIT licensed with **30,000+ GitHub stars** . **Git-push deployments** . **Best for Heroku-like simplicity** .



- **[CapRover](https://github.com/caprover/caprover)**  

  **Easy-to-use app/database deployment platform**, Apache-2.0 licensed . **One-click apps for WordPress, MongoDB, MySQL, and 100+ others** . **Web GUI for management** . **Best for GUI-driven PaaS** .



### Edge & Distributed



- **[KubeEdge](https://github.com/kubeedge/kubeedge)**  

  **Kubernetes-native edge computing framework**, Apache-2.0 licensed with **7,000+ GitHub stars** . **Extends Kubernetes to edge nodes** . **Best for edge container orchestration** .



- **[SuperEdge](https://github.com/superedge/superedge)**  

  **Edge computing framework**, Apache-2.0 licensed . **Kubernetes-native edge management** . **Best for edge deployments** .



- **[OpenYurt](https://github.com/openyurtio/openyurt)**  

  **Extending Kubernetes to edge**, Apache-2.0 licensed with **4,000+ GitHub stars** . **Native Kubernetes edge extension** . **Best for cloud-edge synergy** .



### Additional Strong Open-Source Options



- **Knative Eventing** — Event-driven serverless on Kubernetes .

- **Google Cloud Run (Knative-based)** — Built on Knative .

- **OpenShift Serverless** — Knative on OpenShift .

- **Kyma** — SAP's Kubernetes serverless platform .

- **Nuclio** — High-performance serverless framework .

- **Flogo** — Edge-native serverless .

- **Fn Project** — Oracle's container-native serverless (archived) .

- **OpenWhisk** — Apache serverless platform .

- **Kubeless** — Kubernetes-native serverless (archived) .



**Frameworks for building custom serverless container solutions**: Combine **Knative** for Kubernetes-native serverless with scale-to-zero . Use **OpenFaaS** for functions and containers with the largest community . Deploy **KEDA** for event-driven autoscaling . Choose **Firecracker** or **gVisor** for secure container isolation . Use **Coolify** or **Dokploy** for self-hosted PaaS . Integrate **Kamal** for simple container deployments . Note that true serverless container compute with managed infrastructure, global edge presence, and vendor-supported SLAs (Fargate, Cloud Run, Azure Container Apps, Fly.io) remains primarily commercial territory; open-source stacks provide strong serverless platforms, autoscaling, and container isolation foundations that require integration for complete serverless deployments.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Serverless container platforms execute arbitrary code and handle sensitive data. Self-hosted solutions require proper security hardening, container isolation, and compliance with data privacy regulations.

- **Cold start performance varies** — Knative and OpenFaaS use warm containers; Fission achieves ~100msec cold starts . Firecracker microVMs boot in ~125ms . Benchmark against your requirements .

- **Container isolation is critical for multi-tenancy** — gVisor, Kata Containers, and Firecracker provide stronger isolation than standard containers . Choose based on your security requirements .

- **Scale-to-zero has trade-offs** — cold starts add latency. Configure minimum instances for latency-sensitive workloads .

- The open-source ecosystem provides strong serverless platforms, autoscaling, and container isolation foundations, but **managed infrastructure, global edge presence, and vendor-supported SLAs** remain primarily commercial offerings.



---



**Made for platform engineers, DevOps teams, and organizations seeking serverless container sovereignty.**  

Let's make serverless container compute more open, transparent, and scalable.
