# Scott Jellen  
### Independent Researcher · Protocol Design · Rights Modeling

I design standards-oriented protocols and reference infrastructure for representing rights, incentives, and interoperability in digital and institutional systems.

This GitHub profile serves as an index and entry point for my protocol-oriented research. Authoritative specifications, schemas, registries, and reference tooling are developed and versioned openly, with explicit scope, lifecycle status, and archival discipline.

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

## 🗂 Registry & Schemas (v0.1.1)

The repository includes a versioned reference registry (v0.1.1) and associated schemas.

**Authoritative artifacts**
- Registry object schemas (event, league, team, venue, broadcaster, rights bundle)
- Entitlement token and settlement record schemas
- Deterministic index files and registry metadata
- Canonical identifiers and digest conventions

**Reference tooling (illustrative, non-production)**
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

## 🔬 Scope & Status

**Stable / Frozen**
- RFCs 0001–0003  
- Registry schema set v0.1.1  
- Canonical index and digest rules  

**Active (Standards-Oriented Development)**
- Governance and compliance extensions  
- Settlement and clearinghouse formalization  
- Registry federation and multi-authority models  

**Explicitly Out of Scope**
- Consumer applications  
- Proprietary platform integrations  
- League-specific business logic  

---

## 📚 Research Papers

Whitepapers exploring rights structures, incentives, and system design across multiple sectors.

Selected works:
- *The Sports Spin-Off*  
- *The Content Layer*  
- *The Shadow Subscription*  

Archive:  
https://scottjellen.com/whitepapers

---

## 📝 Briefs

Concise research briefs derived from larger papers and protocol work, focused on clarifying structure, incentives, or implementation patterns.

Archive:  
https://scottjellen.com/briefs

---

## 🧭 Research Principles

- clarity over scale  
- infrastructure before applications  
- protocols before platforms  
- versioning over polish  
- publish early, freeze deliberately  

Systems are treated as structures, not products:

**rights → access → incentives → outcomes**

---

## 📬 Contact

For critique, collaboration, or research discussion:  
https://scottjellen.com/contact  

Portfolio: https://scottjellen.com  
LinkedIn: https://www.linkedin.com/in/sjellen/