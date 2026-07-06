# Step 6: GHEC Platform + Consolidation

**⏱️ ~15 min** · Goal: platform pitch, ADO migration, TCO math.

## Read

**GHEC:** The full GitHub platform. $21/user/mo. Includes 50,000 Actions minutes + 50 GB Packages storage.

**Why customers pick GHEC:**
- One platform: repos + Actions + Packages + AppSec + Copilot
- One auth, one audit, one bill
- Displaces Jenkins + Artifactory + separate SCM + separate CI + AI tools
- Fastest path to agentic workflows (they run on the platform)

**Key features:** Rulesets · Custom repo roles · IP allowlist · Audit log streaming · SAML/SCIM · Push rules · Merge queue

**GHES vs GHEC vs EMU:**
| | GHEC | GHES | GHEC + EMU |
|---|---|---|---|
| Hosting | Cloud | On-prem | Cloud |
| Identity | Personal + SAML | Personal + SAML | IdP-only |
| Best for | Most enterprises | Regulated / air-gapped | Regulated cloud |

**Actions overage:** Linux 2-core = $0.008/min · Windows = 2x · macOS = 10x

## Disco

| Question | Signal | Follow-up |
|---|---|---|
| "How many SCM/CI tools?" | "3+" | "Consolidation. One platform for repos + CI + packages + security + AI. TCO math almost always works." |
| "ADO exit plan?" | "On roadmap" | "MSFT funds ADO → GHEC migrations (30% empowerment). Cloud Accelerate Factory + partner (Avanade/Accenture/Slalom) runs the migration." |
| "How enforce standards across repos?" | "Manual" | "Rulesets — required checks, protected branches, push rules. Set once at org level, applies everywhere." |
| "Regulatory blocker for cloud?" | "FedRAMP / air-gap" | "GHES fits. Same platform, self-hosted. Often hybrid — GHES for regulated, GHEC for the rest." |

## 📝 Quiz
Complete [`quiz.md`](quiz.md).
