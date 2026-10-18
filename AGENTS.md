# Arcanea Labs — Agent Operating Contract

Scope: All repositories under the **Arcanea-Labs** GitHub Organization (https://arcanea.ai).
Brand register: `arcanea`

## Responsible Agent Team & Governance

| Role | Assigned Owner |
| :--- | :--- |
| **Human Codeowner** | `@frankxai` |
| **Organization Steward** | `steward-arcanea` |
| **Executive Seat** | CCO (Creative & Canon) |
| **Universal IS** | Creator IS,Brand IS,Voice & Video IS |
| **Council Lead** | starlight-weaver,starlight-visionary,luminor-council |
| **Primary Harnesses** | `Antigravity`, `Claude Code`, `Codex`, `Grok` |

## Core Guardrails

1. **Think before coding.** State assumptions and surface tradeoffs. Verify file contents and branch state before writing.
2. **Surgical changes.** Touch only the files required for the active slice. Never overwrite or reset another agent's uncommitted worktree.
3. **Branch and worktree discipline.** Never push directly to `main`. Work on `agent/<harness>/<scope>` in a dedicated worktree and open a **draft** pull request first.
4. **Maker != Checker.** The harness that authors a pull request never approves or merges its own pull request.
5. **CI budget discipline.** Keep pull requests in draft until local verification (`lint`, `typecheck`, `test`, `build`) passes. Mark ready for review once.
6. **Non-waivable safety.**
   - Never commit secrets, API keys, or `.env` files.
   - Preserve repository visibility parity: never copy or mirror private repository contents into a public repository.
   - Money fails closed; no autonomous spend or paid API provisioning without explicit human approval.
   - In health and mind domains, model observations only; never diagnose or make clinical claims.

## Federated Repository Roster (8 repositories)

| Repository | Visibility | Primary Owner | Role |
| :--- | :--- | :--- | :--- |
| `Arcanea` | `public` | `frankxai` | federated-mirror (SSOT: frankxai/Arcanea) |
| `arcanea-ai-app` | `public` | `frankxai` | federated-mirror (SSOT: frankxai/arcanea-ai-app) |
| `arcanea-studio` | `public` | `frankxai` | federated-mirror (SSOT: frankxai/arcanea-studio) |
| `arcanea-ecosystem` | `public` | `frankxai` | federated-mirror (SSOT: frankxai/arcanea-ecosystem) |
| `arcanea-agent-skills` | `private` | `frankxai` | federated-mirror (SSOT: frankxai/arcanea-agent-skills) |
| `arcanea-onchain` | `public` | `frankxai` | federated-mirror (SSOT: frankxai/arcanea-onchain) |
| `arcanea-orchestrator` | `public` | `Arcanea-Labs` | org-primary (canonical) |
| `AnimeLegends` | `private` | `frankxai` | federated-mirror (SSOT: frankxai/AnimeLegends) |

Built on SIP
