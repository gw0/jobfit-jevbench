---
company: Fireworks AI
title: Member of Technical Staff, Systems Infrastructure (2026 PhD New Grad)
location: San Mateo
url: https://jobs.ashbyhq.com/fireworks/ad58a098-ef75-4a4b-8475-55c2653213ef
posted_at: 2026-09-08
---

**About Us:**
-------------

Fireworks is the platform for specialized intelligence, enabling companies to build, train, and serve AI models tailored to their own data, workflows, and products. Founded by the team behind PyTorch and backed by AMD, Atreides, Benchmark Capital, Index Ventures, Lightspeed, NVIDIA, Sequoia Capital, and TCV, Fireworks powers production AI with hundreds of state-of-the-art open models across text, image, embedding, audio, and multimodal workloads. Today, Fireworks is a Series D company valued at $17.5 billion, bringing together an ambitious, collaborative team that's building the future of enterprise AI.

**THE ROLE:**

This role is designed for systems researchers finishing their PhD who want to see their ideas run on real fleets at real scale. As a Member of Technical Staff on the Systems Infrastructure team, you'll design and build the substrate underneath Fireworks — the schedulers, storage systems, and networks that keep tens of thousands of accelerators busy and inference latency low.

The problems here are the ones your dissertation probably touched: how to place compute-intensive jobs across heterogeneous hardware without stranding capacity, how to move model weights and KV cache fast enough that they never become the bottleneck, and how to keep a datacenter network saturated with collective traffic without collapsing tail latency. The difference is that here you get a production fleet as your testbed and your work ships.

You'll be paired with a senior engineer as a mentor and given a real problem from day one. Start dates are flexible around thesis defense timelines.

**AREAS OF FOCUS**

We're hiring across three areas — depth in any one of them is what we're looking for, not all three:

* **Scheduling & resource management:** GPU job scheduling and scheduling of compute-intensive workloads across heterogeneous hardware; multi-tenant isolation, fair sharing and preemption, topology- and locality-aware placement, autoscaling, fleet utilization, and capacity planning across accelerator generations and vendors
* **Distributed storage & caching:** High-performance distributed storage and caching for model weights, checkpoints, datasets, and KV cache; tiering across memory, local NVMe and object storage, cache admission and eviction policy, consistency, and fast cold-start and weight-loading paths
* **Datacenter networking:** High-performance DC networks for AI workloads; RDMA/RoCE and InfiniBand, collective communication (NCCL/RCCL) performance, congestion control, topology design, load balancing, and tail-latency and reliability engineering at fleet scale

**KEY RESPONSIBILITIES**

* Design, build, and operate core infrastructure systems for large-scale training and inference
* Model and measure system behavior — build the benchmarks, traces, and simulators needed to reason about scheduling, caching, and network performance before committing to a design
* Identify bottlenecks across the stack, from kernel and driver to scheduler policy, and drive them out with data
* Turn research ideas into production systems that hold up under real workloads, real failures, and real customers
* Work closely with the research and inference teams so that infrastructure design and model design inform each other
* Contribute to the team's technical direction by tracking emerging hardware, interconnects, and systems research

**MINIMUM QUALIFICATIONS:**

* PhD completed within the last 6 months, or expected completion by December 2026, in Computer Science, Computer Engineering, Electrical Engineering, or a similar field
* Research background in one or more of: distributed systems, operating systems, scheduling and resource management, storage systems, computer networks, computer architecture, or high-performance computing
* Depth in at least one of the three focus areas above, demonstrated through your dissertation, publications, or systems you've built
* Strong systems programming skills in C/C++, Rust, Go, or a similar language, plus working proficiency in Python
* Experience building and evaluating real systems — not only simulation — and reasoning rigorously about performance with measurements
* Ability to communicate systems design and results clearly to audiences with different backgrounds

**PREFERRED QUALIFICATIONS:**

* First-authored publications at top-tier systems or networking venues (OSDI, SOSP, NSDI, EuroSys, SIGCOMM, ATC, FAST, ASPLOS, MLSys, SC, or similar)
* Industry internships in infrastructure, cloud, or HPC, or meaningful open-source contributions to systems projects (Kubernetes, Ray, Slurm, vLLM, NCCL, DPDK/SPDK, Ceph, or similar)
* Hands-on experience with GPU clusters, accelerator programming (CUDA, ROCm, Triton), or heterogeneous compute environments
* Experience with Kubernetes and cloud infrastructure, or with operating multi-tenant clusters in production
* Experience with performance profiling and debugging in distributed environments
* Research or engineering experience demonstrated via grants, fellowships, patents, or systems competitions

**Why Fireworks?**
------------------

* Solve Hard Problems: Tackle challenges at the forefront of AI infrastructure, from low-latency inference to scalable model serving.
* Build What’s Next: Work with bleeding-edge technology that impacts how businesses and developers harness AI globally.
* Ownership & Impact: Join a fast-growing, passionate team where your work directly shapes the future of AI—no bureaucracy, just results.
* Learn from the Best: Collaborate with world-class engineers and AI researchers who thrive on curiosity and innovation.

*Fireworks AI is an equal-opportunity employer. We celebrate diversity and are committed to creating an inclusive environment for all innovators.*
