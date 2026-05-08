# ⫻data/forge_set: Process Automation Candidates (Phase 2 & 3)

**Domain:** Process Automation (Hybrid AI/Human)
**Archetype:** analytical+iterative

## Candidate A: The "Compliant Onboarding" Forge (Score: 9.2)
- **Concept:** Automates employee/client onboarding. AI agents handle data extraction and validation (`TAS_Sequence`), while HR teams review a generated BPMN diagram of the process flow.
- **Key Patterns:** `Modularity_Amplification` + `TAS_Transform` (KickLang → BPMN XML).
- **Pros:** Highly practical, clear human-in-the-loop checkpoints.

## Candidate B: The "Dynamic Triage" Forge (Score: 8.8)
- **Concept:** Intelligent routing of complex support tickets or incidents. Agents score and route issues, dynamically adjusting the sequence, while logging a BPMN trace of the taken path for later review.
- **Key Patterns:** `Broadcast_Bus_Injection` + `TAS_Sequence`.
- **Pros:** Highly adaptive, but mapping highly dynamic agent behavior to static BPMN can be complex.

## Candidate C: The "Automated Compliance Audit" Forge (Score: 9.5)
- **Concept:** Agents run continuous audits against a target system or dataset, defined by `TAS_Sequence`. The system periodically snapshots the process into a strict BPMN model for external human auditors, ensuring full transparency.
- **Key Patterns:** `Consent_Gate_Stacking` (for audit sign-offs) + `Cross_Forge_Callback`.
- **Pros:** Maximizes the strengths of both patterns—relentless AI execution combined with rigorous, human-readable compliance reporting.

**KickForge Recommendation:** Candidate C ("Automated Compliance Audit") offers the most robust demonstration of integrating dynamic AI orchestration with static, standardized documentation.