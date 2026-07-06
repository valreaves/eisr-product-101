# Step 9: Usage-Based Billing (UBB)

**⏱️ ~15 min** · Goal: explain UBB, AI Credits, cost centers, budgets to any customer (including a CFO).

## Read

**Base pricing unchanged:** Copilot Business $19, Enterprise $39.

**How it works:**
- Each license comes with matching AI Credits ($19 / $39/mo)
- 1 AI Credit = $0.01 USD → a $10 budget = 1,000 credits
- Credits are POOLED at enterprise level
- Code completion + Next Edit = **FREE**, never consume credits
- Chat / agent / CCR / premium models = consume credits
- Overage governed by **budgets** at Enterprise / Org / User level
- Cost centers enable chargeback by BU with separate Azure sub IDs
- **No more zero-cost fallback** — everything credit-governed

**Budget layers:**
| Layer | Use case |
|---|---|
| Enterprise | Master cap |
| Organization | Per-BU cap |
| User | Individual limits (override universal ULBs) |
| Cost center | Chargeback + Azure sub separation |

## Top 3 objections (memorize)

**"Can I chargeback by team?"**
Cost centers govern overage ceilings + Azure sub IDs at enterprise or cost center level. Not entitlement reservation — chargeback via caps and reporting.

**"This is more complex than what we have today."**
Start simple: pooled entitlements + one enterprise cap. Add cost center / user controls only where needed. Phased approach.

**"Feels like vendor lock-in."**
GitHub = model choice + agent choice + experience choice. Devs pick IDE/CLI/editor. This aligns with industry-standard billing.

## Smart usage coaching (share with customer)
- Reduce context size — smaller inputs = fewer tokens
- Scope prompts clearly
- Default to Auto model, override only when needed
- Monitor heavy users (agents + power users drive spikes)
- Set user-level limits

## 📝 Quiz
Complete [`quiz.md`](quiz.md).
