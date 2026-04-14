# Using WavePro to Plan, Purchase, and Track Guaranteed Commitments
 
## Who This Guide Is For
 
This guide is for cloud buyers, FinOps practitioners, and engineering leads who manage AWS spend through WavePro — Alphaus' end-user platform that comes with Ripple. If your MSP has enabled Guaranteed Commitments for your account, this guide walks you through exactly how to use WavePro to plan commitments confidently, reduce coverage risk, and track what you hold.
 
---
 
## Why This Process Matters
 
Buying Reserved Instances or Savings Plans without analysis is one of the most common — and costly — mistakes in cloud FinOps. Commit too aggressively and you're paying for capacity you're not using. Commit too conservatively and you're leaving 30–40% discounts on the table.
 
WavePro addresses this by grounding every commitment decision in your actual historical usage. And because commitments are guaranteed, the downside risk is fundamentally changed: if your monthly savings go negative after the lock-in period, the shortfall is refunded — bringing your net savings back to zero.
 
---
 
## The Two Areas of WavePro You Need to Know
 
WavePro's Guaranteed Commitments functionality is organized into two sections:
 
- **Commitment Planner** — Where you review commitment plan recommendations generated from your historical usage, and purchase Guaranteed Commitments.
- **Commitment Inventory** — Where you track the commitments you've purchased.
 
> **Note:** Access to both sections requires your MSP to have enabled Guaranteed Commitments for your account via Ripple.
 
---
 
## Part 1: Commitment Planner
 
### What It Does
 
The Commitment Planner analyzes your historical AWS usage — pulled from your connected Cost and Usage Report (CUR) — and generates commitment plan recommendations.
 
---
 
### Understanding the Plan Recommendations
 
Recommendations are presented across three available plans, each with a different lock-in period and savings profile:
 
| Plan | Description | Minimum Term |
|------|-------------|--------------|
| **Flexible** | 30-day GRI commitments for all reservable services. Unused discounts are automatically refunded after 30 days. | 30 days |
| **High Discount** | 1-year GRI and native commitments for all reservable services. Lower Risk Premium rate with deeper long-term savings. | 365 days |
| **1 + 3 Year** | 1-year GRI and 3-year native commitments. Deepest available savings for stable, long-term workloads. | 365 days |
 
**What the guarantee covers:**
 
- Discounts and refunds are automatically settled every month — no manual management required.
- If discounts are not realized, the difference is automatically refunded. Your costs will never exceed on-demand pricing after the lock-in period.
- RI/SPs are managed in a dedicated AWS account within your organization. You can verify them in WavePro or the AWS Console.

The Risk Premium is the cost of the guarantee — calculated as a percentage of your realized monthly savings, not a flat fee. This means:

- If utilization drops and savings decrease, the Risk Premium decreases proportionally.
- If monthly savings reach zero, no Risk Premium is charged.
- After the lock-in period, if monthly savings go negative, the gap is refunded, bringing your net savings back to zero.

**How the underlying native RI/SP term is determined:** You don't choose the native AWS commitment term. The system automatically selects the native RI/SP that maximizes savings — typically a 3-year commitment, where available, or a 1-year term for services where a 3-year term isn't offered (e.g., RDS).
 
**Choosing between plans:**
 
- **Flexible (30-Day):** Best for services with unpredictable usage, new service trials, or environments with changing scale. Shortest lock-in with minimal commitment risk.
- **High Discount (1-Year):** Best for stable workloads where you're confident in sustained usage. Lower Risk Premium rate and stronger net savings than the Flexible plan.
- **1 + 3 Year:** Best for workloads with high confidence in long-term usage stability. Deepest available savings through a combination of 1-year GRI and 3-year native commitments.
 
Once you've reviewed the options, select the plan that fits your risk tolerance and savings goals. Because these are Guaranteed Commitments, your downside exposure is bounded — the guarantee backstops under-utilization risk in ways standard RIs and SPs do not.
 
**Decision framework:**
 
- Variable or uncertain usage → Flexible (30-Day) to limit lock-in exposure while still capturing commitment discounts.
- Stable, predictable workload → High Discount (1-Year) for the lower Risk Premium rate and better net savings.
- High confidence in long-term usage → 1 + 3 Year for the deepest available savings.
- New to Guaranteed Commitments → Start with the Flexible (30-Day) plan to build confidence in your usage patterns, then evaluate moving to a longer-term plan.
 
---
 
### Purchasing
 
Once you've reviewed the recommendations and selected a plan, click **Apply Plan** to purchase the Guaranteed Commitment.
 
> **Note:** The Guaranteed Commitments Service only covers native commitments purchased through managed accounts. Existing AWS RIs or Savings Plans purchased independently cannot be migrated into the program.
 
---
 
## Part 2: Commitment Inventory
 
### What It Shows
 
The Commitment Inventory is your ledger of Guaranteed Commitments you've purchased. For each active commitment, you can see:
 
- Service type and commitment plan
- Expiration date
- **Utilization** — The current utilization rate of your commitment. Higher utilization means your commitment is being used more effectively.
- **Cost Reduction Effect** — The monthly cost and monthly savings generated by the commitment.
 
---
 
### How to Use It
 
- **Ongoing tracking:** Check the inventory monthly — or ahead of any major workload changes — to confirm that active commitments are being utilized as expected.
- **Renewal planning:** Use expiration dates as your renewal calendar. Begin the planning process 30–45 days before a commitment expires to avoid gaps in coverage. Return to the Commitment Planner to generate a fresh set of recommendations based on your latest usage data.
- **Utilization review:** Keep in mind that since the Risk Premium is tied to realized savings, lower utilization means a lower premium — not a fixed cost you're stuck paying.
 
---
 
## End-to-End Workflow Summary
 
Here's the recommended sequence for a first-time setup and an ongoing steady-state cadence:
 
### First-Time Setup
 
1. Confirm with your MSP that Guaranteed Commitments are enabled for your account in Ripple.
2. Open Commitment Planner — review your first set of recommendations.
3. Select the plan appropriate to your workload (Flexible Plan if usage history is limited or workload is variable).
4. Purchase your first Guaranteed Commitments.
5. Check the Commitment Inventory to confirm your commitments appear. Note that there may be a short delay before purchased commitments are reflected.
 
### Ongoing Steady-State (Monthly)
 
1. **Commitment Inventory** → Review active commitments and confirm utilization is healthy.
2. **Commitment Planner** → Check for updated recommendations as your usage patterns evolve.
 
---
 
## Common Questions
 
**"What happens if my usage drops?"**
After the lock-in period, if your total monthly savings go negative, the shortfall is refunded — bringing your net savings back to zero.
 
**"What if utilization drops but savings are still positive?"**
The Risk Premium adjusts proportionally. A drop in utilization means a lower premium that month — not a penalty.
 
**"Can I bring my existing AWS RIs or Savings Plans into the program?"**
No. The Guaranteed Commitments Service only covers native commitments purchased through managed accounts. Existing commitments cannot be migrated.
 
**"How accurate are the Commitment Planner recommendations?"**
Accuracy improves with usage history. For new accounts, treat initial recommendations as directional. Revisit the planner after 30–60 days for higher-confidence recommendations as more usage history accumulates.
 
---
 
## Next Steps
 
- **Ready to run your first plan?** Log in to WavePro and navigate to Commitment Planner.
- **Not seeing Guaranteed Commitment options?** Contact your MSP — they need to enable access via Ripple before purchase options appear.