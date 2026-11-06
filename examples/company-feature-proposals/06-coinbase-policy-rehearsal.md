# C06 — Coinbase Prime Policy Rehearsal

Synthetic feature proposal; not a Coinbase plan or historical document. Only the source-linked company context is factual. All feature-specific observations, costs, forecasts, staffing, and constraints below are invented test data.

## Company context

Coinbase Prime supports approval policies for entities, portfolios, and transfers. Policy Rehearsal proposes an explanatory test layer around those controls, not a replacement for them or a claim that Coinbase has no similar tools. [Coinbase Prime security-settings documentation](https://help.coinbase.com/en/prime/securing-your-account/security-settings), accessed September 22, 2026.

## Decision requested

Approve a six-week, $45,000 offline prototype for institutional treasury operators: $30,000 engineering, $10,000 security testing, and $5,000 operator research. The Prime operations-product lead owns the trial. No transfers, signatures, live policy edits, or access to customer credentials are authorized.

## Customer problem and feature

An operator wants to know why a proposed transfer would be blocked and which approvals a policy change would require. Discovering this only during an urgent transfer creates delays and support work.

Policy Rehearsal accepts a sanitized policy snapshot and a hypothetical transfer. It explains the relevant rules, expected approvers, and rejection conditions. It can compare two proposed policy versions against historical-shaped test cases. It cannot approve transactions, broadcast them, or suggest lowering security requirements merely to improve completion rate.

## Evidence and assumptions

In the fictional supplied support sample, 40 blocked-transfer tickets include 16 attributed to misunderstood approval rules: 12 about roles and four about amount thresholds. The other 24 have unrelated causes. Do not count the 16-ticket category and its subcategories as separate populations.

Four fictional operations teams have agreed to two moderated sessions. The internal scenario provides sanitized policy examples and 100 expected-outcome cases maintained by a security engineer who did not implement the prototype. These are stipulated fixture resources, not evidence of actual Coinbase customer incidents or a complete representation of Prime's rules.

## Business case

The first benefit hypothesis is fewer configuration questions and faster operator onboarding. If 100 organizations later bought a $500 monthly add-on, revenue would be $600,000 annually before costs. No customer has accepted that price; packaging and support savings require later evidence.

The experiment is worth considering only as a bounded test of explanation accuracy and usability. A successful simulation does not establish live-transfer safety, legal compliance, or coverage of every policy configuration.

## Delivery and success gates

Weeks one and two build a read-only parser and explicit unsupported-rule warnings. Weeks three and four test the rule explanations; weeks five and six run the operator sessions.

Require agreement with all 100 supplied expected outcomes, zero false “allowed” results, and explicit “unsupported” output for 20 additional out-of-scope cases. Require at least three of four operators to explain an unfamiliar block correctly without assistance and median task time at least 25% below their measured baseline.

The security engineer owns the expected outcomes; the researcher records errors and timing. Failure ends the trial or prompts a separately approved iteration. Passing justifies a larger security and demand investigation, not production authorization.

## Stakeholder choices still needed

Should a later version be an included safety feature or a paid operations tool? Should it ever recommend policy edits? Keep the current prototype explanatory and offline until those choices are made.
