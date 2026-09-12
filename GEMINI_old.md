# MetaForge v1.0 — The Forge of Forges

## Project Overview
MetaForge v1.0 is a unified framework and "Forge of Forges" designed to orchestrate complex multi-agent systems. It enables the creation, iteration, and deployment of domain-specific "Forges" (e.g., story, workflow, research, code, humor) through a standardized, 6-phase protocol.

The system relies on a **Three-Agent-Core** and uses **KickLang DSL** for command and control.

### Core Architecture (Three-Agent-Core)
The system relies on a **Three-Agent-Core** and uses **KickLang DSL** for command and control. For a detailed breakdown of each agent's expanded roles and responsibilities, see `docs/three-agent-core-roles.md`.

- **KickForge:** Handles Task-Action-Structure (TAS) extraction, purification, validation, and scoring.
- **KickFlow:** Manages workflow structuring, coordination, Gen3 technique application, and knowledge transfer.
- **KickGuard:** Enforces ethics, integrity, dynamic orchestration, visual assets, and consent-first gates.

### Key Concepts
- **TAS (Task-Action-Structure):** The foundational definition for a new Forge, specifying domain, archetype, goals, and constraints.
- **KickLang DSL:** The native command layer (e.g., `⫻cmd/`, `⫻data/`, `⫻logic/`).
- **Orchestration Patterns (Gen3):** Advanced coordination techniques used by KickFlow (e.g., Modularity_Amplification, Consent_Gate_Stacking, Broadcast_Bus_Injection). See `docs/kickflow-orchestration-patterns.md` for details.
- **6-Phase Protocol:** A strict workflow from framing to final delivery, with a maximum of 3 meta-iterations.
- **Hybrid Score:** A metric of consistency and engagement, with a target of ≥ 8.5 for full assembly.
- **Persistent Meta-DNA:** Learned preferences and states that persist across sessions.

---

## Directory Structure
- **`docs/`**: Strategic playbooks and high-level patterns (e.g., `metaforge-v1-playbook.md`).
- **`examples/`**: Sample inputs (`sample-tas.md`) and production-ready outputs (e.g., `automated-compliance-audit-forge.md`) for reference.
- **`metaforge-v1/`**: Contains the `SKILL.md` file defining the Gemini CLI skill for this framework.
- **`references/`**: Technical specifications and protocol details (e.g., `unified-metaforge-protocol.md`).

---

## Usage & Protocol
To use this framework, follow the **Unified MetaForge v1.0 Protocol**:

1.  **Phase 1 (Launch & Framing):** Formalize the Universal TAS and confirm archetype/domain.
2.  **Phase 2 (Mapping & Generation):** Generate forge variations and score them.
3.  **Phase 3 (Presentation):** Present top options for feedback.
4.  **Phase 4 (Refine & Iterate):** Max 3 iterations based on feedback; update Meta-DNA.
5.  **Phase 5 (Build & Polish):** Finalize architecture (if score ≥ 8.5) and generate visual assets.
6.  **Phase 6 (Closure):** Persist Meta-DNA and sign off on integrity.

### Quick Start Commands
- **Activate Skill:** "activate skill metaforge-v1"
- **Spawn Forge:** "spawn a forge for [domain]"
- **Submit TAS:** Provide a Task-Action-Structure definition based on `examples/sample-tas.md`.

---

## Development Conventions
- **Consent-First:** All major transitions require explicit user consent gates.
- **Banned Structures:** Avoid circular dependencies without guards, hardcoded agent names, or missing persistence layers.
- **Iterative Limit:** Strictly enforce a maximum of 3 meta-iterations to prevent infinite loops and ensure focus.
- **Hybrid Scoring:** Use the `KickForge` scoring system to evaluate every generation; anything below 7 is discarded.
