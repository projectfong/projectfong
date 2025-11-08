# Project Fong

Welcome - I’m Fong.  

For years I worked behind the scenes as the sole IT department, building and securing infrastructure for regulated environments.  
Now, **Project Fong** is where I bring that discipline into the open - showcasing selected work in AI systems, compliance, and infrastructure.

---

## 🔹 About This Space
- GitHub here is used **only for demos and showcases**.  
- Most repositories are **stripped-down** or **partial releases**, while select projects may include **full working versions**.  
- Full projects and production implementations are maintained in a private environment.

> ⚠️ **Disclaimer**  
> All repositories in this GitHub are **demo or showcase projects only**.  
> Full production implementations are maintained privately.

---
## 🔹 Governance and Framework

All repositories and documentation published here operate under the [Project Fong AI Governance Framework](https://github.com/projectfong/projectfong-ai-governance/blob/5941f213d9f44939dad189f0afc20d545dc343fd/docs/AI_GOVERNANCE_FRAMEWORK_PUBLIC.md) - a set of internal policies and engineering controls designed to ensure reproducibility, auditability, and responsible use of AI systems.

The public materials reflect selected portions of that framework for demonstration purposes only. Full operational enforcement, validation logic, and compliance automation remain private.

---

## 🔹 Focus Areas
- **AI Systems Architecture**: orchestration, embeddings, retrieval, multi-agent control  
- **Compliance & Security**: designed for regulated and security-sensitive environments, implementing controls consistent with NIST and federal cybersecurity best practices, secure design and validation utilities  
- **Infrastructure & Automation**: hybrid networks, firewalls, virtualization, Terraform/Ansible, Docker orchestration  
- **Full-Stack Prototyping**: FastAPI, React/TypeScript, containerized deployments, RESTful and async service design  

---

## 🔹 Featured Projects (Showcases & Tools)
- **[cfo-aistack-demo](https://github.com/projectfong/cfo-aistack-demo)** → stripped-down modular AI stack (architecture blueprint; full implementation private, README-only)  
- **[cfo-router-demo](https://github.com/projectfong/cfo-router-demo)** → demo router that acts as the *brain* between users and local AI systems - handles routing, model selection, and policy-based decisions (public-safe echo version)
- **[cfo-vessel-demo](https://github.com/projectfong/cfo-vessel-demo)** → demo LLM engine (Vessel) - exposes a safe inference API with canned responses; full runtime and GPU logic private
- **[cfo-flask-rag-demo](https://github.com/projectfong/cfo-flask-rag-demo)** → demo Flask RAG-style service that demonstrates a controlled retrieval pipeline and safe-by-default API behavior; used for governance and audit reproducibility testing
- **[cfo-embed-demo](https://github.com/projectfong/cfo-embed-demo)** → demo embedding encoder, vectorizer
- **[cfo-ai-security-demo](https://github.com/projectfong/cfo-ai-security-demo)**  → demo offline AI security workflow demonstration that simulates firewall log ingestion, summarization, and embedding via cfo-aistack (cfo-vessel + cfo-embed) - produces deterministic JSON evidence for audit and validation
- **[cfo-chatbotui-demo](https://github.com/projectfong/cfo-chatbotui-demo)** → finished demo chatbot (React/TypeScript + FastAPI)
- **[vectorforge](https://github.com/projectfong/vectorforge)** → modular vector database toolkit; focuses on embedding analysis, RAG testing, and vector optimization pipelines  
- **[validns](https://github.com/projectfong/validns)** → domain/DNS validation utility built for compliance and network integrity checks  
- **[validns-lite](https://github.com/projectfong/validns-lite)** → minimal Python reimplementation designed for scripting and automation use-cases

---

## 🔹 Personal and Private Gitea Screenshot

Screenshot from local private Gitea repo (sensitive details redacted):

* **Gitea Starred Repositories**

  ![Gitea](docs/gitea-local.png)

>Identifiers redacted; screenshot included to illustrate internal repository organization and version-control discipline.

---

## Lab Environment

All AI runtime and orchestration projects are developed and validated on self-hosted hardware.

| Role | Hardware | GPUs | Purpose |
|------|-----------|------|----------|
| **Compute Node A** | Intel i5-9400F, 32 GiB RAM, SSD, NVMe | 2 × RTX 3070 (8 GiB) | Docker, codeproject.ai / embed server |
| **Compute Node B** | AMD Ryzen 7 3700X, 32 GiB RAM, SSD, NVMe | 2 × RTX 3060 (12 GiB) | Docker, Primary inference / model-serving node | 
| **Virtualization Host** | Dell PowerEdge R730, 2 × Xeon E5-2690 v4, 384 GiB RAM, Oracle F320 NVMe, Dual 1100w PSU | None | Proxmox VE 9.0.6 – VM orchestration, CI/CD, log aggregation |
| **Storage / Network** | SAS RAID (≈ 22 TB usable), OPNsense | None | VM disks, ZFS pools, datasets, and segmented networking |
| **Backup** | QNAP NAS – 9 TB NFS (Ironwolf + dual RED SA500 mirror cache) | None | Proxmox Backup Server for dedicated VM backup |

*All systems are personally owned and maintained for research and R&D use.  
No customer or sensitive data is processed.*

---

## 🔹 Keywords / Related Search

* LLM inference engine, local AI infrastructure  
* RAG pipelines, retrieval-augmented generation, vector retrieval APIs  
* embedding management, vector optimization, multi-agent coordination  
* GPU scheduling, llama.cpp, GGUF  
* compliance, cybersecurity frameworks, secure design, auditability, policy enforcement, prompt governance, AI Governance  
* containerized orchestration, audit logging, observability hooks
* Qdrant, FAISS, Postgres, vector search, collection analysis
* React, TypeScript, FastAPI frontend, Python, on-prem deployments or hybrid deployments

---

## 🔹 Notes
`projectfong` is about **reinvention** - bringing forward the work that was once hidden behind the scenes.  

What you see here are **representations** of larger projects, shared selectively for visibility.  

This GitHub serves as a technical portfolio illustrating architecture, discipline, and experimentation across AI systems and secure infrastructure.

---

> © 2025 Fong - Licensing varies by repository.  
Each project explicitly defines its applicable license within its own LICENSE.md file.

