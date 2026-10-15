# Devang Patil

**Systems Architecture &middot; Linux Internals &middot; Autonomous AI Engines**

Undergraduate CS researcher and systems engineer. I focus on low-latency infrastructure, Linux kernel pressure telemetry, offline causal diagnostics, and deterministic agentic systems.

[GitHub](https://github.com/Dev-angPatil) &middot; [Email](mailto:officialdevangpatil@gmail.com) &middot; [LinkedIn](https://www.linkedin.com/in/devangpatil/)

---

## ⚡ Flagship System: [ops-assistant](https://github.com/Dev-angPatil/ops-assistant)

> **Sub-50ms Incident Root-Cause Isolation Engine for Production Linux**

A high-performance operations copilot engineered for air-gapped, mission-critical Linux environments. Rather than querying non-deterministic cloud LLMs, `ops-assistant` synthesizes kernel-level Pressure Stall Information (PSI) telemetry with axiomatic causality directed acyclic graphs (DAGs) to isolate system bottlenecks in real time.

### Architectural Highlights

- **Kernel PSI Telemetry Ingestion:** Directly ingests `/proc/pressure/{cpu,memory,io}` and cgroups v2 metrics, capturing true resource contention without user-space polling overhead.
- **Axiomatic Causality DAGs:** Evaluates incidents across a 16-class Linux failure taxonomy (I/O starvation, memory thrashing, cgroup throttling, file descriptor exhaustion) to pinpoint exact fault origins.
- **100% Air-Gapped & Zero-Cloud:** Operates entirely on-box with zero API keys or external data egress, guaranteeing that sensitive production logs and operational telemetry never leave the host.
- **Ephemeral Namespace Sandboxing:** Isolates automated diagnostic probes and proposed remediation routines inside transient Linux namespaces (`unshare`), mitigating operator risk.

### Empirical Benchmarks

| Metric | Measured Performance | Specification |
| :--- | :--- | :--- |
| **Root-Cause Isolation** | **`45.2 ms`** | Sub-50ms deterministic triage |
| **Resident Memory** | **`< 16 MB`** peak RAM | Negligible footprint daemon |
| **Verification Suite** | **`353 / 353`** passing | Comprehensive unit, kernel & regression tests |
| **External Dependencies** | **`0`** cloud APIs | Fully autonomous on-box runtime |
| **Distribution Matrix** | **`6`** Linux distros | Debian, RHEL, Arch, Alpine, SUSE, BOSS |

```bash
# Clone & run locally in an air-gapped environment
git clone https://github.com/Dev-angPatil/ops-assistant.git
cd ops-assistant && ./install.sh
```

---

## Selected Systems & Research

- **[Signalpost](https://github.com/Dev-angPatil/signalpost)** &mdash; Autonomous corporate intelligence agent built for the Builderr Signalpost Challenge, featuring official Norwegian public registry grounding, cryptographic lineage verification, and strict anti-contamination gates.
- **[IntentStore](https://github.com/Dev-angPatil/SSM)** &mdash; Semantic storage intelligence engine utilizing zero-copy reflink cloning (`ioctl FICLONE`), high-throughput inode crawling (>45k/s), and Holt-Winters time-series archival planning.
- **[Research Publications](https://github.com/Dev-angPatil/Research_Papers)** &mdash; Consolidated portfolio of 5 IEEE-format research papers spanning combinatorial packing, agrometeorology, web security, and UAV swarm APF navigation.

---

<p align="center">
  <sub>Engineered with restraint. Hosted on Linux.</sub>
</p>