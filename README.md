# Scott Jellen  
### Independent Researcher · Protocol Designer · Infrastructure Systems

I design protocol-oriented research, reference infrastructure, and institutional frameworks for representing rights, incentives, access, and coordination in complex systems.

This GitHub profile serves as the public development index for **Jellen Protocol Lab**, an independent research initiative focused on protocol design, rights infrastructure, institutional systems, and public-facing technical artifacts.

Authoritative specifications, schemas, registries, reference tooling, and canonical research artifacts are developed and versioned openly, with explicit scope, lifecycle status, and archival discipline.

Primary development and canonical artifacts are maintained in the **`sjellen/protocols`** repository.

---

## 📡 Flagship Protocol: Universal Sports Graph (USG)

The **Universal Sports Graph (USG)** is a protocol stack for representing sports broadcast rights as structured, interoperable data.

USG defines a neutral, machine-readable layer for:

- rights definition and ownership  
- entitlement and access authorization  
- registry-backed auditability and settlement primitives  

The goal is to make sports rights **computable**, reducing ambiguity across leagues, distributors, platforms, regulators, and downstream systems.

---

## 📘 Normative Protocol Surface

The following documents define the **normative protocol surface** of USG.  
These are standards-oriented specifications. Whitepapers and briefs elsewhere in the canon are interpretive, exploratory, or contextual.

- **The Universal Sports Graph — Blueprint Edition**  
  DOI-backed whitepaper defining the problem space, protocol goals, and architectural framing.

- **RFC 0001 — The Universal Sports Graph**  
  Core rights graph model, access surface, and clearinghouse abstraction.

- **RFC 0002 — USG Entitlement Token Profile**  
  Standards-track specification defining entitlement tokens, required claims, validation rules, security properties, and interoperability expectations.

- **RFC 0003 — USG Registry Architecture**  
  Standards-track specification defining:
  - canonical registry object models  
  - identifier and namespace semantics  
  - lifecycle and mutation rules  
  - canonical JSON forms and digest requirements  
  - deterministic index structures  
  - federation and multi-authority constraints  

Together, RFCs **0001–0003** define the minimum viable USG protocol stack:

**rights graph → entitlement enforcement → authoritative registry substrate**

---

## 🗂 Registry & Schemas

The repository includes a versioned reference registry and associated schemas.

**Authoritative artifacts**
- Registry object schemas
- Entitlement token and settlement record schemas
- Deterministic index files and registry metadata
- Canonical identifiers and digest conventions

**Reference tooling**
- Schema validation utilities  
- Integrity and digest checks  
- Index verification helpers  

Tooling exists to demonstrate protocol behavior, not to function as production infrastructure.

---

## 🔎 Resolver Layer

A minimal, read-only resolver layer provides stable lookup paths for USG artifacts without introducing service guarantees.

The resolver exists to:

- make canonical registry versions referenceable  
- support `latest` and version-pinned resolution  
- enable citation, inspection, and tooling integration  

It is designed for referenceability and inspection — not orchestration.

The resolver is interface-only:

- no SLAs  
- no business logic  
- no mutation authority  

Authoritative state remains in the registry.

---

## 🧪 Current Focus

Current work is focused on turning research artifacts into structured protocol and institutional systems:

- USG registry, resolver, and federation models
- standards-oriented governance and compliance extensions
- settlement and clearinghouse formalization
- institutional continuity mechanisms
- labor, retirement, and public-system transition frameworks
- operational simulations for policy and infrastructure proposals

---

## 🔬 Scope & Status

**Stable / Frozen**
- RFCs 0001–0003  
- Registry schema set  
- Canonical index and digest rules  

**Active**
- Governance and compliance extensions  
- Settlement and clearinghouse formalization  
- Registry federation and multi-authority models  
- Applied institutional frameworks  

**Explicitly Out of Scope**
- Consumer applications  
- Proprietary platform integrations  
- League-specific business logic  

---

## 📚 Research Papers

Whitepapers exploring rights structures, incentives, labor systems, public infrastructure, and institutional design across multiple sectors.

Selected works:

- *The Universal Sports Graph — Blueprint Edition*
- *The Shutdown Stabilizer*
- *The Shorter Working Life*
- *The Shadow Subscription*
- *The Content Layer*
- *The Sports Spin-Off*
- *Less Than Net Zero*

Archive:  
https://scottjellen.com/whitepapers

---

## 📝 Briefs

Concise research briefs derived from larger papers and protocol work, focused on clarifying structure, incentives, implementation patterns, or operational implications.

Archive:  
https://scottjellen.com/briefs

---

## 🧭 Research Principles

- clarity over scale  
- infrastructure before applications  
- protocols before platforms  
- versioning over polish  
- publish early, freeze deliberately  
- mechanisms before narratives  

Systems are treated as structures, not products:

**rights → access → incentives → outcomes**

---

## 📬 Contact

For critique, collaboration, or research discussion:  
https://scottjellen.com/contact  

Portfolio: https://scottjellen.com  
LinkedIn: https://www.linkedin.com/in/sjellen/