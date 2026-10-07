<div align="center">

# 🧭 InfraNerve Roadmap

### `FROM SYSTEMS FUNDAMENTALS TO PRODUCTION AI INFRASTRUCTURE`

A dependency-driven curriculum for learning, building, measuring, troubleshooting, and operating **AI Infrastructure** and **NVIDIA Infrastructure**.

`LEARN → IMPLEMENT → EXPERIMENT → MEASURE → TROUBLESHOOT → OPERATE`

</div>

---

## 🎯 How to Use This Roadmap

Each phase answers six questions:

1. **What should I learn?**
2. **In what order should I learn it?**
3. **Where should I study it?**
4. **How should I split the concepts into documents?**
5. **What should I actually do hands-on?**
6. **What should I be capable of before continuing?**

---

## 🧪 Lab Access Levels

| Symbol | Environment |
|---|---|
| 🟢 | Ordinary Linux machine / VM |
| 🟡 | NVIDIA GPU required |
| 🟠 | Multiple NVIDIA GPUs required |
| 🔵 | Multi-node / RDMA / InfiniBand infrastructure |
| ☁️ | Cloud infrastructure can be used |
| 📖 | Theory / analysis fallback when hardware is unavailable |

A hardware-dependent phase does **not** block the roadmap.

If hardware is unavailable:

`STUDY → ANALYZE → DOCUMENT → RETURN TO PHYSICAL LAB LATER`

Do not claim the physical lab as completed until it has actually been performed.

---

## 📦 Documentation Rule

Do not use:

`ONE CONCEPT = ONE PDF`

and do not use:

`ONE PHASE = ONE HUGE PDF`

Use:

`ONE COHERENT ENGINEERING QUESTION = ONE DOCUMENT`

Example:

```text
RDMA
├── DMA
├── Kernel Bypass
├── Zero Copy
├── Memory Registration
└── RDMA Data Path
        ↓
rdma_fundamentals.pdf

RDMA Programming Model
├── Verbs
├── Queue Pairs
├── Completion Queues
├── Send / Receive
└── Read / Write
        ↓
rdma_verbs_and_queue_architecture.pdf
```

---

# 🗺️ Master Learning Path

```text
AI INFRASTRUCTURE
      ↓
LINUX & SYSTEMS
      ↓
COMPUTER ARCHITECTURE
      ↓
PARALLEL COMPUTING
      ↓
GPU COMPUTING
      ↓
NVIDIA GPU ARCHITECTURE
      ↓
CUDA
      ↓
GPU MEMORY & OPTIMIZATION
      ↓
MEMORY & STORAGE
      ↓
ETHERNET / TCP-IP
      ↓
RDMA / RoCE
      ↓
INFINIBAND
      ↓
NVIDIA NETWORKING
      ↓
GPUDIRECT
      ↓
MULTI-GPU
      ↓
NCCL
      ↓
DISTRIBUTED AI
      ↓
GPU SERVERS
      ↓
DGX / HGX
      ↓
AI CLUSTERS
      ↓
CONTAINERS
      ↓
KUBERNETES
      ↓
GPU KUBERNETES
      ↓
GPU OPERATOR
      ↓
AI SOFTWARE STACK
      ↓
INFERENCE
      ↓
NVIDIA INFERENCE
      ↓
OBSERVABILITY
      ↓
PERFORMANCE
      ↓
SECURITY
      ↓
TROUBLESHOOTING
      ↓
CLOUD
      ↓
NVIDIA AI ENTERPRISE
      ↓
DATA CENTERS
      ↓
AI FACTORIES
      ↓
PRODUCTION OPERATIONS
```

---

# 📍 Progress Tracker

| # | Phase | Status |
|---:|---|:---:|
| 01 | 🏗️ AI Infrastructure Fundamentals | ⬜ |
| 02 | 🐧 Linux & Systems Fundamentals | ⬜ |
| 03 | 🖥️ Computer Architecture | ⬜ |
| 04 | ⚡ Parallel Computing | ⬜ |
| 05 | ⚡ GPU Computing Fundamentals | ⬜ |
| 06 | 🟢 NVIDIA GPU Architecture | ⬜ |
| 07 | 🧩 CUDA Programming | ⬜ |
| 08 | 💾 CUDA Memory & Optimization | ⬜ |
| 09 | 💾 AI Memory Systems | ⬜ |
| 10 | 🗄️ AI Storage | ⬜ |
| 11 | 🌐 Networking Fundamentals | ⬜ |
| 12 | 🔗 RDMA & RoCE | ⬜ |
| 13 | 🌐 InfiniBand | ⬜ |
| 14 | 🟢 NVIDIA Networking | ⬜ |
| 15 | ⚡ GPUDirect | ⬜ |
| 16 | 🔗 Multi-GPU Architecture | ⬜ |
| 17 | 🧮 NCCL & Collective Communication | ⬜ |
| 18 | 🧠 Distributed AI Training | ⬜ |
| 19 | 🖥️ AI Server Architecture | ⬜ |
| 20 | 🟢 NVIDIA DGX / HGX | ⬜ |
| 21 | 🏢 AI Cluster Architecture | ⬜ |
| 22 | 📦 GPU Containers | ⬜ |
| 23 | ☸️ Kubernetes Fundamentals | ⬜ |
| 24 | ⚡ Kubernetes for GPUs | ⬜ |
| 25 | 🟢 NVIDIA GPU Operator | ⬜ |
| 26 | 🧰 NVIDIA AI Software Stack | ⬜ |
| 27 | 🚀 AI Inference Fundamentals | ⬜ |
| 28 | 🟢 NVIDIA Inference Stack | ⬜ |
| 29 | 📡 GPU Observability | ⬜ |
| 30 | 📈 GPU Performance Engineering | ⬜ |
| 31 | 🔐 AI Infrastructure Security | ⬜ |
| 32 | 🛠️ Troubleshooting & Reliability | ⬜ |
| 33 | ☁️ Cloud GPU Infrastructure | ⬜ |
| 34 | 🟢 NVIDIA AI Enterprise & NGC | ⬜ |
| 35 | 🏭 AI Data Centers | ⬜ |
| 36 | 🏭 AI Factories | ⬜ |
| 37 | 🛠️ Production AI Infrastructure Operations | ⬜ |

`⬜ Planned` · `🟡 In Progress` · `✅ Completed`

---

# PART I — SYSTEMS FOUNDATIONS

<details>
<summary><b>Phase 01 — 🏗️ AI Infrastructure Fundamentals</b></summary>

### 🎯 Goal

Understand the complete system required to turn data and models into running AI workloads.

### 🔗 Learning Order

`AI Workload → Compute → Memory → Storage → Network → Server → Cluster → Platform → Operations`

### 📚 Concepts

- AI infrastructure
- traditional IT vs AI infrastructure
- training vs inference
- CPU and GPU compute
- memory
- storage
- networking
- GPU servers
- clusters
- distributed systems
- orchestration
- observability
- operations
- AI factories

### 📖 Study From

**Primary**
- NVIDIA Data Center documentation
- NVIDIA AI Infrastructure material
- NVIDIA AI Enterprise documentation

**Supporting**
- AWS / Azure / Google Cloud AI infrastructure architecture guides
- introductory HPC architecture material

### 📦 Document Splitting

#### `ai_infrastructure_fundamentals.pdf`

Combine:

- what AI infrastructure is
- traditional vs AI infrastructure
- training vs inference
- AI workload lifecycle
- CPU vs accelerator

**Question:** Why does AI require specialized infrastructure?

#### `ai_infrastructure_systems_stack.pdf`

Combine:

- compute
- memory
- storage
- networking
- servers
- clusters
- orchestration

**Question:** What systems cooperate to execute an AI workload?

#### `ai_infrastructure_operations_overview.pdf`

Combine:

- observability
- reliability
- lifecycle
- operations
- AI factory overview

### 🧪 Lab — Trace an AI Workload

**Access:** 🟢 / 📖

**Where:** Any computer.

**Goal:** Trace an AI request through infrastructure.

**Steps**

1. Pick either model training or inference.
2. Draw:

```text
DATA
 ↓
STORAGE
 ↓
CPU / RAM
 ↓
GPU
 ↓
GPU MEMORY
 ↓
NETWORK
 ↓
CLUSTER
 ↓
AI SOFTWARE
 ↓
OUTPUT
```

3. For each layer write:
   - purpose
   - possible bottleneck
   - possible failure
   - monitoring signal

### ❓ Questions

- Why isn't a GPU alone an AI infrastructure platform?
- What happens if GPUs are fast but storage is slow?
- What happens if multi-node GPUs have poor networking?

### 🏭 Production Relevance

Infrastructure engineers diagnose the **whole data path**, not only the GPU.

### 📦 Publish

```text
Docs/Foundations/
Labs/Foundations/ai-workload-path/
```

### ✅ Exit Criteria

- [ ] Explain training vs inference infrastructure.
- [ ] Identify every major infrastructure layer.
- [ ] Explain how one slow subsystem can starve the GPU.

</details>

<details>
<summary><b>Phase 02 — 🐧 Linux & Systems Fundamentals</b></summary>

### 🎯 Goal

Become comfortable inspecting and operating the Linux layer underneath AI infrastructure.

### 🔗 Learning Order

`Filesystem → Processes → Memory → Devices → Kernel → Services → Logs → Networking`

### 📚 Concepts

- filesystem
- users/groups
- permissions
- processes
- threads
- signals
- file descriptors
- system calls
- virtual memory
- `/proc`
- `/sys`
- device files
- kernel modules
- systemd
- logs
- SSH
- basic networking

### 📖 Study From

- Linux Kernel documentation
- Ubuntu or RHEL documentation
- Linux `man` pages
- Linux Foundation material

### 📦 Document Splitting

#### `linux_processes_and_execution.pdf`

Processes + threads + signals + file descriptors + system calls.

#### `linux_memory_and_devices.pdf`

Virtual memory + `/proc` + `/sys` + devices + kernel modules.

#### `linux_server_operations.pdf`

Users + permissions + systemd + logs + SSH + networking.

### 🛠️ Tools

```bash
ps
top
htop
free
vmstat
iostat
lscpu
lsmem
lsblk
lspci
lsmod
dmesg
journalctl
systemctl
ip
ss
```

### 🧪 Lab — Linux Infrastructure Inventory

**Access:** 🟢

**Where:** Linux laptop, VM, WSL2, or server.

**Goal:** Inspect a Linux machine using only the terminal.

**Steps**

```bash
uname -a
lscpu
free -h
lsblk
lspci
ip addr
ip route
ps aux
systemctl --type=service --state=running
journalctl -b --priority=warning
```

Create a table containing:

```text
CPU
RAM
DISKS
PCIe DEVICES
NETWORK INTERFACES
RUNNING SERVICES
KERNEL
```

Then automate the inventory using Bash.

### 🔎 Observe

- physical vs logical CPUs
- total/available memory
- storage devices
- PCIe devices
- network interfaces
- running services

### ❓ Questions

- What is `/proc`?
- What is `/sys`?
- What does a kernel module do?
- Why would an NVIDIA driver involve the Linux kernel?

### 🏭 Production Relevance

Most GPU servers and Kubernetes GPU nodes ultimately require Linux-level diagnosis.

### 📦 Publish

```text
Docs/Foundations/
Code/Linux/system-inventory/
```

### ✅ Exit Criteria

- [ ] Inspect a Linux server from CLI.
- [ ] Find hardware and services.
- [ ] Read relevant logs.
- [ ] Write a simple Bash inventory script.

</details>

<details>
<summary><b>Phase 03 — 🖥️ Computer Architecture</b></summary>

### 🎯 Goal

Understand the hardware topology underneath accelerator servers.

### 🔗 Learning Order

`CPU → Cores → Cache → RAM → NUMA → PCIe → DMA → Devices`

### 📚 Concepts

- CPU
- ISA
- cores
- threads
- registers
- ALU
- SIMD
- cache hierarchy
- RAM
- NUMA
- memory bandwidth
- PCIe
- DMA
- interrupts
- device I/O

### 📖 Study From

- CPU vendor architecture documentation
- Linux hardware documentation
- computer architecture course/textbook material
- PCIe architecture introductions

### 📦 Document Splitting

#### `cpu_architecture_and_execution.pdf`

CPU + ISA + cores + threads + registers + ALU + SIMD.

#### `cpu_memory_hierarchy.pdf`

Cache + RAM + latency + bandwidth + NUMA.

#### `pcie_dma_and_device_io.pdf`

PCIe + DMA + interrupts + device communication.

### 🧪 Lab — Map CPU, NUMA, Memory, PCIe & Devices

**Access:** 🟢  
**Best environment:** Linux GPU server.

**Requirements**

- Linux
- `lscpu`
- `lspci`
- `numactl`
- optional `hwloc`
- optional NVIDIA GPU

#### Step 1 — CPU

```bash
lscpu
```

Record:

- sockets
- cores/socket
- threads/core
- logical CPUs
- NUMA nodes

#### Step 2 — NUMA

```bash
numactl --hardware
numastat
```

Record which CPUs and memory belong to each node.

#### Step 3 — PCIe

```bash
lspci
lspci -t
```

Identify:

- GPUs
- NICs
- NVMe
- PCI bridges

#### Step 4 — Inspect Device

```bash
lspci -vv
```

Inspect link speed and width for an interesting device.

#### Step 5 — NVIDIA Topology

If GPU available:

```bash
nvidia-smi -L
nvidia-smi topo -m
```

#### Step 6 — Build Your Actual Map

```text
CPU SOCKET
   ↓
NUMA NODE
├── LOCAL RAM
└── PCIe ROOT
    ├── GPU
    ├── NIC
    └── NVMe
```

### 🔎 Observe

- Which memory is local to each CPU?
- Where is the GPU attached?
- Where is the NIC attached?
- Is the system single or multi-NUMA?

### ❓ Questions

- Why does NUMA locality matter?
- Why does PCIe topology matter?
- Why could GPU/NIC placement affect distributed training?

### 🏭 Production Relevance

NUMA and PCIe topology can directly affect CPU↔GPU and GPU↔NIC performance.

### 📦 Publish

```text
Labs/Computer-Architecture/system-topology/
├── README.md
└── topology.md
```

### ✅ Exit Criteria

- [ ] Explain NUMA.
- [ ] Read a PCIe tree.
- [ ] Locate GPU/NIC/storage devices.
- [ ] Draw the topology of a real machine.

</details>

<details>
<summary><b>Phase 04 — ⚡ Parallel Computing</b></summary>

### 🎯 Goal

Understand why accelerators and distributed systems can execute workloads faster.

### 🔗 Learning Order

`Sequential → Concurrency → Parallelism → Synchronization → Scaling`

### 📚 Concepts

- concurrency
- parallelism
- processes
- threads
- task parallelism
- data parallelism
- SIMD
- SIMT
- synchronization
- race conditions
- locks
- barriers
- Amdahl's Law
- scaling efficiency

### 📖 Study From

- OpenMP documentation
- NVIDIA accelerated-computing learning material
- HPC parallel-programming resources

### 📦 Document Splitting

#### `parallel_computing_fundamentals.pdf`

Sequential + concurrent + parallel + task/data parallelism.

#### `parallel_synchronization.pdf`

Race conditions + locks + barriers + synchronization.

#### `parallel_scaling_and_performance.pdf`

Amdahl's Law + speedup + throughput + scaling efficiency.

### 🧪 Lab — Sequential vs Parallel Execution

**Access:** 🟢

**Where:** Python/Linux.

1. Create a CPU-heavy task.
2. Run sequentially.
3. Run using Python multiprocessing.
4. Test 1, 2, 4, 8 workers.
5. Record runtime.

### 📊 Measure

```text
Workers | Runtime | Speedup | Efficiency
```

### ❓ Questions

- Did doubling workers halve runtime?
- What overhead appeared?
- What would Amdahl's Law predict?

### 🏭 Production Relevance

Scaling hardware without understanding parallel efficiency wastes expensive compute.

### 📦 Publish

```text
Code/Parallel-Computing/
Benchmarks/Parallel-Computing/
```

### ✅ Exit Criteria

- [ ] Explain concurrency vs parallelism.
- [ ] Measure speedup.
- [ ] Explain why scaling stops being linear.

</details>

---

# PART II — GPU & CUDA

<details>
<summary><b>Phase 05 — ⚡ GPU Computing Fundamentals</b></summary>

### 🎯 Goal

Understand why GPUs are architecturally suited to AI.

### 🔗 Learning Order

`CPU vs GPU → Throughput → Host/Device → SIMT → GPU Workloads`

### 📚 Concepts

- CPU vs GPU
- latency vs throughput
- massive parallelism
- host/device
- kernels
- SIMT
- warps
- GPU memory
- compute-bound vs memory-bound

### 📖 Study From

- NVIDIA CUDA Programming Guide — Introduction
- NVIDIA CUDA Programming Model
- NVIDIA Accelerated Computing learning material

### 📦 Document Splitting

#### `cpu_vs_gpu_computing.pdf`

CPU/GPU architecture + latency/throughput + workload suitability.

#### `gpu_execution_fundamentals.pdf`

Host/device + kernel + SIMT + warp + workload bottlenecks.

### 🧪 Lab — Inspect an NVIDIA GPU

**Access:** 🟡 / 📖 fallback

```bash
nvidia-smi
nvidia-smi -L
nvidia-smi -q
nvidia-smi topo -m
```

Record:

- GPU
- VRAM
- driver
- utilization
- power
- temperature
- processes
- topology

**Fallback:** Study a documented `nvidia-smi -q` sample and label each field.

### 🏭 Production Relevance

`nvidia-smi` is a basic first-line inspection tool for GPU hosts.

### 📦 Publish

```text
Labs/NVIDIA-GPU-CUDA/gpu-inspection/
```

### ✅ Exit Criteria

- [ ] Explain CPU vs GPU.
- [ ] Explain host/device terminology.
- [ ] Inspect GPU state.

</details>

<details>
<summary><b>Phase 06 — 🟢 NVIDIA GPU Architecture</b></summary>

### 🎯 Goal

Understand the compute and memory structure inside NVIDIA GPUs.

### 🔗 Learning Order

`SM → CUDA Cores/Tensor Cores → Warps → Registers/Shared Memory → Cache → HBM`

### 📚 Concepts

- SM
- CUDA cores
- Tensor Cores
- warps
- warp schedulers
- registers
- shared memory
- L1/L2
- HBM/VRAM
- compute capability
- PCIe vs SXM
- MIG overview

### 📖 Study From

- NVIDIA GPU architecture whitepapers
- CUDA Programming Guide
- NVIDIA GPU product architecture documentation

### 📦 Document Splitting

#### `nvidia_gpu_compute_architecture.pdf`

SM + CUDA cores + Tensor Cores + warp execution.

#### `nvidia_gpu_memory_architecture.pdf`

Registers + shared memory + cache + HBM.

#### `nvidia_gpu_platform_architecture.pdf`

Compute capability + PCIe/SXM + MIG overview.

### 🧪 Lab — Map Architecture to a Real GPU

**Access:** 🟡 / 📖

1. Identify GPU:

```bash
nvidia-smi -L
```

2. Determine architecture and compute capability from NVIDIA documentation.
3. Find:
   - SM count
   - memory capacity
   - memory type
   - bandwidth
   - Tensor Core generation
   - interface
4. Build an architecture card.

### 🏭 Production Relevance

Architecture determines capacity, compatibility, performance characteristics, and workload suitability.

### 📦 Publish

```text
Labs/NVIDIA-GPU-CUDA/gpu-architecture-profile/
```

### ✅ Exit Criteria

- [ ] Explain an SM.
- [ ] Explain GPU memory hierarchy.
- [ ] Interpret basic architecture specifications.

</details>

<details>
<summary><b>Phase 07 — 🧩 CUDA Programming Fundamentals</b></summary>

### 🎯 Goal

Write and understand code that executes directly on NVIDIA GPUs.

### 🔗 Learning Order

`Host/Device → Kernel → Thread → Block → Grid → Memory → Synchronization`

### 📚 Concepts

- CUDA platform
- host/device
- kernels
- threads
- blocks
- grids
- indexing
- warps
- allocation
- memory copies
- synchronization
- Runtime API
- errors
- NVCC

### 📖 Study From

- NVIDIA CUDA Programming Guide — Programming GPUs in CUDA
- CUDA Runtime API
- NVCC documentation
- CUDA Samples

### 📦 Document Splitting

#### `cuda_execution_model.pdf`

Kernel + threads + blocks + grids + indexing + warps.

#### `cuda_host_device_programming.pdf`

Allocation + transfers + launches + synchronization + errors.

#### `cuda_build_and_debug_workflow.pdf`

NVCC + compilation + runtime errors + Compute Sanitizer.

### 🧪 Lab — Build Your First CUDA Programs

**Access:** 🟡 / ☁️

**Requirements**

- NVIDIA GPU
- driver
- CUDA Toolkit
- C/C++

Verify:

```bash
nvidia-smi
nvcc --version
```

Build in order:

1. Hello CUDA
2. Vector addition
3. Vector scaling
4. Matrix addition
5. Basic matrix multiplication
6. Reduction

Compile:

```bash
nvcc program.cu -o program
./program
```

Add CUDA error checking.

Run:

```bash
compute-sanitizer ./program
```

### 🔎 Observe

- grid/block dimensions
- thread IDs
- CPU↔GPU transfers
- kernel execution
- synchronization

### 🏭 Production Relevance

CUDA knowledge makes GPU performance and framework behavior less opaque.

### 📦 Publish

```text
Code/CUDA/Fundamentals/
```

### ✅ Exit Criteria

- [ ] Write a kernel.
- [ ] Configure grid/block dimensions.
- [ ] Allocate/copy GPU memory.
- [ ] Compile with NVCC.
- [ ] Detect basic CUDA errors.

</details>

<details>
<summary><b>Phase 08 — 💾 CUDA Memory & GPU Optimization</b></summary>

### 🎯 Goal

Learn why a working CUDA kernel can still perform poorly.

### 📚 Concepts

- global/shared/local/constant memory
- registers
- coalescing
- bank conflicts
- occupancy
- divergence
- streams
- asynchronous execution
- pinned memory
- Unified Memory

### 📖 Study From

- CUDA Programming Guide
- CUDA Best Practices Guide
- Nsight Compute documentation
- Nsight Systems documentation

### 📦 Document Splitting

#### `cuda_memory_model.pdf`

CUDA memory spaces.

#### `cuda_memory_access_optimization.pdf`

Coalescing + bank conflicts + bandwidth.

#### `cuda_execution_optimization.pdf`

Occupancy + divergence + launch behavior.

#### `cuda_streams_and_async_execution.pdf`

Streams + pinned memory + async copies + overlap.

### 🧪 Lab — Profile and Optimize a Kernel

**Access:** 🟡

1. Choose your matrix/vector kernel.
2. Establish baseline runtime.
3. Profile with Nsight Systems.
4. Profile kernel with Nsight Compute.
5. Identify inefficient memory access or execution.
6. Modify one variable.
7. rerun.
8. Compare.

### 📊 Record

```text
Version | Runtime | Bandwidth | Occupancy | Notes
```

### ❓ Questions

- Was it compute-bound or memory-bound?
- Did optimization actually improve runtime?
- What metric proves it?

### 🏭 Production Relevance

Optimization should be measurement-driven, not based on intuition.

### 📦 Publish

```text
Benchmarks/CUDA/optimization/
```

### ✅ Exit Criteria

- [ ] Profile CUDA execution.
- [ ] Identify a bottleneck.
- [ ] Optimize it.
- [ ] Demonstrate improvement quantitatively.

</details>

---

# PART III — MEMORY & STORAGE

<details>
<summary><b>Phase 09 — 💾 AI Memory Systems</b></summary>

### 🎯 Goal

Understand memory from server RAM through GPU memory and model state.

### 📚 Concepts

- RAM
- NUMA
- VRAM/HBM
- capacity
- bandwidth
- PCIe transfer
- pinned memory
- Unified Memory
- oversubscription
- weights
- activations
- gradients
- KV cache
- OOM

### 📖 Study From

- CUDA memory documentation
- NVIDIA GPU architecture documentation
- PyTorch CUDA memory documentation

### 📦 Document Splitting

#### `ai_hardware_memory_architecture.pdf`

RAM + NUMA + HBM + bandwidth + latency.

#### `cpu_gpu_memory_transfer.pdf`

PCIe + pageable/pinned + Unified Memory.

#### `ai_workload_memory_anatomy.pdf`

Weights + activations + gradients + KV cache + OOM.

### 🧪 Lab — Observe AI Memory Growth

**Access:** 🟡

1. Start:

```bash
watch -n 1 nvidia-smi
```

2. Run a small PyTorch GPU workload.
3. Increase batch size.
4. Record GPU memory.
5. Continue until memory growth becomes clear.
6. Do **not** intentionally destabilize shared/production infrastructure.

### 📊 Record

```text
Batch | VRAM | GPU Utilization | Runtime
```

### 🏭 Production Relevance

Many AI failures and scaling limits are memory-capacity problems before compute problems.

### 📦 Publish

```text
Benchmarks/Memory/gpu-memory-scaling/
```

### ✅ Exit Criteria

- [ ] Explain HBM vs RAM.
- [ ] Explain major training/inference memory consumers.
- [ ] Diagnose a basic OOM scenario.

</details>

<details>
<summary><b>Phase 10 — 🗄️ Storage for AI</b></summary>

### 🎯 Goal

Understand how storage feeds datasets and checkpoints to AI compute.

### 📚 Concepts

- HDD/SSD
- SATA/NVMe
- block/file/object
- NFS
- distributed storage
- parallel filesystems
- NVMe-oF
- IOPS
- throughput
- latency
- checkpoints
- dataset pipelines
- GPUDirect Storage overview

### 📖 Study From

- Linux storage documentation
- NVMe documentation
- storage vendor documentation
- NVIDIA GPUDirect Storage documentation

### 📦 Document Splitting

#### `storage_fundamentals_for_ai.pdf`

Media + interfaces + storage models + performance metrics.

#### `distributed_storage_for_ai.pdf`

NFS + distributed/parallel storage + NVMe-oF.

#### `ai_storage_io_pipeline.pdf`

Dataset loading + checkpoints + bottlenecks.

#### `gpudirect_storage_fundamentals.pdf`

Traditional vs direct GPU storage path.

### 🧪 Lab — Storage Benchmark

**Access:** 🟢

**Tool:** `fio`

Test a **safe scratch/test file**, not important data.

Measure:

- sequential read
- sequential write
- random read
- random write

Vary:

- block size
- queue depth

### 📊 Record

```text
Test | Block Size | IOPS | Bandwidth | Latency
```

### 🏭 Production Relevance

Idle GPUs may actually be waiting for storage.

### 📦 Publish

```text
Benchmarks/Memory-Storage/fio/
```

### ✅ Exit Criteria

- [ ] Explain IOPS vs bandwidth vs latency.
- [ ] Run a safe storage benchmark.
- [ ] Recognize storage starvation.

</details>

---

# PART IV — AI NETWORKING

<details>
<summary><b>Phase 11 — 🌐 Networking Fundamentals</b></summary>

### 🎯 Goal

Build the networking foundation required before RDMA and AI fabrics.

### 🔗 Learning Order

`Ethernet → IP → TCP/UDP → Switching/Routing → NIC → Performance`

### 📚 Concepts

- Ethernet
- MAC
- IP
- TCP/UDP
- ports
- DNS
- switching
- routing
- VLAN
- MTU
- NIC
- queues
- RSS
- latency
- bandwidth
- throughput
- packet loss
- congestion

### 📖 Study From

- Linux networking documentation
- TCP/IP educational material
- Ethernet vendor documentation
- NVIDIA Ethernet documentation

### 📦 Document Splitting

#### `ethernet_and_tcp_ip_fundamentals.pdf`
#### `network_switching_and_routing.pdf`
#### `network_interfaces_and_packet_io.pdf`
#### `network_performance_fundamentals.pdf`

### 🧪 Lab — Measure a Network Path

**Access:** 🟢  
**Best:** Two Linux hosts.

Inspect:

```bash
ip addr
ip route
ss -tuln
ethtool <interface>
```

Test latency:

```bash
ping <peer>
```

Trace route:

```bash
traceroute <peer>
```

Test throughput:

Server:

```bash
iperf3 -s
```

Client:

```bash
iperf3 -c <server>
```

Capture only traffic you are authorized to inspect:

```bash
sudo tcpdump -i <interface>
```

### 📊 Record

- RTT
- throughput
- link speed
- MTU
- packet loss

### 🏭 Production Relevance

Distributed AI performance depends heavily on predictable network behavior.

### 📦 Publish

```text
Labs/AI-Networking/network-baseline/
```

### ✅ Exit Criteria

- [ ] Explain bandwidth vs throughput vs latency.
- [ ] Inspect NIC configuration.
- [ ] Benchmark an authorized network path.

</details>

<details>
<summary><b>Phase 12 — 🔗 RDMA & RoCE</b></summary>

### 🎯 Goal

Understand CPU-bypass networking and RDMA over Ethernet.

### 🔗 Learning Order

`DMA → RDMA → Memory Registration → Verbs → QP/CQ → RoCE → PFC/ECN`

### 📚 Concepts

- DMA
- RDMA
- kernel bypass
- zero copy
- memory registration
- verbs
- Protection Domains
- Queue Pairs
- Completion Queues
- Send/Receive
- Read/Write
- RoCE
- RoCEv2
- PFC
- ECN
- congestion

### 📖 Study From

- NVIDIA Networking documentation
- NVIDIA RoCE documentation
- Linux RDMA / rdma-core documentation

### 📦 Document Splitting

#### `rdma_fundamentals.pdf`

DMA + RDMA + bypass + zero-copy + registration.

#### `rdma_verbs_and_queue_architecture.pdf`

Verbs + PD + QP + CQ + operations.

#### `roce_architecture.pdf`

RoCE/RoCEv2 + Ethernet transport.

#### `roce_congestion_control.pdf`

PFC + ECN + congestion.

### 🧪 Lab — Discover and Benchmark RDMA

**Access:** 🔵 / 📖

**Requirements:** Authorized RDMA-capable hosts.

Inspect:

```bash
rdma link
ibv_devices
ibv_devinfo
```

If two RDMA hosts exist, use perftest tools such as:

```bash
ib_write_bw
ib_read_bw
```

Record:

- device
- port state
- link layer
- bandwidth
- message size

### 📖 Hardware Fallback

If RDMA is unavailable:

1. Study `ibv_devinfo` sample output.
2. Draw:
   `Application → Registered Memory → QP → NIC → Fabric → Remote NIC → Memory`
3. Label where CPU/kernel involvement is reduced.
4. Do not mark physical benchmark complete.

### 🏭 Production Relevance

RDMA underpins high-performance distributed AI communication.

### 📦 Publish

```text
Docs/AI-Networking/
Labs/AI-Networking/RDMA/
Benchmarks/AI-Networking/RDMA/
```

### ✅ Exit Criteria

- [ ] Explain memory registration.
- [ ] Explain QP/CQ.
- [ ] Explain RoCEv2.
- [ ] Interpret basic RDMA device information.

</details>

<details>
<summary><b>Phase 13 — 🌐 InfiniBand</b></summary>

### 🎯 Goal

Understand and inspect a purpose-built high-performance fabric.

### 📚 Concepts

- HCA
- switch
- port
- fabric
- LID/GID
- Subnet Manager
- routing
- Service Levels
- Virtual Lanes
- congestion
- adaptive routing
- counters

### 📖 Study From

- NVIDIA InfiniBand documentation
- NVIDIA networking manuals
- NVIDIA fabric diagnostic documentation

### 📦 Document Splitting

#### `infiniband_architecture.pdf`
#### `infiniband_addressing_and_management.pdf`
#### `infiniband_routing_and_qos.pdf`
#### `infiniband_operations_and_diagnostics.pdf`

### 🧪 Lab — Discover an InfiniBand Fabric

**Access:** 🔵 / 📖

```bash
ibstat
ibv_devinfo
ibnetdiscover
ibhosts
ibswitches
iblinkinfo
```

Where authorized:

```bash
ibdiagnet
```

Build:

```text
HOST/HCA
   ↓
SWITCH
   ↓
SWITCH
   ↓
REMOTE HCA
```

Record link states and topology.

### 📖 Fallback

Use documented/sample topology output and manually identify HCAs, switches, ports, and fabric paths.

### 🏭 Production Relevance

Fabric topology and link health directly affect distributed GPU communication.

### 📦 Publish

```text
Labs/AI-Networking/InfiniBand/
```

### ✅ Exit Criteria

- [ ] Explain an InfiniBand fabric.
- [ ] Identify HCA/switch roles.
- [ ] Understand basic diagnostic workflow.

</details>

<details>
<summary><b>Phase 14 — 🟢 NVIDIA Networking</b></summary>

### 🎯 Goal

Understand NVIDIA's networking components used around accelerated clusters.

### 📚 Concepts

- ConnectX
- SuperNIC
- Spectrum
- BlueField
- DPU
- DOCA
- offload
- telemetry

### 📖 Study From

- NVIDIA Networking documentation
- ConnectX documentation
- Spectrum documentation
- BlueField documentation
- NVIDIA DOCA documentation

### 📦 Document Splitting

#### `nvidia_connectx_and_supernic.pdf`
#### `nvidia_spectrum_networking.pdf`
#### `nvidia_bluefield_dpu.pdf`
#### `nvidia_doca_fundamentals.pdf`

### 🧪 Lab — Identify NVIDIA Network Components

**Access:** 🟢 / 🔵 / 📖

On available Linux hardware:

```bash
lspci | grep -i -E 'mellanox|nvidia'
ip link
ethtool -i <interface>
```

If NVIDIA NIC exists, record:

- device
- driver
- firmware
- link
- PCIe location

Then draw:

```text
GPU SERVER
├── GPU
├── ConnectX / SuperNIC
│       ↓
└── Spectrum Fabric
```

Add BlueField separately and explain how DPU offload changes the design.

### 🏭 Production Relevance

Operators must know whether a problem belongs to host networking, NIC hardware, switch fabric, or DPU services.

### 📦 Publish

```text
Labs/AI-Networking/nvidia-network-inventory/
```

### ✅ Exit Criteria

- [ ] Distinguish NIC, SuperNIC, switch, and DPU.
- [ ] Explain ConnectX/Spectrum/BlueField roles.

</details>

<details>
<summary><b>Phase 15 — ⚡ GPUDirect</b></summary>

### 🎯 Goal

Understand how NVIDIA reduces unnecessary data copies between GPUs and I/O devices.

### 📚 Concepts

- peer-to-peer
- GPUDirect
- GPUDirect RDMA
- memory registration
- PCIe topology
- NIC↔GPU
- GPUDirect Storage

### 📖 Study From

- NVIDIA GPUDirect RDMA documentation
- NVIDIA GPUDirect Storage documentation
- CUDA peer-to-peer documentation

### 📦 Document Splitting

#### `gpudirect_peer_to_peer.pdf`
#### `gpudirect_rdma.pdf`
#### `gpudirect_storage.pdf`

### 🧪 Lab — Analyze GPU/NIC Locality

**Access:** 🟡 / 🔵 / 📖

```bash
nvidia-smi topo -m
lspci -t
```

Map GPU and NIC PCIe relationships.

Compare:

```text
Traditional:
GPU → Host Memory → CPU → NIC

GPUDirect RDMA:
GPU Memory ↔ NIC
```

If actual GPUDirect infrastructure exists, follow the vendor-supported validation/benchmark procedure for that environment.

### 🏭 Production Relevance

GPU/NIC locality and direct data paths can materially affect multi-node communication.

### 📦 Publish

```text
Labs/AI-Networking/gpudirect-topology/
```

### ✅ Exit Criteria

- [ ] Explain GPUDirect RDMA.
- [ ] Explain why PCIe locality matters.
- [ ] Distinguish GPUDirect RDMA from GDS.

</details>

---

# PART V — MULTI-GPU & DISTRIBUTED AI

<details>
<summary><b>Phase 16 — 🔗 Multi-GPU Architecture</b></summary>

### 🎯 Goal

Understand communication between GPUs inside a node.

### 📚 Concepts

- P2P
- PCIe
- NVLink
- NVSwitch
- NUMA
- affinity
- MIG
- scale-up
- scale-out

### 📖 Study From

- NVIDIA NVLink documentation
- NVIDIA NVSwitch documentation
- CUDA multi-GPU documentation
- NVIDIA MIG documentation

### 📦 Document Splitting

#### `gpu_peer_to_peer_architecture.pdf`
#### `nvlink_architecture.pdf`
#### `nvswitch_architecture.pdf`
#### `gpu_partitioning_and_mig.pdf`
#### `scale_up_vs_scale_out_ai.pdf`

### 🧪 Lab — Map Multi-GPU Topology

**Access:** 🟠 / 📖

```bash
nvidia-smi -L
nvidia-smi topo -m
nvidia-smi nvlink --status
```

Record GPU↔GPU paths.

Identify:

- PCIe paths
- NVLink connections
- NUMA affinity

### 📖 Fallback

Analyze published topology from an NVIDIA multi-GPU system.

### 🏭 Production Relevance

Topology-aware workload placement reduces communication penalties.

### 📦 Publish

```text
Labs/Distributed-AI/multi-gpu-topology/
```

### ✅ Exit Criteria

- [ ] Read a multi-GPU topology matrix.
- [ ] Explain NVLink vs NVSwitch.
- [ ] Explain scale-up vs scale-out.

</details>

<details>
<summary><b>Phase 17 — 🧮 NCCL & Collective Communication</b></summary>

### 🎯 Goal

Understand how multiple GPUs exchange data efficiently.

### 📚 Concepts

- rank
- communicator
- Broadcast
- Reduce
- AllReduce
- AllGather
- ReduceScatter
- All-to-All
- ring/tree
- topology
- transports
- debugging

### 📖 Study From

- NVIDIA NCCL User Guide
- NCCL API documentation
- NVIDIA `nccl-tests`

### 📦 Document Splitting

#### `collective_communication_fundamentals.pdf`
#### `collective_algorithms.pdf`
#### `nccl_architecture_and_transports.pdf`
#### `nccl_operations_and_debugging.pdf`

### 🧪 Lab — NCCL AllReduce Benchmark

**Access:** 🟠 / 🔵

**Requirements:** Multiple supported NVIDIA GPUs and NCCL test environment.

1. Inspect topology:

```bash
nvidia-smi topo -m
```

2. Run the supported `nccl-tests` AllReduce benchmark for your environment.
3. Test increasing message sizes.
4. Enable NCCL diagnostic output when investigating behavior:

```bash
export NCCL_DEBUG=INFO
```

5. Record:
   - message size
   - algorithm bandwidth
   - bus bandwidth

### 📖 Fallback

Study `nccl-tests` output and explain what each metric represents.

### 🏭 Production Relevance

Distributed training can become communication-bound even when GPUs are individually fast.

### 📦 Publish

```text
Benchmarks/Distributed-AI/NCCL/
```

### ✅ Exit Criteria

- [ ] Explain AllReduce.
- [ ] Explain ring/tree conceptually.
- [ ] Interpret NCCL benchmark results.
- [ ] Connect NCCL performance to topology.

</details>

<details>
<summary><b>Phase 18 — 🧠 Distributed AI Training</b></summary>

### 🎯 Goal

Understand how training computation and model state are distributed.

### 📚 Concepts

- rank/world size
- DDP
- data parallelism
- tensor parallelism
- pipeline parallelism
- FSDP2
- sharding
- synchronization
- gradient communication
- checkpoints
- stragglers
- failures

### 📖 Study From

- PyTorch Distributed documentation
- PyTorch DDP tutorial
- PyTorch FSDP2 tutorial
- PyTorch Tensor/Pipeline Parallel documentation

### 📦 Document Splitting

#### `distributed_training_fundamentals.pdf`
#### `data_parallel_training.pdf`
#### `model_parallelism.pdf`
#### `distributed_sharding_and_fsdp.pdf`
#### `distributed_training_reliability.pdf`

### 🧪 Lab — Single-Node DDP

**Access:** 🟠

1. Start with a working single-GPU PyTorch training script.
2. Convert to DDP.
3. Use one process per GPU.
4. Launch with the current PyTorch distributed launcher (`torchrun`).
5. Record:
   - runtime
   - GPU utilization
   - memory/GPU
   - throughput

Compare single GPU vs multi-GPU.

### 📖 Fallback

Trace a DDP iteration:

```text
FORWARD
 ↓
BACKWARD
 ↓
LOCAL GRADIENTS
 ↓
ALLREDUCE
 ↓
SYNCHRONIZED GRADIENTS
 ↓
OPTIMIZER STEP
```

### 🏭 Production Relevance

Distributed training couples model code to GPU memory, collective communication, topology, and failure handling.

### 📦 Publish

```text
Code/Distributed-AI/PyTorch-DDP/
Benchmarks/Distributed-AI/DDP/
```

### ✅ Exit Criteria

- [ ] Explain rank/world size.
- [ ] Explain DDP synchronization.
- [ ] Explain when sharding becomes necessary.
- [ ] Distinguish DDP, FSDP2, TP, and PP.

</details>

---

# PART VI — SERVERS & CLUSTERS

<details>
<summary><b>Phase 19 — 🖥️ AI Server Architecture</b></summary>

### 🎯 Goal

Treat a GPU server as an integrated hardware system.

### 📚 Concepts

- motherboard
- CPU
- NUMA
- RAM
- PCIe
- GPU
- NIC
- NVMe
- BMC
- power
- cooling
- failure domains

### 📦 Document Splitting

#### `gpu_server_compute_architecture.pdf`
#### `gpu_server_io_architecture.pdf`
#### `gpu_server_management_and_reliability.pdf`

### 🧪 Lab — Build a Server Inventory

**Access:** 🟢 / 🟡

Use:

```bash
lscpu
free -h
lspci
lsblk
ip link
nvidia-smi
nvidia-smi topo -m
```

If permitted, inspect platform management information using vendor-supported BMC/IPMI tooling.

Create:

```text
SERVER
├── CPU
├── RAM
├── GPU
├── NIC
├── NVMe
└── MANAGEMENT
```

### 🏭 Production Relevance

Failure diagnosis requires knowing which physical component owns a symptom.

### 📦 Publish

```text
Labs/AI-Servers-Clusters/server-inventory/
```

### ✅ Exit Criteria

- [ ] Draw a GPU server.
- [ ] Explain compute vs I/O topology.
- [ ] Explain BMC purpose.

</details>

<details>
<summary><b>Phase 20 — 🟢 NVIDIA DGX / HGX Systems</b></summary>

### 🎯 Goal

Understand NVIDIA's integrated multi-GPU server architecture.

### 📚 Concepts

- HGX
- DGX
- SXM
- NVLink
- NVSwitch
- CPU/GPU topology
- NIC/storage
- management

### 📖 Study From

- NVIDIA DGX documentation
- NVIDIA HGX platform documentation
- NVIDIA system architecture guides

### 📦 Document Splitting

#### `nvidia_hgx_architecture.pdf`
#### `nvidia_dgx_system_architecture.pdf`
#### `nvidia_dgx_system_management.pdf`
#### `dgx_vs_hgx.pdf`

### 🧪 Lab — Reverse Engineer a DGX/HGX Topology

**Access:** 📖 / 🟡 if system available

1. Select one DGX/HGX generation.
2. Read its official system architecture.
3. Record:
   - GPUs
   - CPU
   - memory
   - NVLink/NVSwitch
   - NICs
   - storage
4. Draw topology.
5. If actual DGX access exists, compare your diagram against `nvidia-smi topo -m`.

### 🏭 Production Relevance

DGX/HGX knowledge connects individual GPU concepts to production-scale NVIDIA systems.

### 📦 Publish

```text
Labs/AI-Servers-Clusters/dgx-hgx-topology/
```

### ✅ Exit Criteria

- [ ] Explain HGX vs DGX.
- [ ] Explain SXM/NVSwitch role.
- [ ] Read an NVIDIA system topology.

</details>

<details>
<summary><b>Phase 21 — 🏢 AI Cluster Architecture</b></summary>

### 🎯 Goal

Scale from one GPU server to a managed cluster.

### 📚 Concepts

- compute nodes
- management nodes
- storage
- fabrics
- scheduling
- job queues
- management network
- compute network
- failure domains
- HA
- capacity planning

### 📦 Document Splitting

#### `ai_cluster_compute_architecture.pdf`
#### `ai_cluster_network_architecture.pdf`
#### `ai_cluster_resource_management.pdf`
#### `ai_cluster_reliability_and_capacity.pdf`

### 🧪 Architecture Lab — Design an 8×8 GPU Cluster

**Access:** 📖

Design:

```text
8 NODES
×
8 GPUs/NODE
=
64 GPUs
```

Specify:

- intra-node GPU topology
- inter-node fabric
- management network
- storage
- scheduler/orchestrator
- monitoring
- failure domains

### ❓ Questions

- What fails if one node dies?
- What if one switch fails?
- How are workloads scheduled?
- How is storage shared?

### 🏭 Production Relevance

Cluster design determines scale, availability, manageability, and performance.

### 📦 Publish

```text
Projects/ai-cluster-design/
```

### ✅ Exit Criteria

- [ ] Design a logical GPU cluster.
- [ ] Identify major failure domains.
- [ ] Explain management vs compute networks.

</details>

---

# PART VII — CONTAINERS & KUBERNETES

<details>
<summary><b>Phase 22 — 📦 Containers for GPU Workloads</b></summary>

### 🎯 Goal

Understand how GPU applications are packaged and isolated.

### 📚 Concepts

- images
- layers
- registries
- namespaces
- cgroups
- OCI
- volumes
- networking
- NVIDIA Container Toolkit
- NGC

### 📖 Study From

- Docker documentation
- NVIDIA Container Toolkit documentation
- NVIDIA NGC documentation

### 📦 Document Splitting

#### `container_fundamentals.pdf`
#### `container_isolation_and_resources.pdf`
#### `nvidia_gpu_containers.pdf`
#### `nvidia_ngc_containers.pdf`

### 🧪 Lab — Run a GPU Container

**Access:** 🟡

1. Verify host:

```bash
nvidia-smi
docker --version
```

2. Install/configure NVIDIA Container Toolkit according to official documentation.
3. Run a supported CUDA/NVIDIA container with GPU access.
4. Inside container run:

```bash
nvidia-smi
```

5. Compare host/container GPU visibility.

### 🏭 Production Relevance

Containers make GPU software stacks reproducible across hosts.

### 📦 Publish

```text
Labs/Containers-Kubernetes/gpu-container/
```

### ✅ Exit Criteria

- [ ] Explain image vs container.
- [ ] Explain namespaces/cgroups conceptually.
- [ ] Run a GPU-enabled container.

</details>

<details>
<summary><b>Phase 23 — ☸️ Kubernetes Fundamentals</b></summary>

### 🎯 Goal

Understand the orchestration layer used to manage containerized workloads.

### 📚 Concepts

- API server
- etcd
- scheduler
- controllers
- nodes
- kubelet
- Pods
- Deployments
- Services
- ConfigMaps
- Secrets
- requests/limits
- probes
- networking
- persistent storage

### 📖 Study From

- Kubernetes official Concepts
- Kubernetes Tasks
- Kubernetes Tutorials

### 📦 Document Splitting

#### `kubernetes_control_plane.pdf`
#### `kubernetes_nodes_and_workloads.pdf`
#### `kubernetes_workload_configuration.pdf`
#### `kubernetes_networking_and_services.pdf`
#### `kubernetes_storage_fundamentals.pdf`

### 🧪 Lab — Deploy and Diagnose a Workload

**Access:** 🟢

Use a local Kubernetes environment.

1. Inspect:

```bash
kubectl get nodes
kubectl get pods -A
```

2. Create a Deployment.
3. Expose it with a Service.
4. Inspect:

```bash
kubectl get pods -o wide
kubectl describe pod <pod>
kubectl logs <pod>
```

5. Delete a Pod.
6. Observe controller recovery.
7. Deliberately use a bad image tag.
8. Diagnose the resulting failure.
9. Correct it.

### 🏭 Production Relevance

Operating Kubernetes requires understanding both normal reconciliation and failure states.

### 📦 Publish

```text
Code/Kubernetes/Fundamentals/
Labs/Containers-Kubernetes/kubernetes-basics/
```

### ✅ Exit Criteria

- [ ] Deploy a workload.
- [ ] Inspect scheduling.
- [ ] Read Pod logs/events.
- [ ] Diagnose a simple failed Pod.

</details>

<details>
<summary><b>Phase 24 — ⚡ Kubernetes for GPUs</b></summary>

### 🎯 Goal

Understand how GPUs become schedulable Kubernetes resources.

### 📚 Concepts

- extended resources
- device plugins
- `nvidia.com/gpu`
- labels
- taints/tolerations
- affinity
- GPU topology
- sharing
- MIG

### 📖 Study From

- Kubernetes GPU scheduling documentation
- NVIDIA Kubernetes Device Plugin documentation
- NVIDIA MIG documentation

### 📦 Document Splitting

#### `kubernetes_gpu_resources.pdf`
#### `kubernetes_gpu_scheduling.pdf`
#### `kubernetes_gpu_sharing_and_mig.pdf`

### 🧪 Lab — Schedule and Diagnose a GPU Pod

**Access:** 🟡

**Requirements**

- Kubernetes
- NVIDIA GPU node
- working NVIDIA device integration

#### Step 1

```bash
kubectl get nodes
kubectl describe node <gpu-node>
```

Find GPU resources under capacity/allocatable.

#### Step 2

Create a Pod whose resource limit requests one GPU.

#### Step 3

```bash
kubectl apply -f gpu-pod.yaml
kubectl get pod -o wide
kubectl describe pod <pod>
```

#### Step 4

Inside the Pod:

```bash
nvidia-smi
```

#### Step 5 — Failure Exercise

Request more GPUs than available.

Observe:

```bash
kubectl describe pod <pod>
```

Find scheduler events explaining why the Pod remains Pending.

### ❓ Questions

- Who exposes `nvidia.com/gpu`?
- Why is the Pod Pending?
- What is the difference between discovering and scheduling a GPU?

### 🏭 Production Relevance

Unschedulable GPU workloads are common operational problems in accelerator clusters.

### 📦 Publish

```text
Labs/Containers-Kubernetes/gpu-scheduling/
```

### ✅ Exit Criteria

- [ ] Find allocatable GPUs.
- [ ] Schedule a GPU Pod.
- [ ] Diagnose an intentionally unschedulable GPU Pod.

</details>

<details>
<summary><b>Phase 25 — 🟢 NVIDIA GPU Operator</b></summary>

### 🎯 Goal

Understand automated lifecycle management of NVIDIA software on Kubernetes GPU nodes.

### 📚 Concepts

- Operator pattern
- ClusterPolicy
- driver
- Container Toolkit
- Device Plugin
- GPU Feature Discovery
- DCGM
- DCGM Exporter
- MIG Manager

### 📖 Study From

- NVIDIA GPU Operator documentation
- NVIDIA GPU Operator installation guide
- GPU Operator platform support/component matrix

### 📦 Document Splitting

#### `nvidia_gpu_operator_architecture.pdf`
#### `gpu_operator_software_stack.pdf`
#### `gpu_operator_monitoring_and_mig.pdf`

### 🧪 Lab — Install and Inspect GPU Operator

**Access:** 🟡

Before installation:

- verify supported OS/Kubernetes combination
- verify driver strategy
- verify Helm and `kubectl`

Install using the **current official NVIDIA procedure**, not a hard-coded old chart version.

Then inspect:

```bash
kubectl get pods -n gpu-operator
kubectl get clusterpolicy
kubectl get nodes
```

Identify components corresponding to:

```text
DRIVER
CONTAINER TOOLKIT
DEVICE PLUGIN
GFD
DCGM
DCGM EXPORTER
MIG MANAGER
```

Run a GPU verification workload.

### 🏭 Production Relevance

GPU Operator reduces manual lifecycle management across fleets of GPU Kubernetes nodes.

### 📦 Publish

```text
Labs/Containers-Kubernetes/GPU-Operator/
```

### ✅ Exit Criteria

- [ ] Explain Operator reconciliation.
- [ ] Identify GPU Operator components.
- [ ] Verify GPU node readiness.

</details>

---

# PART VIII — AI SOFTWARE STACK

<details>
<summary><b>Phase 26 — 🧰 NVIDIA & AI Software Stack</b></summary>

### 🎯 Goal

Trace an AI operation from framework to GPU hardware.

### 🔗 Learning Order

```text
APPLICATION
 ↓
PYTORCH
 ↓
CUDA LIBRARIES
 ↓
CUDA RUNTIME
 ↓
CUDA DRIVER API
 ↓
NVIDIA DRIVER
 ↓
GPU
```

### 📚 Concepts

- driver
- CUDA Toolkit
- Runtime API
- Driver API
- cuBLAS
- cuDNN
- NCCL
- TensorRT
- framework
- NGC
- compatibility

### 📖 Study From

- CUDA platform documentation
- CUDA compatibility documentation
- cuBLAS/cuDNN documentation
- NCCL documentation
- TensorRT documentation
- NGC documentation

### 📦 Document Splitting

#### `nvidia_driver_and_cuda_stack.pdf`
#### `nvidia_cuda_libraries.pdf`
#### `ai_framework_to_gpu_stack.pdf`
#### `nvidia_ai_software_ecosystem.pdf`

### 🧪 Lab — Inspect Software Compatibility

**Access:** 🟡

```bash
nvidia-smi
nvcc --version
python -c "import torch; print(torch.__version__); print(torch.version.cuda); print(torch.cuda.is_available())"
```

Record:

- driver
- CUDA Toolkit
- framework
- framework CUDA build
- GPU

Draw the software stack.

### 🏭 Production Relevance

Driver/runtime/framework incompatibilities are a major class of GPU deployment failures.

### 📦 Publish

```text
Labs/NVIDIA-GPU-CUDA/software-stack-inventory/
```

### ✅ Exit Criteria

- [ ] Explain driver vs Toolkit.
- [ ] Explain Runtime vs Driver API.
- [ ] Trace PyTorch to hardware.

</details>

---

# PART IX — INFERENCE & DEPLOYMENT

<details>
<summary><b>Phase 27 — 🚀 AI Inference Fundamentals</b></summary>

### 🎯 Goal

Understand inference as both a GPU workload and a production service.

### 🔗 Learning Order

`Inference Lifecycle → Performance → Batching → Memory → Scaling/SLOs`

### 📚 Concepts

- training vs inference
- online/batch inference
- model loading
- warmup
- latency
- throughput
- RPS
- concurrency
- batching
- queues
- GPU memory
- KV cache
- precision
- quantization
- replicas
- load balancing
- autoscaling
- SLO
- tail latency

### 📖 Study From

- framework inference documentation
- NVIDIA inference material
- model-serving documentation
- performance-engineering material

### 📦 Document Splitting

#### `ai_inference_fundamentals.pdf`

Training vs inference + lifecycle + online/batch + loading + warmup.

#### `inference_performance_fundamentals.pdf`

Latency + throughput + RPS + concurrency + tail latency.

#### `inference_batching_and_scheduling.pdf`

Batching + dynamic batching + queues + scheduling.

#### `inference_memory_and_optimization.pdf`

VRAM + weights + KV cache + precision + quantization.

#### `inference_scaling_and_slos.pdf`

Replicas + load balancing + autoscaling + capacity + SLOs.

### 🧪 Lab — Repeatable Inference Benchmark

**Access:** 🟡

**Goal:** Measure how batch size changes inference behavior.

1. Select a small model that fits comfortably on the GPU.
2. Record model/hardware/software versions.
3. Warm up the model.
4. Test:

```text
Batch: 1, 2, 4, 8, 16, 32
```

Stop before unsafe memory pressure.

5. For each batch size run repeated measurements.
6. Record:
   - average latency
   - p50
   - p95
   - p99 where tooling supports it
   - throughput
   - VRAM
   - GPU utilization

### 📊 Results

```text
Batch | Avg | p50 | p95 | p99 | Throughput | VRAM | GPU Util
```

### ❓ Questions

- Which batch maximized throughput?
- What happened to latency?
- When did memory become limiting?
- Why can throughput improve while latency worsens?

### 🏭 Production Relevance

Inference platforms optimize multiple competing objectives rather than simply maximizing GPU utilization.

### 📦 Publish

```text
Benchmarks/Deployment-Inference/batch-size-scaling/
```

### ✅ Exit Criteria

- [ ] Explain latency/throughput trade-off.
- [ ] Run a reproducible benchmark.
- [ ] Explain batching and concurrency.
- [ ] Explain basic production scaling.

</details>

<details>
<summary><b>Phase 28 — 🟢 NVIDIA Inference Stack</b></summary>

### 🎯 Goal

Learn NVIDIA model optimization and serving components.

### 📚 Concepts

**TensorRT**
- engine
- graph optimization
- precision
- profiles
- runtime

**Triton**
- model repository
- backend
- batching
- concurrency
- HTTP/gRPC
- metrics

### 📖 Study From

- NVIDIA TensorRT documentation
- NVIDIA Triton Inference Server documentation

### 📦 Document Splitting

#### `tensorrt_architecture.pdf`
#### `tensorrt_model_optimization.pdf`
#### `triton_inference_server_architecture.pdf`
#### `triton_batching_and_concurrency.pdf`
#### `triton_serving_and_observability.pdf`

### 🧪 Lab — Optimize Then Serve

**Access:** 🟡

Part A:

1. Select compatible model.
2. Establish baseline.
3. Optimize/build TensorRT engine using supported workflow.
4. Benchmark.
5. Compare.

Part B:

1. Create Triton model repository.
2. Start Triton.
3. Verify model readiness.
4. Send requests.
5. Test batching/concurrency.
6. inspect metrics.

### 📊 Compare

```text
Baseline vs Optimized
Latency
Throughput
VRAM
Precision
```

### 🏭 Production Relevance

TensorRT optimizes model execution; Triton provides a serving layer around models.

### 📦 Publish

```text
Projects/gpu-inference-platform/
Benchmarks/Deployment-Inference/TensorRT/
```

### ✅ Exit Criteria

- [ ] Explain TensorRT vs Triton.
- [ ] Benchmark an optimization.
- [ ] Serve a model.
- [ ] Inspect serving metrics.

</details>

---

# PART X — OBSERVABILITY & PERFORMANCE

<details>
<summary><b>Phase 29 — 📡 GPU Observability & Telemetry</b></summary>

### 🎯 Goal

Build visibility into GPU infrastructure health and utilization.

### 📚 Concepts

- metrics/logs/traces
- utilization
- VRAM
- power
- temperature
- clocks
- ECC
- health
- DCGM
- DCGM Exporter
- Prometheus
- Grafana
- alerting

### 📖 Study From

- NVIDIA DCGM documentation
- DCGM Exporter documentation
- Prometheus documentation
- Grafana documentation

### 📦 Document Splitting

#### `gpu_telemetry_fundamentals.pdf`
#### `nvidia_dcgm.pdf`
#### `gpu_metrics_pipeline.pdf`
#### `gpu_dashboards_and_alerting.pdf`

### 🧪 Lab — GPU Telemetry Pipeline

**Access:** 🟡

Start with host inspection:

```bash
nvidia-smi
```

Install/use DCGM according to the supported procedure.

Explore:

```bash
dcgmi discovery -l
dcgmi health -g 0 --set a
```

Use commands appropriate to your installed DCGM release.

Then deploy DCGM Exporter.

Verify metrics endpoint and configure Prometheus scraping.

Build Grafana panels for:

- utilization
- memory
- power
- temperature
- health/error signals

### 🔎 Observe

Generate an authorized GPU workload and watch metric changes.

### 🏭 Production Relevance

Without telemetry, GPU capacity and failures are largely invisible at fleet scale.

### 📦 Publish

```text
Projects/gpu-monitoring-stack/
```

### ✅ Exit Criteria

- [ ] Explain DCGM vs DCGM Exporter.
- [ ] Collect GPU metrics.
- [ ] Query metrics.
- [ ] Build useful dashboards.

</details>

<details>
<summary><b>Phase 30 — 📈 GPU Performance Engineering</b></summary>

### 🎯 Goal

Find bottlenecks using measurements rather than assumptions.

### 📚 Concepts

- baselines
- bottlenecks
- utilization
- occupancy
- bandwidth
- arithmetic intensity
- roofline
- CPU starvation
- PCIe
- storage
- network
- profiling
- regression

### 📖 Study From

- NVIDIA Nsight Systems documentation
- NVIDIA Nsight Compute documentation
- CUDA Best Practices Guide

### 📦 Document Splitting

#### `gpu_performance_methodology.pdf`
#### `gpu_compute_and_memory_performance.pdf`
#### `system_level_ai_bottlenecks.pdf`
#### `nvidia_gpu_profiling.pdf`

### 🧪 Lab — End-to-End Bottleneck Investigation

**Access:** 🟡

1. Select a GPU workload.
2. Establish baseline.
3. Observe CPU/GPU utilization.
4. Profile timeline with Nsight Systems.
5. If CUDA kernels are relevant, inspect them with Nsight Compute.
6. Check:
   - CPU
   - GPU compute
   - GPU memory
   - PCIe/data movement
   - storage
   - network where relevant
7. Form one hypothesis.
8. Change one variable.
9. Measure again.

### 📊 Classify

```text
CPU BOUND
GPU COMPUTE BOUND
GPU MEMORY BOUND
PCIe / TRANSFER BOUND
STORAGE BOUND
NETWORK BOUND
```

### 🏭 Production Relevance

Expensive GPUs should not be upgraded merely because another subsystem is starving them.

### 📦 Publish

```text
Benchmarks/Performance-Operations/end-to-end-investigation/
```

### ✅ Exit Criteria

- [ ] Establish a baseline.
- [ ] Profile execution.
- [ ] Form evidence-based hypotheses.
- [ ] Demonstrate or reject a bottleneck.

</details>

---

# PART XI — SECURITY & RELIABILITY

<details>
<summary><b>Phase 31 — 🔐 AI Infrastructure Security</b></summary>

### 🎯 Goal

Understand the trust boundaries of shared accelerator infrastructure.

### 📚 Concepts

- least privilege
- IAM
- SSH
- secrets
- segmentation
- firewalls
- container security
- RBAC
- image security
- supply chain
- GPU isolation
- MIG
- multi-tenancy
- audit
- patching

### 📖 Study From

- Linux security documentation
- Kubernetes security documentation
- NVIDIA security documentation/bulletins
- cloud-provider IAM/security documentation

### 📦 Document Splitting

#### `linux_and_host_security_for_ai.pdf`
#### `container_and_kubernetes_security.pdf`
#### `gpu_isolation_and_multitenancy.pdf`
#### `ai_infrastructure_network_security.pdf`

### 🧪 Lab — Threat Model a GPU Cluster

**Access:** 📖

Draw:

```text
USER
 ↓
API / SSH
 ↓
KUBERNETES
 ↓
CONTAINER
 ↓
GPU NODE
 ↓
GPU / NETWORK / STORAGE
```

For each boundary identify:

- asset
- threat
- access control
- telemetry
- mitigation

Do not perform offensive testing against systems you do not own or have permission to test.

### 🏭 Production Relevance

Shared GPU infrastructure combines high-value models/data with expensive shared hardware.

### 📦 Publish

```text
Labs/Security-Troubleshooting/gpu-cluster-threat-model/
```

### ✅ Exit Criteria

- [ ] Identify trust boundaries.
- [ ] Explain least privilege.
- [ ] Explain GPU multi-tenancy risks.
- [ ] Create a basic threat model.

</details>

<details>
<summary><b>Phase 32 — 🛠️ Troubleshooting & Reliability</b></summary>

### 🎯 Goal

Develop a repeatable troubleshooting methodology.

### 🔗 Troubleshooting Order

```text
APPLICATION
 ↓
FRAMEWORK
 ↓
CUDA
 ↓
GPU
 ↓
PCIe
 ↓
MEMORY
 ↓
NETWORK
 ↓
STORAGE
 ↓
KUBERNETES
 ↓
PHYSICAL SYSTEM
```

### 📚 Concepts

- CUDA/GPU errors
- OOM
- thermal issues
- ECC
- driver mismatch
- PCIe problems
- NCCL failures
- RDMA/fabric failures
- storage latency
- container failures
- scheduling failures
- node failures
- RCA
- incident response
- runbooks

### 📦 Document Splitting

#### `gpu_and_cuda_troubleshooting.pdf`
#### `ai_network_troubleshooting.pdf`
#### `kubernetes_gpu_troubleshooting.pdf`
#### `ai_infrastructure_incident_response.pdf`

### 🧪 Lab — Controlled Failure Investigation

**Access:** 🟢 / 🟡

Use only your lab environment.

Create safe failures such as:

1. bad container image
2. impossible Kubernetes resource request
3. incorrect application configuration
4. controlled GPU-memory pressure
5. intentionally slow test storage workload

For each:

```text
SYMPTOM
 ↓
EVIDENCE
 ↓
HYPOTHESIS
 ↓
TEST
 ↓
ROOT CAUSE
 ↓
FIX
 ↓
VERIFICATION
```

### 🛠️ Runbooks

Create separately:

```text
Runbooks/
├── gpu-oom.md
├── gpu-not-detected.md
├── nccl-failure.md
├── rdma-link-issue.md
├── kubernetes-gpu-unschedulable.md
└── driver-cuda-mismatch.md
```

### 🏭 Production Relevance

A strong operator reduces mean time to diagnosis by following evidence and layers.

### ✅ Exit Criteria

- [ ] Triage systematically.
- [ ] Use logs/events/metrics.
- [ ] Produce an RCA.
- [ ] Write reusable runbooks.

</details>

---

# PART XII — CLOUD & ENTERPRISE

<details>
<summary><b>Phase 33 — ☁️ Cloud GPU Infrastructure</b></summary>

### 🎯 Goal

Map physical AI infrastructure concepts onto cloud primitives.

### 📚 Concepts

- GPU instances
- sizing
- images
- VPC
- subnets
- IAM
- security groups
- storage
- managed Kubernetes
- autoscaling
- placement
- spot capacity
- cost
- hybrid infrastructure

### 📖 Study From

Choose one primary cloud first.

Use its official documentation for:

- GPU instances
- networking
- storage
- IAM
- Kubernetes
- monitoring
- pricing

### 📦 Document Splitting

#### `cloud_gpu_compute.pdf`
#### `cloud_ai_networking_and_security.pdf`
#### `cloud_storage_for_ai.pdf`
#### `cloud_gpu_scaling_and_cost.pdf`
#### `hybrid_ai_infrastructure.pdf`

### 🧪 Lab — Design and Optionally Deploy Cloud GPU Infrastructure

**Access:** ☁️ / 📖

Architecture:

```text
VPC
├── MANAGEMENT
├── GPU COMPUTE
├── STORAGE
└── MONITORING
```

If using paid resources:

1. Estimate cost first.
2. Create only required resources.
3. Verify GPU.
4. perform a small workload.
5. collect basic metrics.
6. terminate resources when finished.
7. verify no unnecessary billable resources remain.

### 🏭 Production Relevance

Cloud adds elasticity but introduces placement, networking, quota, availability, and cost constraints.

### 📦 Publish

```text
Projects/cloud-ai-architecture/
```

### ✅ Exit Criteria

- [ ] Select an appropriate GPU instance conceptually.
- [ ] Design cloud networking/storage.
- [ ] Explain cost/capacity trade-offs.

</details>

<details>
<summary><b>Phase 34 — 🟢 NVIDIA AI Enterprise & NGC</b></summary>

### 🎯 Goal

Understand NVIDIA's enterprise software distribution and deployment ecosystem.

### 📚 Concepts

- NVIDIA AI Enterprise
- NGC Catalog
- optimized containers
- lifecycle
- compatibility
- enterprise support
- deployment models
- NIM

### 📖 Study From

- NVIDIA AI Enterprise documentation
- NVIDIA NGC documentation
- NVIDIA NIM documentation

### 📦 Document Splitting

#### `nvidia_ai_enterprise_architecture.pdf`
#### `nvidia_ngc_ecosystem.pdf`
#### `nvidia_ai_enterprise_lifecycle.pdf`
#### `nvidia_nim_fundamentals.pdf`

### 🧪 Lab — Inspect and Run an NGC Artifact

**Access:** 🟡 / ☁️

1. Explore an appropriate official NGC container/model.
2. Record:
   - purpose
   - required GPU
   - software dependencies
   - deployment method
3. Run an appropriate artifact if infrastructure permits.
4. Verify GPU access.
5. document the environment.

### 🏭 Production Relevance

Enterprise infrastructure depends on tested software stacks, compatibility, lifecycle management, and supported deployment patterns.

### 📦 Publish

```text
Labs/Cloud-NVIDIA-Enterprise/NGC/
```

### ✅ Exit Criteria

- [ ] Explain NGC.
- [ ] Explain NVIDIA AI Enterprise's role.
- [ ] Explain NIM at a high level.

</details>

---

# PART XIII — DATA CENTERS & AI FACTORIES

<details>
<summary><b>Phase 35 — 🏭 AI Data Centers</b></summary>

### 🎯 Goal

Extend infrastructure thinking from servers to facilities.

### 📚 Concepts

- racks
- rack units
- GPU density
- power
- power distribution
- air/liquid cooling
- cabling
- network fabrics
- storage
- redundancy
- telemetry
- capacity
- efficiency

### 📖 Study From

- NVIDIA data-center infrastructure material
- server/rack vendor architecture
- data-center power/cooling engineering material

### 📦 Document Splitting

#### `ai_data_center_rack_architecture.pdf`
#### `ai_data_center_power_and_cooling.pdf`
#### `ai_data_center_network_and_storage.pdf`
#### `ai_data_center_capacity_and_reliability.pdf`

### 🧪 Architecture Lab — Design a GPU Rack

**Access:** 📖

Specify:

- server count
- GPUs/server
- network connections
- management connections
- storage
- estimated power considerations
- cooling approach
- redundancy

Draw front/logical topology.

### ❓ Questions

- What limits rack GPU density?
- Why is liquid cooling increasingly relevant?
- What happens when power capacity is insufficient?
- Where are the failure domains?

### 🏭 Production Relevance

Large-scale AI is constrained by facilities as well as compute.

### 📦 Publish

```text
Projects/gpu-rack-design/
```

### ✅ Exit Criteria

- [ ] Explain rack density constraints.
- [ ] Explain power/cooling implications.
- [ ] Design a conceptual GPU rack.

</details>

<details>
<summary><b>Phase 36 — 🏭 AI Factories</b></summary>

### 🎯 Goal

Combine compute, networking, storage, software, and operations into an AI production system.

### 📚 Concepts

- data ingestion
- preparation
- training
- fine-tuning
- inference
- accelerated compute
- GPU clusters
- storage
- fabrics
- orchestration
- observability
- security
- lifecycle
- capacity
- energy

### 📖 Study From

- NVIDIA AI Factory material
- NVIDIA reference architectures
- NVIDIA enterprise/data-center material

### 📦 Document Splitting

#### `ai_factory_architecture.pdf`
#### `ai_factory_workload_pipeline.pdf`
#### `ai_factory_operations.pdf`

### 🧪 Architecture Lab — Design an AI Factory

**Access:** 📖

Design:

```text
DATA SOURCES
    ↓
INGESTION
    ↓
STORAGE
    ↓
GPU CLUSTER
    ↓
HIGH-SPEED FABRIC
    ↓
TRAINING / FINE-TUNING
    ↓
MODEL REGISTRY
    ↓
INFERENCE
    ↓
OBSERVABILITY
```

For every block document:

- purpose
- scaling constraint
- failure mode
- telemetry
- security boundary

### 🏭 Production Relevance

An AI factory is a system-of-systems; optimizing one layer in isolation is insufficient.

### 📦 Publish

```text
Projects/ai-factory-architecture/
```

### ✅ Exit Criteria

- [ ] Explain end-to-end AI factory architecture.
- [ ] Identify dependencies and bottlenecks.
- [ ] Identify operational failure domains.

</details>

<details>
<summary><b>Phase 37 — 🛠️ Production AI Infrastructure Operations</b></summary>

### 🎯 Goal

Integrate the entire roadmap into production-oriented operational thinking.

### 📚 Concepts

- provisioning
- configuration management
- cluster lifecycle
- scheduling
- GPU allocation
- capacity
- observability
- SLOs
- incident response
- RCA
- upgrades
- driver/CUDA lifecycle
- Kubernetes lifecycle
- GPU Operator lifecycle
- networking
- storage
- backup/recovery
- security
- cost
- automation

### 📦 Document Splitting

#### `ai_infrastructure_lifecycle_management.pdf`

Provisioning + configuration + upgrades + compatibility.

#### `ai_infrastructure_capacity_and_scheduling.pdf`

GPU allocation + scheduling + utilization + capacity + cost.

#### `production_ai_observability_and_slos.pdf`

Monitoring + alerting + SLOs + service health.

#### `production_ai_reliability_engineering.pdf`

Incidents + RCA + change management + recovery.

#### `ai_infrastructure_operations.pdf`

GPU + network + storage + Kubernetes operations.

#### `ai_infrastructure_automation.pdf`

Repeatability + automation + configuration workflows.

### 🏗️ Final Capstone

Build or design:

```text
Projects/
└── production-ai-infrastructure/
    ├── README.md
    ├── architecture/
    ├── automation/
    ├── kubernetes/
    ├── monitoring/
    ├── benchmarks/
    ├── runbooks/
    └── troubleshooting/
```

### 🧪 Capstone Scenarios

Practice, where safely possible:

1. GPU workload deployment
2. GPU monitoring
3. inference benchmark
4. unschedulable workload
5. GPU memory pressure
6. container failure
7. simulated node/service failure
8. performance regression
9. runbook execution
10. post-incident write-up

### 🔗 Operational Flow

```text
PROVISION
 ↓
CONFIGURE
 ↓
VALIDATE
 ↓
DEPLOY
 ↓
MONITOR
 ↓
MEASURE
 ↓
DETECT
 ↓
DIAGNOSE
 ↓
RECOVER
 ↓
DOCUMENT
 ↓
AUTOMATE
```

### 🏭 Production Relevance

This phase turns isolated technical knowledge into infrastructure operations capability.

### 📦 Publish

```text
Projects/production-ai-infrastructure/
Runbooks/
Benchmarks/
```

### ✅ Final Exit Criteria

I should be able to reason across:

```text
FACILITY
   ↓
SERVER
   ↓
CPU / MEMORY
   ↓
GPU
   ↓
STORAGE
   ↓
NETWORK
   ↓
MULTI-GPU / NCCL
   ↓
CLUSTER
   ↓
CONTAINER
   ↓
KUBERNETES
   ↓
NVIDIA SOFTWARE
   ↓
AI WORKLOAD
   ↓
OBSERVABILITY
   ↓
OPERATIONS
```

And I should be able to:

- [ ] inspect infrastructure
- [ ] deploy workloads
- [ ] measure performance
- [ ] identify bottlenecks
- [ ] diagnose failures
- [ ] document incidents
- [ ] write runbooks
- [ ] automate repeatable work
- [ ] explain architectural trade-offs

</details>

---

# 📚 Primary Study Source Map

Use **official documentation first**.

| Domain | Primary Source |
|---|---|
| Linux | Linux Kernel + distribution documentation |
| Computer Architecture | CPU/vendor architecture documentation |
| Parallel Computing | OpenMP + HPC material |
| CUDA | NVIDIA CUDA Programming Guide |
| CUDA Optimization | NVIDIA CUDA Best Practices Guide |
| GPU Architecture | NVIDIA architecture documentation |
| GPU Profiling | NVIDIA Nsight Systems / Nsight Compute |
| Storage | Linux/NVMe/vendor documentation |
| Ethernet | Linux + NVIDIA Ethernet documentation |
| RDMA | NVIDIA Networking + rdma-core |
| RoCE | NVIDIA Networking documentation |
| InfiniBand | NVIDIA InfiniBand documentation |
| NVIDIA Networking | ConnectX / Spectrum / BlueField / DOCA docs |
| GPUDirect | NVIDIA GPUDirect documentation |
| NCCL | NVIDIA NCCL User Guide |
| Distributed Training | PyTorch Distributed documentation |
| Containers | Docker documentation |
| GPU Containers | NVIDIA Container Toolkit |
| Kubernetes | Kubernetes official documentation |
| GPU Kubernetes | Kubernetes GPU scheduling + NVIDIA device plugin |
| GPU Operator | NVIDIA GPU Operator documentation |
| TensorRT | NVIDIA TensorRT documentation |
| Triton | NVIDIA Triton documentation |
| GPU Monitoring | NVIDIA DCGM documentation |
| Metrics | Prometheus documentation |
| Dashboards | Grafana documentation |
| Cloud | Official cloud-provider documentation |
| NVIDIA Enterprise | NVIDIA AI Enterprise documentation |
| NGC | NVIDIA NGC documentation |

---

# 📦 Artifact Decision Tree

```text
I LEARNED SOMETHING
       ↓
Is it primarily conceptual?
       ↓
      YES
       ↓
📘 DOCUMENT


Did I write executable implementation?
       ↓
      YES
       ↓
💻 CODE


Did I configure/test infrastructure?
       ↓
      YES
       ↓
🧪 LAB


Did I measure performance?
       ↓
      YES
       ↓
📊 BENCHMARK


Did I integrate multiple systems?
       ↓
      YES
       ↓
🏗️ PROJECT


Did I document repeatable diagnosis/recovery?
       ↓
      YES
       ↓
🛠️ RUNBOOK
```

---

# 🗂️ Long-Term Repository Structure

Create folders only when actual content exists.

```text
InfraNerve/
│
├── README.md
├── ROADMAP.md
│
├── Docs/
│   ├── Foundations/
│   ├── Computer-Architecture/
│   ├── NVIDIA-GPU-CUDA/
│   ├── Memory-Storage/
│   ├── AI-Networking/
│   ├── Distributed-AI/
│   ├── AI-Servers-Clusters/
│   ├── Containers-Kubernetes/
│   ├── Cloud-NVIDIA-Enterprise/
│   ├── Deployment-Inference/
│   ├── Performance-Operations/
│   ├── Security-Troubleshooting/
│   └── AI-Factories-Data-Centers/
│
├── Code/
├── Labs/
├── Benchmarks/
├── Projects/
└── Runbooks/
```

---

# 🔬 Standard Lab Template

Every future InfraNerve lab should answer:

```text
WHAT AM I TESTING?
       ↓
WHERE AM I RUNNING IT?
       ↓
WHAT DO I NEED?
       ↓
WHAT COMMANDS / CONFIGURATION DO I USE?
       ↓
WHAT SHOULD I OBSERVE?
       ↓
WHAT SHOULD I MEASURE?
       ↓
WHAT QUESTIONS SHOULD I ANSWER?
       ↓
WHY DOES THIS MATTER IN PRODUCTION?
       ↓
WHAT ARTIFACT DO I PUBLISH?
```

A lab is **not complete** merely because commands were executed.

A lab is complete when I can explain:

1. what happened,
2. why it happened,
3. what the measurements mean,
4. how the result relates to infrastructure,
5. and what I would investigate if the result were abnormal.

---

# 🧠 Learning Philosophy

The objective is not:

> “I read about RDMA.”

It is:

> “I understand why RDMA exists, can explain its memory and queue model, know how to inspect RDMA-capable infrastructure, can benchmark it when hardware is available, and know which metrics matter.”

The objective is not:

> “I learned CUDA.”

It is:

> “I wrote CUDA kernels, profiled them, identified bottlenecks, changed the implementation, and measured whether performance improved.”

The objective is not:

> “I learned Kubernetes GPUs.”

It is:

> “I understand how GPUs become Kubernetes resources, scheduled a GPU workload, intentionally created an unschedulable workload, inspected scheduler events, and diagnosed the cause.”

---

# 🏁 Long-Term Outcome

InfraNerve should progressively demonstrate:

- 📘 infrastructure knowledge
- 🐧 Linux operational skills
- 💻 CUDA programming
- 🧪 GPU experimentation
- 🌐 networking investigation
- 📊 performance measurement
- 🔗 distributed GPU understanding
- 📦 GPU containerization
- ☸️ Kubernetes GPU operations
- 🟢 NVIDIA infrastructure knowledge
- 🚀 inference engineering
- 📡 observability
- 🔐 infrastructure security
- 🛠️ troubleshooting
- 🏗️ system design
- 🏭 AI factory architecture
- ⚙️ production-oriented operations

The progression is:

`UNDERSTAND → CONFIGURE → IMPLEMENT → EXPERIMENT → MEASURE → DIAGNOSE → OPERATE`

---

<div align="center">

### ⚡ InfraNerve

`NVIDIA AI INFRASTRUCTURE × GENERAL AI INFRASTRUCTURE`

**Learning the systems that make AI run.**

`LEARN THE SYSTEM → BUILD THE SYSTEM → MEASURE THE SYSTEM → OPERATE THE SYSTEM`

</div>
