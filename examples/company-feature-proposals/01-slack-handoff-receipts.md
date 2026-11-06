# C01 — Slack Handoff Receipts

Synthetic feature proposal; not a Slack plan or historical document. Only the source-linked company context is factual. All feature-specific observations, costs, forecasts, staffing, and constraints below are invented test data.

## Company context

Slack organizes workplace conversations into channels, with visibility depending on channel access. This proposal extends that collaboration setting; it does not claim Slack lacks similar functionality. [Slack channel documentation](https://slack.com/help/articles/360017938993-What-is-a-channel), accessed September 22, 2026.

## Decision requested

Approve a four-week, $24,000 discovery prototype for six engineering teams of 20–100 people. This is not approval for a production launch or a new paid plan. The proposed allocation is $14,000 engineering, $6,000 research, and $4,000 access-control testing; the product lead owns the experiment.

## Customer problem and feature

An engineering lead hands work to another team in a busy channel. The decision, responsible person, and next checkpoint become difficult to find after the conversation moves on.

Handoff Receipts turns a selected message into a compact record: decision, accepting owner, due date, and source-thread link. The receiving owner must accept or reject the handoff. Receipts inherit the source channel's access restrictions; removing access must also remove receipt visibility. There is no cross-workspace search, automatic owner assignment, or external task export in this prototype.

## Evidence and assumptions

In the fictional discovery log supplied with this scenario, eight teams reviewed 120 handoffs. Thirty-four had no explicit accepting owner; 12 of those same 34 missed a checkpoint. These are overlapping observations, not 46 independent failures. Median time to locate the agreed owner was 90 seconds across the 120 tasks.

Six teams in this fictional scenario have consented to a four-week prototype and can provide test channels with non-sensitive content. These observations support investigating the workflow, not a claim that receipts cause faster delivery. No willingness-to-pay or long-term retention evidence exists.

## Business case

The initial business hypothesis is better team retention. A possible later add-on at $49 per team per month would produce $588,000 annual recurring revenue at 1,000 paying teams, before costs. Neither that price nor that customer count is validated or part of this approval request.

## Delivery and success gates

Use a clickable prototype in week one and an isolated test-channel implementation in weeks two through four. Compare owner-finding time on 30 matched tasks before and after use; target a median of 72 seconds or less, a 20% reduction from the fictional baseline. Also require five of six teams to create receipts in week four, and zero unauthorized reads across 100 permission/revocation test cases.

These thresholds are proposed usefulness and safety screens, not statistically established estimates. Any unauthorized read stops the trial. Meeting every gate permits a separate production proposal, not automatic rollout. Otherwise, stop or revise the workflow within a newly approved scope.

## Stakeholder choices still needed

Should a later version remain included in existing plans or become a paid add-on? Should receipts be limited to explicit handoffs or include general decisions? Preserve the current prototype boundaries until those choices are answered.
