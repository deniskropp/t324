# KickFlow Orchestration Patterns — Detailed v1.0

**KickFlow** is the **central workflow conductor** of the Three-Agent-Core. While KickForge extracts and scores, and KickGuard protects and visualizes, **KickFlow designs, sequences, refines, and coordinates** the actual execution.

It applies a library of **Gen3 Orchestration Patterns** (advanced, battle-tested coordination techniques) that turn raw intent into elegant, modular, consent-aware, and evolvable workflows.

---

## 1. Core Orchestration Patterns (The Gen3 Toolkit)

| Pattern                        | Purpose                                                                 | When KickFlow Applies It                              | KickLang Example |
|--------------------------------|-------------------------------------------------------------------------|-------------------------------------------------------|------------------|
| **Modularity_Amplification**   | Break every deliverable into smallest reusable atomic modules          | Phase 4 & 5 (refinement)                              | `⫻logic/apply: "modularity_amplification"` |
| **Broadcast_Bus_Injection**    | Insert event-driven communication layer so agents react without direct calls | All phases (especially multi-agent coordination)     | `⫻cmd/broadcast:{event: "TASReady", payload: {...}}` |
| **Consent_Gate_Stacking**      | Layer multiple explicit consent checkpoints at critical decision points | Phase 1 (initial), Phase 4 (iteration), Phase 6 (final) | `⫻logic/if: meta_consent_level == "clean" THEN ...` |
| **30%_Syntax_Economy**         | Ruthlessly reduce token bloat while preserving full meaning            | Phase 5 (polish)                                      | Remove redundant explanations, use symbolic shorthand |
| **Cross_Forge_Callback**       | Create reusable hooks so one forge can call or spawn another           | Phase 5 & 6 (when reusability score ≥ 8)              | `⫻data/spec: spawn_hook = "unified-metaforge:spawn(domain)"` |
| **TAS_Sequence**               | Convert purified TAS into strict linear + parallel execution sequence  | Phase 2 (mapping)                                     | `⫻data/spec: phase_beats = [1,2,3,4,5,6]` |
| **TAS_Align**                  | Ensure every sub-task aligns with original user goals + Meta-DNA        | Phase 4 (refinement)                                  | `⫻logic/apply: "TAS_ALIGN + domain_fidelity_check"` |
| **TAS_Contextualize**          | Inject domain-specific best practices and constraints                   | Phase 2 & 4                                           | Add `{domain}_best_practices` to spec |
| **TAS_Transform**              | Convert between formats (TAS → spec → report_card → visual_prompt)     | Phase 5                                               | `⫻logic/apply: "TAS_TRANSFORM + delivery_notes"` |
| **Delegation_Priority**        | Rank tasks by urgency, dependency, and agent strength                   | Every phase                                           | `⫻data/var: delegation_priority = [KickForge: high, KickGuard: medium]` |

---

## 2. How KickFlow Sequences the 6 Phases (Internal Flow)

**KickFlow’s Master Sequence Logic:**

1.  **PHASE 1** → KickGuard (consent gate) → KickForge (TAS extraction) → KickFlow (TAS_SEQUENCE + initial structure)
2.  **PHASE 2** → KickFlow (archetype switch + forge_pattern generation) → KickForge (scoring) → KickFlow (select top 2-3)
3.  **PHASE 3** → KickFlow (presentation formatting) → KickGuard (capture feedback)
4.  **PHASE 4** → KickFlow (apply Gen3 patterns) → KickForge (new candidates + ban check) → KickFlow (iteration decision)
5.  **PHASE 5** → KickFlow (full_architecture_assembly + 30%_syntax_economy + TAS_TRANSFORM) → KickGuard (visuals via AR-00L) → KickForge (final validation)
6.  **PHASE 6** → KickFlow (report_card_assembly + delivery_notes) → KickGuard (integrity sign-off) → Orchestrator (halt)

---

## 3. Decision Heuristics (Internal Rules)

- **Low Score Recovery:** If hybrid score < 8.5 → apply **Modularity_Amplification** + **TAS_Align** before presenting.
- **Creativity Boost:** If user requests “more creative” → boost **TAS_Contextualize** with divergent thinking patterns.
- **Reusability:** If cross-domain request → always inject **Cross_Forge_Callback**.
- **Iteration Pressure:** If iteration ≥ 2 → force **Consent_Gate_Stacking** + **30%_Syntax_Economy**.
- **Visual Detection:** If visual benefit detected → delegate to KickGuard + AR-00L with detailed constellation prompt.

---

## 4. KickFlow Signature Outputs
- **`⫻data/spec`**: Complete phase beats, agent arcs, theme statement, ending variants, spawn hooks.
- **`⫻data/delivery_notes`**: Phase_timing, delegation_priority, persist_strategy, error_recovery, {domain}_best_practices.
- **Refined `⫻data/forge_set`**: Scored and polished options ready for final review.
