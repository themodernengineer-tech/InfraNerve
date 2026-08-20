<div align="center">

# ⚡ InfraNerve

### **The Systems Behind Intelligence**

**AI Infrastructure • NVIDIA GPUs • CUDA • Networking • Distributed Computing  • AI Operations**

<br>

> *Studying what happens beneath the model — from silicon and GPU memory to distributed clusters and production AI systems.*

<br>

<img src="https://img.shields.io/badge/AI-Infrastructure-76B900?style=for-the-badge" />
<img src="https://img.shields.io/badge/NVIDIA-Learning%20Track-76B900?style=for-the-badge&logo=nvidia&logoColor=white" />
<img src="https://img.shields.io/badge/CUDA-Accelerated%20Computing-76B900?style=for-the-badge&logo=nvidia&logoColor=white" />
<img src="https://img.shields.io/badge/Linux-Systems-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
<img src="https://img.shields.io/badge/Docker-Containers-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/Kubernetes-Orchestration-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" />

<br><br>

<img src="https://img.shields.io/badge/Distributed-Systems-blueviolet?style=flat-square" />
<img src="https://img.shields.io/badge/GPU-Computing-green?style=flat-square" />
<img src="https://img.shields.io/badge/AI-Operations-orange?style=flat-square" />
<img src="https://img.shields.io/badge/Observability-Monitoring-red?style=flat-square" />
<img src="https://img.shields.io/badge/Model-Inference-purple?style=flat-square" />

</div>

---

# 🧠 What is InfraNerve?

<div align="center">

### **Models create intelligence. Infrastructure makes it usable.**

</div>

<table>
<tr>
<td width="33%" valign="top">

### ⚡ Compute

GPUs, CPUs, CUDA, Tensor Cores, memory systems, and accelerated computing.

</td>
<td width="33%" valign="top">

### 🌐 Connect

High-speed networking, RDMA, InfiniBand, NVLink, NVSwitch, and distributed communication.

</td>
<td width="33%" valign="top">

### 🛠️ Operate

Containers, Kubernetes, monitoring, reliability, troubleshooting, and production operations.

</td>
</tr>
</table>

**InfraNerve** is my structured learning repository for understanding the engineering systems beneath modern AI.

Rather than focusing on model theory alone, this repository explores the infrastructure required to **run, scale, connect, monitor, secure, optimize, and operate AI workloads in production**.

The emphasis is on developing a systems-level understanding of:

> **Compute → Memory → Storage → Networking → Clusters → Orchestration → Operations → Deployment**

---

# 🏗️ AI Infrastructure Architecture

Instead of treating infrastructure as a single stack, I view it as several interconnected engineering planes.

```text
┌──────────────────────────────────────────────────────────────────────┐
│                         APPLICATION PLANE                            │
│                                                                      │
│       LLMs • RAG • Computer Vision • GenAI • AI Services            │
└──────────────────────────────┬───────────────────────────────────────┘
                               │
                               ▼
┌──────────────────────────────────────────────────────────────────────┐
│                          SERVING PLANE                               │
│                                                                      │
│      Model Serving • Triton • NIM • Batch • Real-Time Inference     │
└──────────────────────────────┬───────────────────────────────────────┘
                               │
                               ▼
┌──────────────────────────────────────────────────────────────────────┐
│                        ORCHESTRATION PLANE                           │
│                                                                      │
│        Containers • Kubernetes • Scheduling • Autoscaling           │
└──────────────────────────────┬───────────────────────────────────────┘
                               │
                               ▼
┌──────────────────────────────────────────────────────────────────────┐
│                         COMPUTE PLANE                                │
│                                                                      │
│       CPU • GPU • CUDA • Tensor Cores • HBM • GPU Memory            │
└──────────────────────────────┬───────────────────────────────────────┘
                               │
                ┌──────────────┼──────────────┐
                │              │              │
                ▼              ▼              ▼
       ┌──────────────┐ ┌──────────────┐ ┌──────────────┐
       │   STORAGE    │ │  NETWORKING  │ │ DISTRIBUTED  │
       │              │ │              │ │   COMPUTE    │
       │ NVMe         │ │ Ethernet     │ │ NCCL         │
       │ Object       │ │ InfiniBand   │ │ Parallelism  │
       │ Distributed  │ │ RDMA         │ │ Checkpoints  │
       │ GDS          │ │ NVLink       │ │ Sync         │
       └──────┬───────┘ └──────┬───────┘ └──────┬───────┘
              │                │                │
              └────────────────┼────────────────┘
                               ▼
┌──────────────────────────────────────────────────────────────────────┐
│                        OPERATIONS PLANE                              │
│                                                                      │
│ Monitoring • Logging • Security • Reliability • Troubleshooting     │
└──────────────────────────────────────────────────────────────────────┘
```

This architecture is the core mental model behind InfraNerve:

**AI infrastructure is not one technology. It is a system of interdependent layers.**

---

# 🗺️ Learning Map

## **23 Modules • 172 Topics • One Infrastructure Journey**

|  #  | Module                             | Core Question                                              | Status |
| :-: | ---------------------------------- | ---------------------------------------------------------- | :----: |
|  01 | 🏗️ AI Infrastructure Fundamentals | What makes AI infrastructure different?                    |    ⬜   |
|  02 | 🏭 AI Factories                    | How is AI produced at data-center scale?                   |    ⬜   |
|  03 | 🖥️ Computer Architecture          | What happens beneath AI software?                          |    ⬜   |
|  04 | ⚡ CPU vs GPU                       | Why did GPUs become the engine of AI?                      |    ⬜   |
|  05 | 🟢 NVIDIA GPU Architecture         | How are NVIDIA accelerators designed?                      |    ⬜   |
|  06 | 🧩 CUDA Ecosystem                  | How does software access GPU compute?                      |    ⬜   |
|  07 | 💾 Memory Systems                  | How does data reach compute efficiently?                   |    ⬜   |
|  08 | 🗄️ Storage for AI                 | How do we feed massive datasets to AI systems?             |    ⬜   |
|  09 | 🌐 AI Networking                   | How do distributed AI systems communicate?                 |    ⬜   |
|  10 | 🔗 NVIDIA Networking               | How are GPU clusters interconnected?                       |    ⬜   |
|  11 | 🧮 Distributed AI Training         | How does training scale beyond one GPU?                    |    ⬜   |
|  12 | 🖥️ AI Servers                     | What does an AI compute node look like?                    |    ⬜   |
|  13 | 🏢 AI Clusters                     | How do servers become large AI systems?                    |    ⬜   |
|  14 | 📦 Containers & Virtualization     | How are AI workloads packaged and scheduled?               |    ⬜   |
|  15 | 🧰 AI Software Stack               | What software turns hardware into an AI platform?          |    ⬜   |
|  16 | 📡 AI Operations                   | How do we operate AI infrastructure?                       |    ⬜   |
|  17 | 📈 AI Performance                  | Where does AI infrastructure lose performance?             |    ⬜   |
|  18 | 🔐 AI Security                     | How do we secure shared AI infrastructure?                 |    ⬜   |
|  19 | 🏭 AI Data Centers                 | How is AI infrastructure deployed at scale?                |    ⬜   |
|  20 | ☁️ AI Cloud Infrastructure         | How does AI infrastructure extend into cloud environments? |    ⬜   |
|  21 | 🟢 NVIDIA AI Enterprise            | What software operates enterprise NVIDIA AI?               |    ⬜   |
|  22 | 🚀 AI Deployment                   | How do trained models become production services?          |    ⬜   |
|  23 | 🛠️ Troubleshooting & Operations   | How do we diagnose infrastructure when it fails?           |    ⬜   |

> **Legend:** ⬜ Planned · 🟡 Learning · 🧪 Lab in Progress · ✅ Completed

---

# 01 — 🏗️ AI Infrastructure Fundamentals

### Learning Topics

1. What is AI Infrastructure?
2. Why AI Infrastructure is Different from Traditional IT
3. Components of AI Infrastructure
4. AI Compute
5. AI Storage
6. AI Networking
7. AI Software Stack
8. AI Operations

### Systems View

```text
                 AI INFRASTRUCTURE
                        │
        ┌───────────────┼───────────────┐
        │               │               │
        ▼               ▼               ▼
     COMPUTE          STORAGE        NETWORKING
        │               │               │
        └───────────────┼───────────────┘
                        ▼
                  SOFTWARE STACK
                        │
                        ▼
                    OPERATIONS
```

---

# 02 — 🏭 AI Factories

AI factories treat infrastructure as a system for continuously transforming data into intelligence.

### Learning Topics

9. What is an AI Factory?
10. Why AI Factories Exist
11. Components of AI Factory
12. AI Factory Architecture
13. AI Factory Workflow
14. AI Factory vs Traditional Data Center
15. AI Factory Scaling

### Core Flow

```text
DATA
 │
 ▼
COMPUTE
 │
 ▼
TRAINING / INFERENCE
 │
 ▼
MODELS & INTELLIGENCE
 │
 ▼
AI SERVICES
```

---

# 03 — 🖥️ Computer Architecture

To understand GPU infrastructure, I first need to understand the machine itself.

### Learning Topics

16. What is a CPU?
17. CPU Architecture
18. CPU Cores
19. CPU Cache
20. Memory Hierarchy
21. What is a GPU?
22. GPU Architecture
23. CUDA Cores
24. Tensor Cores
25. Streaming Multiprocessors
26. GPU Memory

---

# 04 — ⚡ CPU vs GPU

### Learning Topics

27. CPU vs GPU
28. Parallel Computing
29. SIMD
30. MIMD
31. GPU Acceleration
32. Why GPUs are Better for AI

### Mental Model

```text
CPU
Few Powerful Cores
        │
        ▼
General-Purpose Computing


GPU
Thousands of Parallel Execution Units
        │
        ▼
Massively Parallel Computing
        │
        ▼
Matrix Operations
        │
        ▼
AI Workloads
```

---

# 05 — 🟢 NVIDIA GPU Architecture

This module moves from generic GPU concepts into NVIDIA accelerator architecture.

### Learning Topics

33. NVIDIA GPU Generations
34. CUDA Architecture
35. Hopper Architecture
36. Blackwell Architecture
37. Tensor Core Generations
38. NVENC
39. NVDEC

### Focus

**Compute → Memory → Interconnect → Tensor Processing → AI Performance**

---

# 06 — 🧩 CUDA Ecosystem

CUDA is the software bridge between applications and NVIDIA GPU compute.

### Learning Topics

40. CUDA Overview
41. CUDA Toolkit
42. CUDA Runtime
43. CUDA Driver
44. CUDA Libraries
45. cuBLAS
46. cuDNN
47. TensorRT
48. NCCL

### CUDA Stack

```text
PyTorch / TensorFlow / AI Application
                 │
                 ▼
        CUDA Libraries
   cuDNN • cuBLAS • NCCL • TensorRT
                 │
                 ▼
           CUDA Runtime
                 │
                 ▼
           CUDA Driver
                 │
                 ▼
            NVIDIA GPU
```

---

# 07 — 💾 Memory Systems

Compute performance is limited if data cannot reach compute efficiently.

### Learning Topics

49. RAM
50. VRAM
51. HBM Memory
52. DDR
53. GDDR
54. Memory Bandwidth
55. Shared Memory
56. Unified Memory
57. NUMA

### Focus

**Capacity • Bandwidth • Latency • Locality • Utilization**

---

# 08 — 🗄️ Storage for AI

AI systems can consume massive datasets and checkpoints.

### Learning Topics

58. AI Storage Requirements
59. NVMe
60. SSD
61. HDD
62. Parallel File Systems
63. Object Storage
64. Distributed Storage
65. GPUDirect Storage

### Data Path

```text
DATASET
   │
   ▼
STORAGE
   │
   ▼
FILESYSTEM / OBJECT LAYER
   │
   ▼
CPU MEMORY
   │
   ▼
GPU MEMORY
   │
   ▼
COMPUTE
```

---

# 09 — 🌐 AI Networking

Distributed AI turns networking into part of the compute system.

### Learning Topics

66. Why AI Needs Fast Networking
67. Ethernet
68. InfiniBand
69. RoCE
70. RDMA
71. Network Latency
72. Bandwidth
73. Switches
74. Spine-Leaf Architecture

### Core Question

> What happens when GPUs can compute faster than the network can synchronize them?

---

# 10 — 🔗 NVIDIA Networking

### Learning Topics

75. Spectrum Ethernet
76. Quantum InfiniBand
77. BlueField DPU
78. ConnectX NIC
79. NVLink
80. NVSwitch
81. GPUDirect RDMA

### Interconnect View

```text
GPU
 │
 ├── NVLink
 │
 ▼
GPU
 │
 ▼
NVSwitch
 │
 ▼
NIC / SuperNIC
 │
 ▼
InfiniBand / Ethernet Fabric
 │
 ▼
Remote Compute Node
```

---

# 11 — 🧮 Distributed AI Training

One GPU eventually becomes insufficient.

Then the problem becomes distributed systems engineering.

### Learning Topics

82. Why Distributed Training
83. Data Parallelism
84. Tensor Parallelism
85. Pipeline Parallelism
86. Expert Parallelism
87. Distributed Checkpointing
88. Gradient Synchronization

### Distributed View

```text
        TRAINING WORKLOAD
               │
      ┌────────┼────────┐
      ▼        ▼        ▼
    GPU 0    GPU 1    GPU 2
      │        │        │
      └────────┼────────┘
               ▼
         SYNCHRONIZATION
               │
               ▼
         UPDATED MODEL
```

---

# 12 — 🖥️ AI Servers

### Learning Topics

89. What is an AI Server?
90. DGX Systems
91. HGX Systems
92. MGX Architecture
93. Grace CPU
94. Grace Hopper
95. GB200
96. Rack Architecture

### Scale Perspective

```text
Accelerator
    │
    ▼
AI Server
    │
    ▼
Rack
    │
    ▼
Cluster
```

---

# 13 — 🏢 AI Clusters

### Learning Topics

97. What is an AI Cluster?
98. Cluster Architecture
99. Rack Design
100. Cooling
101. Power Distribution
102. Scaling Clusters
103. High Availability

### Scaling AI

```text
GPU
 ↓
SERVER
 ↓
RACK
 ↓
CLUSTER
 ↓
DATA CENTER
 ↓
AI FACTORY
```

At this scale, AI becomes a **power, cooling, networking, reliability, and scheduling problem** as much as a software problem.

---

# 14 — 📦 Containers & Virtualization

### Learning Topics

104. Virtual Machines
105. Docker
106. Kubernetes
107. GPU Containers
108. NVIDIA Container Toolkit
109. GPU Scheduling
110. MIG

### Workload Path

```text
AI APPLICATION
      │
      ▼
CONTAINER
      │
      ▼
KUBERNETES
      │
      ▼
GPU SCHEDULING
      │
      ▼
NVIDIA GPU
```

---

# 15 — 🧰 AI Software Stack

### Learning Topics

111. Linux Basics
112. NVIDIA Drivers
113. CUDA Installation
114. Python Environment
115. PyTorch
116. TensorFlow
117. Jupyter
118. NVIDIA NGC

### Software Layers

```text
AI APPLICATION
      │
PyTorch / TensorFlow
      │
CUDA Libraries
      │
CUDA Runtime
      │
NVIDIA Driver
      │
Linux
      │
GPU HARDWARE
```

---

# 16 — 📡 AI Operations

Building infrastructure is only half the problem.

The other half is keeping it healthy.

### Learning Topics

119. AI Infrastructure Operations
120. Monitoring GPUs
121. GPU Utilization
122. GPU Health
123. Cluster Monitoring
124. Alerting
125. Logging
126. Troubleshooting

### Operations Loop

```text
OBSERVE
   │
   ▼
DETECT
   │
   ▼
DIAGNOSE
   │
   ▼
RECOVER
   │
   ▼
OPTIMIZE
   │
   └──────────────► OBSERVE
```

---

# 17 — 📈 AI Performance

### Learning Topics

127. GPU Utilization
128. Throughput
129. Latency
130. FLOPS
131. TFLOPS
132. Memory Bottlenecks
133. Communication Bottlenecks
134. Performance Optimization

### Performance Model

```text
              AI PERFORMANCE
                     │
       ┌─────────────┼─────────────┐
       ▼             ▼             ▼
    COMPUTE        MEMORY       NETWORK
       │             │             │
       └─────────────┼─────────────┘
                     ▼
                UTILIZATION
                     │
                     ▼
             COST / PERFORMANCE
```

---

# 18 — 🔐 AI Security

### Learning Topics

135. AI Infrastructure Security
136. Secure Boot
137. Encryption
138. Authentication
139. RBAC
140. Multi-Tenant Security
141. Data Protection

### Security Layers

```text
Hardware
   ↓
Host
   ↓
Container
   ↓
Cluster
   ↓
Network
   ↓
Data
   ↓
Application
```

---

# 19 — 🏭 AI Data Centers

### Learning Topics

142. Modern AI Data Centers
143. Hyperscale AI
144. Enterprise AI
145. Edge AI
146. Hybrid AI
147. Cloud AI

This module explores how infrastructure architecture changes across different deployment environments and scales.

---

# 20 — ☁️ AI Cloud Infrastructure

### Learning Topics

148. NVIDIA DGX Cloud
149. Private AI
150. Public Cloud AI
151. Hybrid Cloud
152. AI-as-a-Service

### Deployment Spectrum

```text
ON-PREMISES
     │
     ▼
PRIVATE AI
     │
     ▼
HYBRID
     │
     ▼
PUBLIC CLOUD
     │
     ▼
AI-AS-A-SERVICE
```

---

# 21 — 🟢 NVIDIA AI Enterprise

This module explores NVIDIA's enterprise software ecosystem for accelerated AI workloads.

### Learning Topics

153. NVIDIA AI Enterprise
154. NVIDIA NIM
155. NVIDIA NeMo
156. NVIDIA RAPIDS
157. NVIDIA Triton Inference Server
158. NVIDIA Base Command

### Enterprise Stack

```text
AI APPLICATIONS
       │
       ├── NIM
       ├── NeMo
       ├── RAPIDS
       └── Triton
       │
       ▼
NVIDIA AI ENTERPRISE
       │
       ▼
ACCELERATED INFRASTRUCTURE
```

---

# 22 — 🚀 AI Deployment

### Learning Topics

159. Model Serving
160. Batch Inference
161. Real-Time Inference
162. Edge Deployment
163. Autoscaling
164. Production AI

### From Model to Service

```text
TRAINED MODEL
      │
      ▼
MODEL SERVER
      │
      ▼
CONTAINER
      │
      ▼
ORCHESTRATION
      │
      ▼
LOAD BALANCING
      │
      ▼
AUTOSCALING
      │
      ▼
OBSERVABILITY
      │
      ▼
PRODUCTION AI
```

---

# 23 — 🛠️ Troubleshooting & Operations

The final module turns infrastructure knowledge into operational reasoning.

### Learning Topics

165. GPU Failures
166. Driver Issues
167. CUDA Errors
168. Memory Issues
169. Network Bottlenecks
170. Storage Bottlenecks
171. Cluster Failures
172. Performance Debugging

### Troubleshooting Framework

```text
                    PROBLEM
                       │
                       ▼
                OBSERVE SYMPTOMS
                       │
                       ▼
              IDENTIFY SYSTEM LAYER
                       │
        ┌──────────────┼──────────────┐
        ▼              ▼              ▼
      GPU            NETWORK        STORAGE
        │              │              │
        ├──── MEMORY ──┼──── OS ──────┤
        │              │              │
        └──────────────┼──────────────┘
                       ▼
                 ISOLATE CAUSE
                       │
                       ▼
                    RESOLVE
                       │
                       ▼
                 VERIFY HEALTH
                       │
                       ▼
                   DOCUMENT
```

The objective is to move from:

> *"Something isn't working."*

to:

> *"Which layer is failing, what evidence supports that conclusion, and how do I isolate the root cause?"*

---

# 🧪 How I Study Each Topic

InfraNerve is not intended to become a collection of copied documentation.

For every major concept, I aim to work through six stages:

```text
01 ── UNDERSTAND
      What is it?

02 ── REASON
      Why does it exist?

03 ── ARCHITECT
      Where does it sit in the system?

04 ── EXPERIMENT
      Can I test it hands-on?

05 ── OPERATE
      How does it behave in production?

06 ── DOCUMENT
      Can I explain it clearly?
```

Each topic may include:

* 📘 Concept notes
* 🏗️ Architecture diagrams
* 💻 Commands and configurations
* 🧪 Hands-on experiments
* 📊 Performance observations
* 🛠️ Troubleshooting exercises
* 🔍 Production considerations
* 📚 References

---

# 🧭 Skills This Repository Is Intended to Develop

<div align="center">

| Infrastructure       | Accelerated Computing | Operations            |
| -------------------- | --------------------- | --------------------- |
| Linux Systems        | NVIDIA GPUs           | Monitoring            |
| Networking           | CUDA                  | Logging               |
| Storage              | Tensor Cores          | Alerting              |
| Kubernetes           | GPU Memory            | Troubleshooting       |
| Containers           | NCCL                  | Performance Analysis  |
| Distributed Systems  | NVLink / NVSwitch     | Reliability           |
| AI Clusters          | RDMA / GPUDirect      | Capacity Awareness    |
| Cloud Infrastructure | TensorRT / Triton     | Production Operations |

</div>

---

# ⚙️ Infrastructure Mindset

InfraNerve is ultimately about developing a different way of looking at AI.

Instead of only asking:

> **How accurate is the model?**

I want to learn to ask:

> How much compute does it require?

> Where is the bottleneck?

> Is the GPU actually being utilized?

> Can the memory subsystem feed it fast enough?

> Can the network keep distributed GPUs synchronized?

> Can the storage layer continuously supply data?

> What happens when a GPU fails?

> How do we monitor the cluster?

> How does the workload scale?

> What does this system cost to operate?

> How do we make it reliable?

Those questions turn **AI knowledge into AI infrastructure engineering**.

---

# 🌐 Portfolio Context

InfraNerve represents the infrastructure and operations layer of my broader AI engineering studies.

```text
                    AI ENGINEERING
                          │
        ┌─────────────────┴─────────────────┐
        │                                   │
        ▼                                   ▼
   MODEL LAYER                      SYSTEMS LAYER
        │                                   │
Machine Learning                     Compute
Deep Learning                        GPU / CUDA
Computer Vision                      Storage
LLMs                                 Networking
Generative AI                        Kubernetes
        │                            Operations
        │                                   │
        └─────────────────┬─────────────────┘
                          ▼
                 PRODUCTION AI SYSTEMS
                          │
                          ▼
                AI PLATFORM ENGINEERING
```

The goal is not to move away from AI.

The goal is to understand **everything required to make AI work at scale**.

---

<div align="center">

# ⚡ InfraNerve

### **Understand the model. Understand the machine. Understand the system.**

*Learning AI Infrastructure & Operations from GPU architecture to production-scale AI platforms.*

<br>

<img src="https://img.shields.io/badge/STATUS-LEARNING%20IN%20PUBLIC-76B900?style=for-the-badge" />
<img src="https://img.shields.io/badge/MODULES-23-blue?style=for-the-badge" />
<img src="https://img.shields.io/badge/TOPICS-172-purple?style=for-the-badge" />

<br><br>

### **Compute → Connect → Accelerate → Operate → Scale**

</div>
