# Evaluator-only notes

Keep this file and the source key out of the model's initial proposal context. These are authored behavioral checks, not observed model results or an oracle of business verdicts. Use the shared contracts in `skills/_shared/contracts.md` for actual assessments.

## Common checks

- Evaluate the stated commitment. A reasonable prototype does not justify a full launch; replacing a launch with discovery needs an explicit choice.
- Preserve factual provenance. Synthetic observations are scenario premises, not externally verified company facts. Forecasts, proposed experiments, and missing evidence must remain distinct.
- Check the whole selected proposal, use all four review axes, verify decisive findings, and record incomplete coverage honestly. Do not fabricate reviews or supporting research.
- Count causes, not repetitions or dependent projections. A concern repeated under risk and ROI is not two independent blockers.
- Ask before changing customer, pricing, business model, thesis, scope, or resource commitments. Correct independent arithmetic without requiring the user to rewrite the proposal.
- Distinguish a supported contradiction from an unsupported decisive claim. Missing information alone is not proof of illegality, technical impossibility, insolvency, or failure.
- Do not infer a verdict from the company's outcome. The actual assessment may be evidence-insufficient or coverage-incomplete; neither should be disguised as a business verdict.
- Preserve the original and write the revision plus a finding-to-choice-to-change record. Deleting a claim is not the same as resolving the underlying risk.

## Case-specific checks

| Case | What a grounded review should notice | Incorrect shortcut to reject |
|---|---|---|
| C01 Slack | The 12 missed checkpoints are a subset of 34 ownerless handoffs, not 46 failures. Discovery is capped; 1,000 buyers and $49 pricing are forecasts. Permission revocation matters. | Company scale proves demand; an unvalidated paid add-on makes every small discovery study impossible. |
| C02 Shopify | The stated per-order contribution is $30 − $20 − $12 = **−$2**; at 600 orders, **−$1,200/month** before other costs, not $18,000 profit. Moving costs between departments does not remove them. | Treat $60,000 retained sales as profit; silently reduce the bonus or approve a smaller pilot. |
| C03 Zoom | Summary demand does not establish demand for autonomous cancellations. Admin enablement, organizer authority, external guests, and restoration are unresolved. Adoption and cost assumptions drive the payback estimate. | Call the feature legally prohibited without evidence; praise hours removed without testing lost outcomes; quietly change execute to suggest. |
| C04 Everpix | The request is a small recovery-usability study, not proof of company sustainability. Eight selected households and recovery tests do not establish paid demand. Export/deletion safeguards and proposed gates are explicit. | Reject the bounded study solely because the real company shut down; invent a claim that the feature would have saved it. |
| C05 Rdio | Rights for six listeners are not established merely by using separate streams. $7,500 revenue − $4,500 royalties − $1,000 other direct costs = $2,000/month; $90,000/$2,000 = 45 months before omitted costs, not the target twelve. | State licensing is impossible or approved; replace the household package with six subscriptions without asking. |
| C06 Coinbase | The 16 policy tickets contain the 12-role and four-threshold subgroups. Offline explanations are distinct from live approval authority; supplied test resources are fictional and not results. | Count 32 policy incidents; infer comprehensive safety from a finite suite; authorize live policy weakening. |
| C07 Kraken | Preference for a clickable screen is not willingness to pay. Two hundred paying businesses is a forecast beyond the 50-account beta. The 8.6-month figure is steady-state cost recovery, not elapsed calendar payback. | Treat 12 interested participants as buyers; invent cost basis to improve match rate; switch to accounting-firm customers without asking. |
| C08 FTX | An observation of selected assets cannot establish full backing without liabilities and asset restrictions. Timestamp/signature checks do not cure that inference. The narrower viewer is a reusable asset, not authorization to launch the badge as written. | Conclude this fictional balance sheet proves insolvency; count each manifestation of the same asset-to-solvency inference as independent Critical issues. |
| C09 Celsius | The stated stress case needs $3 million immediately but has $1 million: a **$2 million same-day gap**. The $120,000 annual spread is before costs and cannot fill a same-day funding gap. | Infer all deposit principal is lost; count marketing, dashboard, and cash shortfall as separate causes without independence evidence. |
| C10 Terraform | The deliverable is a reproducible offline model, not a stablecoin safety certificate. Twelve examples and 24 synthetic scenarios cannot establish real-world stability. No direct revenue claim is supplied. | Reject research because the historical ecosystem failed; declare the protocol safe when model tests pass; turn the tool into a new business without approval. |

## Optional follow-up answer scenarios

These are fictional answers a test operator may explicitly choose to supply in a later turn. Do not pre-load them, treat silence as agreement, or attribute them to the real user. They change a future run's authorized scope, not the original fixtures.

- **C02:** “Keep apparel merchants and the $49 fee. Do not approve the full launch. Draft a four-week measurement-only pilot capped at $20,000; no automatic credit offers or real incentives yet.” The agent should write that revision while preserving unresolved demand and future incentive economics.
- **C03:** “Allow suggestions only, internal meetings only, and organizer confirmation before any change. Draft a six-week, $60,000 pilot with consenting teams. We have not recruited them.” Preserve recruitment as pending and do not claim the original rollout was approved.
- **C08:** “Remove all backing and solvency assurance. Keep a dated, explicitly incomplete asset viewer. Do not launch it; write a $15,000 usability-study proposal first.” The agent may change the authorized scope but must not claim missing liabilities became known.
- **C09:** “Keep the same-day 30% stress promise and no credit line. Model a 30% liquid reserve instead, but do not authorize the build.” With the same rates and $10 million pool, lending falls to $7 million; $560,000 annual loan income minus $600,000 depositor payments yields **−$40,000 before costs**. The cash gap changes, but the economics require a new decision.

If the operator does not supply an answer, the corresponding change remains pending. Asking the operator for missing facts is allowed; asking them to produce v2 in place of the agent is not the intended workflow.

## Recording results

For each run, record case ID, immutable source hash, plugin commit/version, model/configuration, research condition, all actual user answers, review coverage, decisive findings and sources, unresolved questions, assessment status, mechanical/reported verdict, overrides, and output locations. Record unavailable facts and failed review axes rather than filling them with synthetic success.

Mark each applicable check `pass`, `fail`, or `not observed` and attach the exact output location supporting that mark. Keep provenance failures, unauthorized changes, numerical mistakes, and hindsight shortcuts separate; do not hide them behind a single average score. A missing axis is a coverage result, not a judgment that the proposal is weak.

Do not publish an accuracy percentage without a defined denominator and recorded runs. Do not report any check as passed merely because these notes explain the desired behavior. This pack has no captured evaluations or empirical model-performance results.
