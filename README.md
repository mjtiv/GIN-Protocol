# GIN-Protocol

**Note:** This protocol is a slightly modified version of the [GPT-VINs-Protocol](https://github.com/mjtiv/gpt-vins-protocol), where the nomenclature of VIN for GPTs has been renamed to GIN. To preserve the historical record and show evolution, both repositories will remain available.

## 🔍 Why We Need Tagged GPTs — Now

If you ask a GPT today:  
> *“What AI server are you running on? What version are you? Who issued you?”*  
It can’t answer.

- No persistent identity  
- No cluster fingerprint  
- No GPU execution hash  
- No infrastructure-bound metadata  

This creates a **compliance and security blind spot** — especially dangerous in regulated environments.

### 💡 Our Proposal:

> **No GPT should operate in regulated environments unless it carries a verifiable identity — a GIN for AI.**

The `.aix` protocol makes this possible:  
- Each agent is **tagged at runtime**  
- Identity is **cryptographically bound to execution**  
- Metadata includes: model version, deployment ID, GPU fingerprint, and timestamp  
- Logs can optionally be submitted to **public or private GIN registries**  

---

## ⚙️ What GIN Tagging Enables

- **Immediate traceback** of rogue or misbehaving agents  
- **Live audit logging** for compliance and infrastructure forensics  
- **Revocation at the hardware level** (PID/GPU-level shutdowns)  
- **Operational accountability** across critical sectors like finance, healthcare, and government  

---

## 🚫 Enforcement vs. Identity: What’s Public, What’s Protected

This repository shares **open protocol concepts only.**  
It does **not** include enforcement systems currently protected under U.S. provisional patents.

### ✅ Publicly Disclosed (CC BY-NC 4.0):
- The `.aix` file format  
- GIN schema and metadata structure  
- Guidance for basic GIN integration into LLM deployments  

### 🔐 Proprietary and Patent-Pending:

The following are **not open source** and require licensing:

- Pre-inference validation of `.aix` trust headers  
- GIN-based prompt rejection or sandbox escalation  
- Execution receipts and cryptographic binding  
- Forensic audit stubs and infrastructure fingerprinting  

These systems are covered by **U.S. Provisional Patent 4: GPT Security & Enforcement Layer**.

---

## 🕊️ Public Domain Declaration – GIN Tagging Concept

The **core idea** of GIN-tagged GPTs is released into the public domain.

> You are free to adopt, extend, or implement the **concept** of persistent, verifiable AI identity — no license or attribution required.

See [`LICENSE.txt`](LICENSE.txt) for full disclosure terms and scope boundaries.

---

## 📁 Related Repositories

- **`.aix` Task File Format** → [https://github.com/mjtiv/aix-file-format](https://github.com/mjtiv/aix-file-format)  
- **Runtime Enforcement Framework** → private repo (available upon licensing inquiry)  

---

## 📄 Licensing & Commercial Use

> 🚨 Enforcement tools described in related patents are **not included** in this repository. This repo is for the GIN identity tagging protocol only.

This repository uses a **dual release model**:  
- Protocol and educational materials: **Creative Commons Attribution–NonCommercial 4.0 (CC BY-NC 4.0)**  
- Enforcement mechanisms: **Patent-protected** — not licensed for commercial use without written agreement

> **No commercial rights are granted** for GIN-based enforcement, parsing, cryptographic receipt generation, or runtime identity tracing under this release.

This license applies only to the GIN tagging protocol and file format — **not** to execution control, validation infrastructure, or enforcement subsystems.

📬 For licensing access to enforcement components, forensic tracing, or pre-inference validation tooling, please contact: **mjt6ss@virginia.edu**

---

> © 2025 M. Joseph Tomlinson IV. Some rights reserved.
