# Scott Jellen  
### Independent Researcher · Protocol Design · Rights Modeling

I study how rights, incentives, and system architecture can be represented clearly through **standards-style protocols**, **schemas**, and **reference models**.

This repository is the **canonical working tree** for my protocol-oriented research, including RFC-style specifications, schema drafts, registry artifacts, and supporting examples.  
All work is published with transparent versioning and explicit scope.

---

## 📡 Flagship Work: Universal Sports Graph (USG)

The **Universal Sports Graph (USG)** is an emerging protocol for representing sports broadcast rights as structured, interoperable data.

USG defines a neutral, machine-readable layer for:
- rights registration  
- access authorization  
- settlement and auditability  

The goal is to clarify incentives across leagues, platforms, distributors, and audiences by making rights computable.

### Published Artifacts
- **The Universal Sports Graph — Blueprint Edition** (DOI-backed whitepaper)  
- **RFC 0001 — The Universal Sports Graph**  
  Defines the core rights graph, access surface, and clearinghouse model.
- **RFC 0002 — USG Entitlement Token Profile**  
  Standards-track specification defining tokenized access, required claims, validation rules, security properties, and interoperability expectations.
- **RFC 0003 — USG Registry Architecture**  
  Standards-track specification defining canonical registry object models, identifier semantics, versioning and lifecycle rules, canonical JSON and digest requirements, index structures, federation and authority rules, and validation requirements.

Together, RFCs 0001–0003 define the **minimum viable USG protocol stack**:
**rights graph → access enforcement → authoritative data substrate**.

### Schemas & Reference Artifacts
- Registry object schemas  
- Event, league, team, venue, broadcaster, and rights-bundle definitions  
- Entitlement token schema  
- Settlement record schema  
- Deterministic index files and registry metadata  
- Validation and integrity-check tooling (non-production reference)

### In Development
- Governance and compliance RFCs  
- Settlement and clearinghouse extensions  
- Registry federation and multi-authority models  
- Reference implementations and validation tooling (illustrative only)

Repository: https://github.com/SJellen/protocols

---

## 🗂 Registry & Protocol Direction

The registry layer formalizes **authoritative identifiers**, **object semantics**, and **validation rules** for USG-compliant data.

Rather than functioning as a simple index, the registry serves as a **reference substrate**:
- enforcing stable identifiers  
- preventing semantic drift  
- enabling auditability and reproducible validation  
- supporting downstream interoperability

The reference registry is intentionally conservative and illustrative, designed to anchor discussion, critique, and early pilot implementations.

---

## 📚 Research Papers

A catalog of whitepapers exploring rights structures, incentives, and system design across multiple sectors.

Selected works:
- **The Universal Sports Graph — Blueprint Edition**  
- **The Sports Spin-Off**  
- **The Content Layer**  
- **The Shadow Subscription**

Full archive:  
https://scottjellen.com/whitepapers

---

## 📝 Briefs

Concise research briefs derived from larger papers and protocol work.  
Intended to clarify structure, incentives, or implementation patterns without full specification weight.

Archive:  
https://scottjellen.com/briefs

---

## 🧭 Research Approach

- clarity over scale  
- versioning over polish  
- publish early, refine in public  
- treat systems as structures: **rights → access → incentives → outcomes**

---

## 📬 Contact

For questions, critique, or research discussion:  
https://scottjellen.com/contact

Portfolio: https://scottjellen.com  
LinkedIn: https://www.linkedin.com/in/sjellen/
