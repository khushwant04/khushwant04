# Khushwant Sanwalot

**AI infrastructure engineer.** I build the systems that make language models usable in production: inference platforms, tenant isolation, control planes, and the reconciliation loops that keep them honest.

Founder of [Hexel Studio](https://hexelstudio.com) · Bengaluru, India

> **Fabric** — a multi-tenant managed inference platform I built and deployed: OpenAI-compatible API, strict control-plane/data-plane split, Postgres row-level security enforced per tenant, GPU reconciliation on Kubernetes, per-request metering.
> **[→ github.com/khushwant04/fabric](https://github.com/khushwant04/fabric)**

---

## Selected work

| Project | What it is |
|---|---|
| **[fabric](https://github.com/khushwant04/fabric)** | Managed inference platform, deployed and serving on two T4 nodes on AKS. Control plane owns accounts, API keys, per-account OIDC providers, and declared deployments; the data plane verifies JWTs locally and proxies to vLLM, so serving survives control-plane downtime. RLS `ENABLE` + `FORCE` on every account table, checked at startup. `Go` `Python` `TypeScript` `PLpgSQL` |
| **[dde](https://github.com/khushwant04/dde)** | Document data extractor. PDFs, images, CSV, and XLSX invoices into schema-valid JSON. The model does visual extraction; Python owns input safety, arithmetic, dates, and the `review_required` decision — so validation stays deterministic and auditable. CI, 11 layout fixtures, `--provider fake` for reproducible runs. `Python 3.12` |
| **[latent-attention](https://github.com/khushwant04/latent-attention)** | Multi-head latent attention implemented from scratch, with a Triton kernel variant and a benchmark comparing the two. |
| **[mixture-of-experts](https://github.com/khushwant04/mixture-of-experts)** | MoE layer in PyTorch: expert networks, gating network, top-k routing. |
| **[pytorch-transformer](https://github.com/khushwant04/pytorch-transformer)** | Transformer built from scratch and trained for EN→IT translation, including the tokenizers and training loop. |
| **[triton](https://github.com/khushwant04/triton)** | Working notes and kernels for GPU programming — CUDA fundamentals through Triton kernel development. |
| **[k8s](https://github.com/khushwant04/k8s)** | Production-shaped single-node Kubernetes via kubeadm: containerd, Calico with NetworkPolicy, MetalLB, hardened NGINX ingress. |

---

## How I think about AI systems

An agent is not a chatbot with tools attached. It is a distributed system with a model inside the control loop — which means the hard problems are mostly the ordinary ones:

- How does state survive a restart?
- What is the blast radius when the model is wrong?
- How do you bound what it is permitted to do?
- How do you know it finished the task, rather than claimed to?

I care more about those than about model capability, because that is where systems actually fail. Fabric is where I test the answers: it exists to make the serving path keep working when the coordinating path does not.

---

## Stack

**AI/ML** — PyTorch, Transformers, vLLM, Triton, RAG, vector search
**Backend** — Python, Go, TypeScript, FastAPI, PostgreSQL, Redis, Kafka
**Infrastructure** — Kubernetes, Docker, Azure, AWS, GCP, Terraform, Prometheus, Grafana
**Frontend** — Next.js, React

---

## Education

**B.E. Computer Science Engineering (AI/ML)** — Visvesvaraya Technological University, 2023–2027

---

## Connect

[Hexel Studio](https://hexelstudio.com) · [LinkedIn](https://www.linkedin.com/in/khushwant-sanwalot/) · [X](https://x.com/ksanwalot04) · [@hexelstudio](https://github.com/hexelstudio) · [khushwantsanwalot2004@outlook.com](mailto:khushwantsanwalot2004@outlook.com)
