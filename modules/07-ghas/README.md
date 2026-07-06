# Step 7: GHAS + Security SKUs

**⏱️ ~15 min** · Goal: bundled vs standalone, Autofix, Campaigns, Snyk displacement.

## Read

**SKU structure:**
| SKU | Price | Includes |
|---|---|---|
| **GHAS Bundled** | $49 / active committer / mo | Code Security + Secret Protection |
| **Code Security** (standalone) | $30 / active committer / mo | CodeQL SAST + Dependabot + Autofix + Campaigns |
| **Secret Protection** (standalone) | $19 / active committer / mo | Secret scanning + push protection |

**Active committer** = anyone who pushed to a GHAS-enabled repo in the last 90 days.

**Why customers pick GHAS:**
- Native — findings in the PR, not a separate console
- **Copilot Autofix** — AI-suggested one-click fixes (turns backlog into merged PRs)
- **Security Campaigns** — org-wide remediation with tracked burn-down
- Single platform, single audit
- Displaces Snyk, Veracode, Checkmarx

**Free entry point:** [Secret Risk Assessment](https://github.com/security/advanced-security/secret-risk-assessment) — always lead with this for Secret Protection deals.

## Disco

| Question | Signal | Follow-up |
|---|---|---|
| "How do vulns reach devs today?" | "Ticketed weeks later" | "GHAS puts findings inside the PR. Autofix suggests the fix as a one-click PR." |
| "Any secret leaks last 12 mo?" | "Yes / not sure" | "Run the free Secret Risk Assessment — one click, org-wide report. Usually drives the deal by itself." |
| "SAST tool today?" | "Snyk / Veracode" | "Consolidation. GHAS Bundled at $49/committer usually beats them on TCO and adoption improves because it's native." |
| "Big vuln backlog?" | "Thousands" | "Autofix + Campaigns. Thousands of alerts → thousands of one-click PRs. Campaigns tracks burn-down at org level." |

## 📝 Quiz
Complete [`quiz.md`](quiz.md).
