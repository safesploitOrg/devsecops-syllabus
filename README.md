# DevSecOps Syllabus

This repository documents a **deliberately designed DevSecOps syllabus** created to transition from infrastructure (Ops) into **secure platform and DevSecOps engineering**.

It reflects a **long-term, structured progression** rather than ad-hoc learning:  
covering delivery pipelines, infrastructure, cloud, containers, identity, monitoring, compliance, and incident response — with **security treated as a system property**, not a final gate.

The emphasis throughout is on **execution, failure modes, and operational realism**, not certifications, tool collecting, or theoretical coverage.

---

## Philosophy

This syllabus is built on a few core beliefs:

- **DevSecOps is an operating model**, not a toolchain
- **Security must be designed in**, not bolted on
- **Automation reduces risk only when it is intentional and observable**
- **Incidents are inevitable** — systems should assume failure
- **Compliance must reflect reality**, not audit theatre

Learning is treated the same way infrastructure is treated:  
structured, iterative, and grounded in real constraints.

---

## Scope and Rigour

This is **not a lightweight overview**.

The syllabus represents a **long-term, disciplined progression** that includes:

- Defined modules with clear responsibility domains  
- Hands-on implementation rather than passive study  
- Iterative reinforcement (e.g. CI → secure CI → containerised delivery → detection → response)  
- Explicit focus on trade-offs, limitations, and failure scenarios  
- Portfolio-grade artefacts produced as outcomes  

Each module is designed to result in **something concrete**:
a working pipeline, a hardened system, a documented design decision, or an operational playbook.


### What This Is

This repository is:

- A deliberately designed **DevSecOps syllabus**, structured into clear modules  
- Grounded in **production infrastructure and security experience**  
- Focused on **automation, auditability, and failure modes**  
- Aligned with real frameworks such as **NIST**, **Cyber Essentials+**, and **NHS Digital**  
- Backed by **hands-on projects** implemented in homelab and cloud environments  

The structure is intended to be **followable by others**, while remaining honest about trade-offs and complexity.


### What This Is Not

This repository is **not**:

- A beginner tutorial or bootcamp  
- A certification cram guide  
- A collection of untested notes or copy-pasted commands  
- A “DevSecOps tools list”  

If you’re looking for quick wins or surface-level coverage, this repo is not for you.

---


## Syllabus Structure

The syllabus is organised into **module-based directories**, each representing a core DevSecOps responsibility area.

At a high level:

- **Modules 01–03** establish DevSecOps, DevOps, and security foundations  
- **Modules 04–06** focus on platforms, pipelines, and infrastructure security  
- **Modules 07–10** address compliance, threat modelling, containers, and incident response  
- **Modules 11–13** focus on professional practice, hands-on projects, and portfolio positioning  

Each module contains its own `README.md` describing:
- Purpose and scope  
- Key concepts and risks addressed  
- Expected outcomes and artefacts  

Modules are intentionally ordered, but can be revisited as understanding deepens.

---

## Execution and Practical Work

Execution is a first-class concern.

Hands-on work appears in two forms:

- **Module-scoped practical work** under `module-12-practical-projects/`  
- **Standalone end-to-end projects** under `projects/`  

Examples of execution include:
- **CI/CD pipelines with integrated SAST/DAST** to surface risk early without blocking delivery
- **IaC with secure state handling** to reduce drift and privilege sprawl
- **Hardened containerised workloads and Kubernetes security controls**
- **Secrets and identity management** using modern tooling and patterns, minimising long-lived credentials and enforcing least-privilege access across systems
- **Monitoring, alerting, and detection pipelines** designed for signal over noise, prioritising actionable alerts and reducing operator fatigue during incidents
- **Incident response playbooks and post-incident analysis**, treating failures as expected events and feeding lessons back into system design and automation

Perfection is not the goal — **clarity of design decisions is**.

---


## Intended Audience

This repository is aimed at:

- Infrastructure / System engineers moving toward **DevSecOps or Platform roles**  
- DevOps engineers looking to deepen **security and operational maturity**  
- Security engineers seeking stronger **infrastructure and delivery context**  

It assumes familiarity with Linux, networking, and basic automation concepts.

---

## Status and Evolution

This repository is actively developed.

- The **structure is intentional and stable**  
- Depth increases as modules and projects are refined  
- Earlier modules may be revisited as later insights emerge  

The goal is not completion for its own sake, but **durable understanding**.


---

## Licence

This repository is shared for learning and reference purposes.  
Unless otherwise stated, content is provided under an open licence for personal and educational use.
