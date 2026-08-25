All nodes are now linked by strict contracts (provenance, validation, audit). qFoldIT is effectively transforming into an industrial standard for **Validated Scientific Gaming**.

These milestones reflect the evolution of the project from an academic experiment (Foldit) to an industrial pipeline for validating scientific tasks in a gaming format. In particular, the involvement of Baker and the Baker Lab team gives qFoldIT a direct "genetic" heritage from Foldit – it is not merely a recent development but a **continuation of an 18‑year history** of crowdsourced science. This significantly strengthens the legal foundation (class E1) and removes risks from imitators.

## 🏗 Platform Architecture (Current Status)

qFoldIT is built on a layered scheme "from science to game engine" with clear separation of responsibilities:

- **Science layer:**
- **Scientific Object Schema (SOS):** a unified schema for "scientific objects". Each object is a "brick" (1 object = 1 "LEGO‑block") with a defined shape and colour.
- **Scientific Knowledge Graph (SKG):** a graph that stores relationships between objects and experiments. Ensures immutability of models (SKG‑factor = 1.0).
- **Scientific Execution Model (SEM):** protocols and workflows for evaluation and optimisation. Breaks a scientific task into a sequence of atomic cycles (typically no more than 10 cycles). Essentially, this is a "computable model" for scientific validation.

- **Corporate pipeline (Mission/Control Plane):**
- **MCP Registry (Science Control mode):** a catalogue of trusted scientific engines and connectors that operate via the Model Context Protocol (MCP). Enforces a **Fail‑closed** policy: for example, OpenStructure (the scientific evaluation module) rejects invalid data and guarantees the identity of `referenceId`.
- **Trust / Provenance (Compliance):** the layer of trust and provenance tracking ("evidence discipline"). Stores IP contracts, change logs, digital signatures. As noted in the documentation, all integration with external IP (e.g., Rick&Morty in Fortnite) is handled within formal licensing agreements, and qFoldIT merely "translates" scientific data into code without importing third‑party artefacts.
- **Experience Compiler (Pattern→UAG):** the "mission compiler". It takes an abstract task pattern (scientific goal, constraints) and translates it into a **Universal Assembly Graph (UAG)** – a unified scene/level graph.

- **Interface layer:**
- **Universal World Interface (UWI):** an abstract API translator that, without loss of semantics, translates MCP commands into specific game‑engine calls (place entity, set property, run Verse script).
- **Engine Toolbelts (Runtime Adapters):** specialised tool sets for each engine:
  - **UEFN‑TOOLBELT:** integration with Fortnite/UEFN. Contains **358+ tools** in 55+ categories (Verse‑code generation, entity embedding, UI/VFX).
  - **UNITY‑TOOLBELT:** analogous set (105 tools).
  - **UNIGINE‑TOOLBELT:** (84 tools).
  - **WEB‑TOOLBELT:** browser engine based on Three.js + Rapier.js + WebMCP, which consumes the same UAG and MCP servers. It does not perform its own computations: it fully shares the scientific results and guarantees full parity with the other platforms.
In total **547+ tools** for the editor side, plus a web runtime (see "What is already done").

- **AI / Agent layers:**
- **Model Context Protocol (MCP):** an open standard for communication of AI agents. Integrated into UEFN (Epic announced the built‑in MCP server in August 2026), allowing agents (Claude Code, Codex, Cursor, etc.) to directly control scenes and code. In qFoldIT, MCP acts as the "conductor" – choosing camera angles, presentation tempo, and the sequence of scientific evaluation steps.
- **Scientific agents:** for example, Anthropic Claude Science is considered a target "cartridge" for high‑level orchestration of computations (see the experiments with protein design).

- **Execution and integration:**
- **OpenStructure (on‑premise):** the closed‑source core for evaluating model quality (LDDT, QS‑score, etc.). Effectively replaces the "classical" Rosetta in‑chain and provides the E1 validation loop. OpenStructure is an open‑source environment for structural modelling, but in qFoldIT it is deployed as an on‑premise backend with verification of all mandatory fields and consistencies.
- **CAMEO / Cameo‑Realtime‑Validation:** pipelines for managing the experimental part and cross‑matching results from different environments (e.g., physical equipment or external simulators). They provide additional layers of verification and reinforce the mission roadmap.
- **Game‑MCP, QubitFold‑MCP, Atomic‑MCP, Protein‑Design‑MCP, etc.:** internal servers/containers that assemble specific runtime environments (e.g., virtual laboratories, nanomachine simulation, chemical synthesis, etc.).

- **Gamification and "pop‑culture":**
qFoldIT deliberately decouples *gameplay* from *science*. The gamification layer is intended to attract players (e.g., through familiar images like LEGO, comics, quests). At the same time, all game mechanics remain deterministic and easily translatable into science: real constructive actions (placing "blocks"‑amino acids, setting bonds and conformations) are immediately mapped to the Scientific Object Schema. As emphasised in the documentation, qFoldIT operates **only as a "structural layer"** – it generates Verse code and objects, but does not modify third‑party storylines or IP. This ensures content "sovereignty": for example, the use of licensed characters inside Fortnite is handled under formal agreements, and qFoldIT merely provides automation at the structural level.

In summary, the current architecture of qFoldIT appears as a **unified ecosystem with closed loops**: from mission definition to obtaining a verified scientific result with full traceability. All components (UAG, MCP, UWI, Toolbelts, SEM/SOS/SKG, OpenStructure, etc.) are clearly integrated under a single architectural contract. For example, the entire scene is described by a **Universal Assembly Graph (UAG)**, which is then transformed through the corresponding Toolbelt into a native game (Fortnite, Unity, Unigine, or web), and the computation results are passed back to the **Evidence Registry** while preserving mission metadata, validator version, and so on.
