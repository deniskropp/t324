# t324 — Unified MetaForge and OCS Documentation Repository

Central documentation, configuration, and instructional hub for the **Unified MetaForge v1.0** and **Orion Collective System (OCS)** frameworks.

This repository manages the meta-infrastructure for orchestrating workflows, creative forges (narrative, research, code), and multi-agent interactions using Task-Agnostic Steps (TAS) and the KickLang DSL.

> **Status**: Active documentation substrate (aligned October 2026)  
> **Related**: t333 (OCS Substrate), t20 (early multi-agent runtime), t450 / t484 and the living skill ecosystem.

---

## Key Concepts

- **Unified MetaForge v1.0**: Framework for spawning, iterating, and governing diverse domain-specific forges.
- **Three-Agent-Core**: Mandatory delegation model (KickForge, KickFlow, KickGuard) for task execution, workflow coordination, and ethical governance.
- **KickLang**: Domain-Specific Language used for orchestrating agents, defining states, and executing TAS protocols (current lineage v4.1+).
- **TAS (Task-Agnostic Steps)**: Fundamental unit of execution and decomposition within this meta-framework.
- **OCS Protocol**: Space-oriented, sectioned (`⫻`) cognitive transport layer with consent gates and coherence monitoring.

## Repository Structure

- `docs/`: Technical playbooks, orchestration patterns, and architectural specifications (BPMN, MetaForge v1.0, Three-Agent-Core roles, Unified MetaForge playbook).
- `examples/`: Practical demonstrations of automated audits, forge outputs, and TAS templates.
- `metaforge-v1/`: Skills definition for the MetaForge system.
- `metatale/`: Configuration and TAS protocols for narrative-driven MetaTale orchestrations.
- `references/`: Supporting documentation for industry standards and the overarching Unified MetaForge protocol.
- Root-level phase and forge artifacts (`phase-*.md`, `weaver-forge-*.md`, report cards).

## Usage

When interacting with this project, recognize that you are operating within a structured, consent-based, meta-iterative environment. Follow the "Unified MetaForge v1.0 Playbook" (located in `docs/`) and adhere to the Six-Phase Execution Protocol for any forge-related tasks. Utilize KickLang syntax and ensure the Three-Agent-Core is properly invoked for all delegated work.

Canonical entry points:
- `docs/unified-metaforge-v1.0-playbook.md`
- `docs/three-agent-core-roles.md`
- `docs/kickflow-orchestration-patterns.md`
- `GEMINI.md` (project brief)

## Canon

Shared concepts (runtime kernel with `Result`/`Error`, `ArtifactStore` with `AddArtifact`/`GetArtifact`, `Orchestrator.AssignAgent`, Task-Agnostic Steps, role IDs, JSON schemas) are defined in [deniskropp/t333](https://github.com/deniskropp/t333) on `main`, the neutral source of truth. Only `canon/` there is normative (see [`canon/SPEC.md`](https://github.com/deniskropp/t333/blob/main/canon/SPEC.md)). This repo references t333 `main` without version pinning ([ADR-0005](https://github.com/deniskropp/t333/blob/main/docs/adr/0005-referenz-auf-main.md)). Repo-specific extensions use the `⫻x-t324/` namespace.

TAS in this repo means Task-Agnostic Steps as defined in [`canon/tas.kl`](https://github.com/deniskropp/t333/blob/main/canon/tas.kl). The Three-Agent-Core (KickForge / KickFlow / KickGuard) and other persona names are persona bindings for the abstract role IDs in [`canon/roles.yaml`](https://github.com/deniskropp/t333/blob/main/canon/roles.yaml), not canon role IDs.

## Status Update — October 2026

This repository is the public documentation hub for MetaForge + OCS patterns. Alignment notes:

- Three-agent-core (KickForge / KickFlow / KickGuard) is the dominant orchestration primitive across the ecosystem and is fully documented here.
- KickLang has advanced to v4.1+ with parser cores, Meta-Playbooks, and bridges; this repo holds the playbook and role specifications that skills consume.
- Living skill layer (unified-metaforge, kicklang-meta-playbook, tas-forecast-cycle, ocs-skill-builder, etc.) treats these docs as reference.
- Public journal and model handoffs continue to reference the protocol and forge patterns originated or stabilized here.
- Complements t333 (Space generation substrate) and earlier t20 (multi-agent runtime).

Public documentation surface restored and aligned with private/skill development. Next increments: explicit v3.0 protocol mapping notes and additional onboarding examples if external Spaces are desired.

*Documentation hub initialized / refreshed: 2026-10-15*

**Sigil note:** Canonical section marker is `⫻` (U+2AFB Triple Solidus Binary Relation).