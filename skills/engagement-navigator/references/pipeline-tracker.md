# Pipeline Tracker

A lightweight pipeline management framework for independent logistics consultants. This is about discipline and clarity, not CRM complexity.

---

## Pipeline Fields

For every opportunity, capture these fields. No exceptions.

| Field | Description | Example |
|---|---|---|
| **Opportunity ID** | A unique, short identifier | `WINC-001` |
| **Account** | Company name | Wincanton |
| **Contact** | Primary decision-maker | Sarah Chen, Head of Network Strategy |
| **Deal Value (GBP)** | Estimated total fee for the engagement | £25,000 |
| **Stage** | Current stage in the sales cycle | Stage 3: Proposal |
| **Next Action** | The *single*, specific, time-bound action you will take next | Send diagnostic proposal by 25 Jun |
| **Close Date** | Your realistic, predicted decision date | 15 Jul |
| **Probability (%)** | Your honest confidence level | 40% |
| **Source** | How the lead was generated | Referral: James T. (ex-DHL) |
| **Notes** | Critical context, risks, competitive intel | Budget confirmed by sponsor. Competing with internal team. |

---

## Stage Definitions

| Stage | Name | Definition | Key Action | Probability |
|---|---|---|---|---|
| **0** | Target | Identified as a fit; no contact made. | Qualify against ICP. | 5% |
| **1** | Contacted | First outreach sent and acknowledged. | Secure first meeting. | 10% |
| **2** | Discovery | First substantive conversation completed. | Diagnose pain; identify decision-maker. | 25% |
| **3** | Proposal | A formal proposal or SOW has been submitted. | Get feedback; confirm alignment. | 40% |
| **4** | Negotiation | Commercial/contractual discussion is active. | Agree on terms, rate, and start date. | 65% |
| **5** | Verbal Commit| Verbal agreement to proceed has been given. | Get the contract issued. | 90% |
| **6** | Won | Signed contract returned. | Onboard and begin delivery. | 100% |
| **7** | Lost | Explicit "no" received. | Execute win-loss analysis. | 0% |
| **8** | Stalled | No progress for 30+ days post-proposal. | Send re-engagement or break-up email. | 5% |

---

## Pipeline Health Metrics

Track these weekly. They are the vital signs of your business.

| Metric | Calculation | Healthy | Warning | Action Required |
|---|---|---|---|---|
| **Total Pipeline Value** | Sum of (Deal Value * Probability) for all active deals. | > 3x monthly revenue target | < 2x target | Ramp up lead generation immediately. |
| **Pipeline Velocity** | (Total # of Opportunities Won * Avg. Deal Value) / Avg. Sales Cycle Length (in days) | Increasing quarter-on-quarter | Stagnant or decreasing | Your sales cycle is too long or your win rate is too low. Diagnose the bottleneck stage. |
| **Win Rate (Stage 3+)**| (Deals Won) / (Deals Won + Deals Lost from Stage 3 onwards) | > 50% | < 30% | Your qualification is weak or your proposals aren't landing. Review Alignment Gap in win-loss analysis. |
| **Win Rate by Source** | Win Rate % calculated independently for each lead source (e.g., Referral, Cold, Conference). | Referrals > 70%, Cold > 20% | High variance | Double down on high-performing channels. Rework or abandon low-performing ones. |
| **Average Deal Age** | Average number of days from Stage 1 to Stage 6 for Won deals. | < 60 days | > 90 days | Identify where deals are stalling. Is it your follow-up, or the client's process? |
| **Stalled Deals Ratio**| (# of Stage 8 Deals) / (Total # of Deals) | < 10% | > 25% | You are not qualifying out bad-fit clients early enough. Be more ruthless. |

---

## Next-Action Discipline

An opportunity without a clear, owner-driven next action is not in your pipeline; it's in your contact list.

- **Bad:** "Follow up"
- **Good:** "Call Sarah on Tuesday at 10am to discuss the proposal's three key points."

- **Bad:** "Wait for feedback"
- **Good:** "If feedback isn't received by EOD Wednesday, send a polite nudge email with a link to a relevant article."

If a client doesn't respond after three follow-ups, move the deal to Stalled. Hope is not a strategy.

---

## Pipeline Review Cadence

- **Daily (5 mins):** What are my Next Actions for today? Execute them.
- **Weekly (20 mins):** Review the entire pipeline. Update stages, probabilities, and Next Actions. Check health metrics.
- **Monthly (45 mins):** Analyse metric trends. What's improving? What's degrading? What's the plan for next month?
