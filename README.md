<h1 align="center">Hi, I'm Rumal 👋</h1>

<h3 align="center">
DevOps Engineer • Telecom Infrastructure • Distributed Systems • AI / LLM Engineering
</h3>

<p align="center">
  <a href="https://rumalg.me/">
    <img src="https://img.shields.io/badge/Portfolio-rumalg.me-0A66C2?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio"/>
  </a>
  <a href="https://www.linkedin.com/in/rumal-gunawardana/">
    <img src="https://img.shields.io/badge/LinkedIn-Rumal_Gunawardana-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://github.com/rumalg123">
    <img src="https://img.shields.io/badge/GitHub-rumalg123-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
</p>

---

## 👨‍💻 About Me

I'm a **DevOps Engineer at Omobio** working where **software, infrastructure, distributed systems, and telecom networks** meet.

My day-to-day engineering work includes carrier-grade SMS Firewall platforms, Linux systems, Kubernetes and containers, CI/CD, monitoring, incident recovery, Erlang-based distributed applications, databases, and protocol-level telecom troubleshooting.

I enjoy understanding systems end to end instead of treating them as black boxes.

A production issue might start in a packet capture, move through **M3UA → SCCP → TCAP → MAP**, appear inside a distributed Erlang node, touch Redis or MariaDB, and finally surface as an application or infrastructure problem. Those cross-layer problems are the ones I enjoy solving most.

Lately I've also been going deeper into AI by building and training my own language model from scratch.

```text
Telecom path:  packets → signalling → distributed services → databases → infrastructure → production

AI path:       text → tokenizer → tensors → transformer → CUDA → training → evaluation → inference
```

---

## 🚀 What I'm Working On

### 🧠 RumalGPT

I'm building **RumalGPT**, an educational decoder-only language model from scratch in PyTorch.

The project is my way of learning LLM engineering from first principles instead of only calling high-level model APIs.

I'm working across the full pipeline:

`dataset construction → BPE tokenization → transformer architecture → GPU training → validation → checkpointing → generation → benchmarking`

The current v3 experiments include modern transformer components such as **RoPE, RMSNorm, SwiGLU, causal attention, tied embeddings, deterministic training, resumable checkpoints, dataset integrity verification, and evaluation tooling**.

I'm also experimenting with scaling training beyond the early small models toward much larger parameter counts while learning the practical limits of GPU memory, throughput, context length, data quality, and optimization.

> The goal is not just to make a chatbot. The goal is to understand what is actually happening inside the model.

### 📡 Telecom Engineering Labs

I'm building test environments that let me experiment with telecom signalling outside production systems.

This includes **SMPP, SS7, SIGTRAN, M3UA, SCTP, SCCP, TCAP, MAP, SMSC, STP, ESME, routing, delivery receipts, protocol failures, and fault injection**.

I currently maintain labs implemented in both **Go** and **Erlang/OTP**.

### ☸️ Platform & Reliability Engineering

I continue to work deeply with:

`Linux • RHEL • Kubernetes • Docker • Podman • CI/CD • Bash • monitoring • databases • networking • incident response`

A major area of interest is moving traditional stateful and distributed telecom workloads toward reliable cloud-native deployment models without losing the operational behavior those systems depend on.

---

## 🛠️ Engineering Stack

### Languages

<p>
  <img src="https://img.shields.io/badge/Erlang-OTP-A90533?style=flat-square&logo=erlang&logoColor=white" alt="Erlang"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go"/>
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white" alt="Bash"/>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"/>
</p>

### Infrastructure & DevOps

<p>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux"/>
  <img src="https://img.shields.io/badge/Red_Hat-EE0000?style=flat-square&logo=redhat&logoColor=white" alt="Red Hat"/>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" alt="Kubernetes"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/Podman-892CA0?style=flat-square&logo=podman&logoColor=white" alt="Podman"/>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions"/>
  <img src="https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white" alt="Jenkins"/>
  <img src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white" alt="Nginx"/>
</p>

### Data, Observability & Backend

<p>
  <img src="https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white" alt="MariaDB"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white" alt="Redis"/>
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white" alt="Prometheus"/>
  <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white" alt="Grafana"/>
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" alt="Spring Boot"/>
  <img src="https://img.shields.io/badge/Keycloak-4D4D4D?style=flat-square&logo=keycloak&logoColor=white" alt="Keycloak"/>
</p>

### AI / ML

<p>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch"/>
  <img src="https://img.shields.io/badge/NVIDIA_CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="CUDA"/>
  <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Hugging Face"/>
</p>

### Telecom / Signalling

```text
SMPP
SS7 / SIGTRAN
M3UA / SCTP
SCCP
TCAP
MAP
SMSC / STP / HLR / MSC
SMS Firewall systems
```

---

## 🔬 Featured Projects

| Project | What I'm Building |
| :--- | :--- |
| **[telco-signalling-lab](https://github.com/rumalg123/telco-signalling-lab)** | A Go-based SMS delivery and signalling test environment with ESME, SMPP proxy, SMSC, STP, M3UA/SCTP, SCCP, TCAP, MAP, DLR handling, routing, protocol testing, and fault injection. |
| **[erlang-telco-test-lab](https://github.com/rumalg123/erlang-telco-test-lab)** | A component-based Erlang/OTP telecom core lab for experimenting with network elements and signalling behavior, starting with an SS7/SIGTRAN STP. |
| **[SpringBoot-Microservice](https://github.com/rumalg123/SpringBoot-Microservice)** | A full-stack microservice platform using Spring Boot, Spring Cloud Gateway, Eureka, Keycloak, PostgreSQL, Redis, Next.js, Docker, rate limiting, and idempotency. |
| **[Advanced-File-Filter-Bot](https://github.com/rumalg123/Advanced-File-Filter-Bot)** | A Telegram indexing and search system built around incremental synchronization, metadata indexing, Redis, MongoDB, and flood-wait-safe scheduling. |
| **RumalGPT v3** | My from-scratch PyTorch LLM project covering tokenizer construction, transformer architecture, pretraining, validation, checkpointing, generation, benchmarking, and model-scaling experiments. Currently developed privately while the project evolves. |

---

## 🧩 How I Approach Engineering

I like working across boundaries.

I don't want to know only that a container restarted. I want to know **why** it restarted, what the application was doing before it happened, what dependency failed, what the network looked like, what state was persisted, and whether the recovery path is actually safe.

The same mindset is what pulled me into LLM engineering. Using models is useful, but understanding tokenization, attention, gradients, optimizers, precision, GPU memory, checkpoints, validation loss, and inference behavior is much more interesting to me.

My general approach is:

1. Understand the system before changing it.
2. Reproduce the problem.
3. Measure instead of guessing.
4. Automate repetitive work.
5. Design for failure and recovery.
6. Verify the result with tests, logs, metrics, or protocol traces.
7. Keep learning one layer deeper.

---

## 🌱 Currently Learning Deeper

I'm continuously going deeper into:

**distributed Erlang/OTP • telecom protocol internals • Kubernetes architecture • reliability engineering • distributed systems • transformer internals • LLM training • GPU optimization • RAG and AI systems**

Long term, I'm especially interested in engineering roles that combine **distributed systems, telecom, cloud-native infrastructure, SRE, and AI systems**.

---

## 💬 Ask Me About

`DevOps` `Linux` `Kubernetes` `Docker` `Erlang` `Telecom` `SMS Firewall` `SMPP` `SS7` `SIGTRAN` `M3UA` `SCTP` `Spring Boot` `Redis` `MariaDB` `CI/CD` `Production Troubleshooting` `LLMs`

---

## 🎮 Outside the Terminal

When I'm not debugging systems, reading protocol traces, or staring at LLM training curves, I'm probably watching **anime, K-dramas, TV shows or movies**, playing games, experimenting with new tech, or reading about whatever interesting thing appeared in the tech world that week.

---

## 🤝 Connect

<p>
  <a href="https://rumalg.me/">🌐 Portfolio</a>
  &nbsp;•&nbsp;
  <a href="https://www.linkedin.com/in/rumal-gunawardana/">💼 LinkedIn</a>
  &nbsp;•&nbsp;
  <a href="https://github.com/rumalg123">💻 GitHub</a>
</p>

<p align="center">
  <i>I like building systems, breaking them in controlled environments, understanding why they broke, and making the next version harder to break.</i>
</p>
