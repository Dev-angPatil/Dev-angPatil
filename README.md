# Devang Patil

CS student building things that are actually useful.

[GitHub](https://github.com/Dev-angPatil) &middot; [Email](mailto:officialdevangpatil@gmail.com) &middot; [LinkedIn](https://www.linkedin.com/in/devangpatil/)

---

## Featured Project: [ops-assistant](https://github.com/Dev-angPatil/ops-assistant)

An AI Linux assistant that is better than normal LLMs or cloud APIs because it uses:

- **Kernel PSI Telemetry:** Directly ingests `/proc/pressure/{cpu,memory,io}` and cgroups v2 metrics instead of guessing from noisy text logs.
- **Causal Reasoning DAGs:** Traces root causes through an axiomatic failure taxonomy instead of hallucinating answers.
- **100% Offline & Air-Gapped:** Runs completely on-host with zero cloud keys, zero API latency, and zero production data leaving the machine.
- **Namespace Sandboxing:** Runs automated diagnostics and proposed fixes inside ephemeral Linux namespaces (`unshare`) so it never breaks production.

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
  <sub>Built with restraint. Hosted on Linux.</sub>
</p>