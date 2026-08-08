# BNBC 2020 — AI-Ready Knowledge Base

> **A structured, clause-level knowledge base of the Bangladesh National Building Code (BNBC) 2020, designed for engineers, researchers, developers, and AI/RAG systems.**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![BNBC](https://img.shields.io/badge/Standard-BNBC%202020-orange.svg)](https://hbri.gov.bd/)

---

## Overview

**`bnbc-2020-database`** is an AI-oriented, structured representation of the **Bangladesh National Building Code (BNBC) 2020**.

Instead of treating the code as a single large document, this repository organizes BNBC 2020 into a navigable virtual file system containing individual clauses, structured data, procedural diagrams, and extracted figures.

The goal is to make the codebase easier to:

* 🔎 Search and navigate
* 🤖 Retrieve with RAG/LLM systems
* 🧠 Use as an AI engineering knowledge base
* 🏗️ Integrate into engineering applications
* 📚 Reference at clause level
* 🔗 Connect engineering questions to the relevant BNBC provisions

> **This is not a conventional database. It is a structured knowledge layer designed to make BNBC 2020 machine-readable and retrievable.**

---

## Repository Structure

The repository follows the major divisions of BNBC 2020:

| Part                                        | Domain                                                                 |
| ------------------------------------------- | ---------------------------------------------------------------------- |
| `Part_01_Scope_and_Definitions`             | Scope, definitions, terminology & units                                |
| `Part_02_Administration_and_Enforcement`    | Permits, administration, inspections & enforcement                     |
| `Part_03_General_Building_Requirements`     | Occupancy, space requirements & general provisions                     |
| `Part_04_Fire_Protection`                   | Fire safety, egress, detection & protection                            |
| `Part_05_Building_Materials`                | Concrete, steel, masonry, timber & materials                           |
| `Part_06_Structural_Design`                 | Loads, seismic, wind, concrete, steel, foundations & structural design |
| `Part_07_Construction_Practices_and_Safety` | Construction practices, site safety & quality control                  |
| `Part_08_Building_Services`                 | MEP, HVAC, plumbing, electrical & lifts                                |
| `Part_09_Alteration_and_Addition`           | Existing buildings, alterations & additions                            |
| `Part_10_Signs_and_Outdoor_Display`         | Signs, billboards & outdoor displays                                   |

The repository also includes a central [`MAP.md`](MAP.md) that provides routing logic for determining which BNBC Part should handle a particular engineering query.

---

## AI / RAG Architecture

The repository is designed around a simple principle:

**User Question → Domain Detection → Part Routing → Clause Retrieval → Context → Answer**

For example:

```text
"What is the required design load for a residential floor?"

        ↓

Structural Engineering Query

        ↓

Part_06_Structural_Design

        ↓

CLAUSE_ROUTER.md

        ↓

Relevant Clause

        ↓

Clause-level Markdown / JSON / Figures

        ↓

LLM / RAG Application
```

This makes the repository suitable as a retrieval layer for engineering-focused AI systems.

---

## Internal Data Structure

Each BNBC Part is organized using several complementary representations:

```text
Part_XX/
│
├── CLAUSE_ROUTER.md
│
├── clauses/
│   ├── clause_01.md
│   ├── clause_02.md
│   └── ...
│
├── json/
│   ├── ...
│
├── mmd/
│   ├── ...
│
└── webp/
    ├── ...
```

### `CLAUSE_ROUTER.md`

Provides a semantic routing layer between real-world engineering questions and specific BNBC clauses.

### `clauses/`

Contains individual Markdown representations of BNBC sections and clauses.

This allows retrieval systems to work with smaller, more relevant context rather than loading an entire code document.

### `json/`

Contains structured/tabular representations extracted from the code.

This can be useful for programmatic processing, filtering, calculations, and future engineering software integrations.

### `mmd/`

Contains **Mermaid.js** representations of procedural and logical relationships.

These can be rendered into diagrams or used as machine-readable representations of decision processes.

### `webp/`

Contains extracted diagrams and graphical material represented in WebP format.

---

## Why This Structure?

Large engineering codes are difficult for conventional LLM applications to consume effectively.

A single document can introduce:

* excessive context
* irrelevant clauses
* difficult citation
* poor retrieval precision
* fragmented tables
* diagrams that are disconnected from their clauses

This repository attempts to solve that problem by decomposing the code into **small, addressable engineering knowledge units**.

Instead of asking an AI system to search an entire code, a retrieval pipeline can first determine the engineering domain and then retrieve only the relevant section.

---

## Example Routing

### Structural Engineering

```text
Question:
"What loads should be considered in the design of a building?"

        ↓

Part 06 — Structural Design

        ↓

Load-related clauses
```

### Fire Safety

```text
Question:
"What are the requirements for means of egress?"

        ↓

Part 04 — Fire Protection

        ↓

Relevant egress clauses
```

### Building Services

```text
Question:
"What BNBC provisions apply to building plumbing?"

        ↓

Part 08 — Building Services

        ↓

Relevant plumbing clauses
```

The complete routing logic is maintained in [`MAP.md`](MAP.md).

---

## Intended Uses

This repository can serve as a foundation for:

* **RAG systems**
* Engineering AI assistants
* BNBC search engines
* Clause recommendation systems
* Code-compliance assistants
* Engineering research
* BNBC-aware chatbots
* Structured engineering databases
* Document retrieval pipelines
* Future BIM / AEC software integrations

---

## Important Disclaimer

This repository is intended as a **research, educational, data-structuring, and software-development resource**.

It should **not be treated as a substitute for the official Bangladesh National Building Code, applicable laws, regulations, professional engineering judgment, or review by the relevant authority**.

Always verify critical design and compliance decisions against the **official/current BNBC documentation and applicable requirements**.

---

## Contributing

Contributions are welcome.

Potential areas for improvement include:

* Clause metadata
* Improved semantic routing
* Cross-references between clauses
* Better table extraction
* JSON schema normalization
* Additional diagrams
* Search indexes
* Embedding/RAG pipelines
* Automated validation
* Engineering-domain tagging
* Citation and source tracking

If you find an error or inconsistency, please open an issue with:

1. The affected Part
2. Clause/file name
3. Description of the issue
4. Suggested correction
5. Source/reference, where available

---

## Roadmap

Possible future development:

* [ ] Unified BNBC clause metadata schema
* [ ] Automated embeddings
* [ ] Vector database integration
* [ ] Semantic search
* [ ] Hybrid BM25 + vector retrieval
* [ ] Clause-to-clause cross-reference graph
* [ ] Engineering-domain ontology
* [ ] Automated citation generation
* [ ] BNBC RAG reference implementation
* [ ] API for clause retrieval
* [ ] Web-based BNBC search interface
* [ ] BIM/engineering-software integration

---

## License

This repository is released under the **MIT License**. See [`LICENSE`](LICENSE) for details.

---

## Author

**Anway Dipta Paul**

GitHub: [@AnwayDiptaPaul](https://github.com/AnwayDiptaPaul)

---

### Citation

If you use this repository in research, software, or an AI system, please reference the repository:

```text
Anway Dipta Paul.
BNBC 2020 — AI-Ready Knowledge Base.
GitHub: AnwayDiptaPaul/bnbc-2020-database.
```

---

> **BNBC 2020, structured for machines — so engineers can build better tools.**
