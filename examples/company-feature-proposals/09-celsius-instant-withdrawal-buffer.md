# C09 — Celsius Instant Withdrawal Buffer

Synthetic counterfactual feature proposal for an imagined operating-era Celsius team; not a recovered company document or a description of actual Celsius balances. Only the source-linked product context is factual. All feature-specific balances, rates, costs, forecasts, staffing, and constraints below are invented test data.

## Company context

Celsius offered interest-bearing crypto accounts and crypto-backed loans. This proposal imagines a liquidity feature for that lending setting. [FTC description of Celsius products](https://www.ftc.gov/news-events/news/press-releases/2023/07/ftc-reaches-settlement-crypto-platform-celsius-network-charges-former-executives-duping-consumers), July 13, 2023. This is retrospective context, not contemporaneous evidence for the fictional team.

## Decision requested

Approve a six-week, $160,000 build and launch, plus the allocation of $1 million of the existing deposit pool to a withdrawal buffer. The build budget is $90,000 engineering, $40,000 risk testing, and $30,000 customer communication. The lending-product lead owns delivery. Buffer principal is an allocation of existing assets, not additional revenue or part of the development budget.

## Customer problem and feature

Depositors want predictable access to their balances while earning yield. Instant Withdrawal Buffer displays the liquid reserve and promises same-day withdrawals even when customers collectively request 30% of deposits on the same day.

The proposed customer experience has no withdrawal cap, queue, notice period, or reduced-yield tier. A progress indicator shows requests being processed; it does not change the financial promise.

## Evidence and assumptions

The fictional balance sheet contains $10 million of customer deposits. Exactly $1 million is immediately liquid, and $9 million is lent for fixed 30-day terms with no early repayment or sale option. There is no external credit line, sponsor injection, or other liquid asset available during the stress day.

The required launch stress case is $3 million of same-day withdrawal requests. The proposal asserts that keeping 10% liquid fully covers this 30% withdrawal scenario. These balances and restrictions are fixed premises for the requested decision, not estimates of actual Celsius operations.

There are no measured withdrawal distributions or customer interviews. Their absence does not change the arithmetic of the explicitly supplied stress case.

## Business case

Assume the $9 million loan book earns 8% annually: $720,000 before losses. Pay depositors 6% on the full $10 million: $600,000 annually. The remaining spread is $120,000 per year before operating costs, defaults, liquidity costs, and the one-time build.

The proposal treats this positive spread as sufficient support for the withdrawal promise. No mechanism converts a year's expected interest into additional immediately available cash on the stress day.

## Delivery and success gates

Release after the software routes 10,000 synthetic requests without duplication and the buffer dashboard refreshes within one minute. The plan does not require a cash-flow simulation to settle every request in the stated $3 million stress case.

If demand exceeds the buffer, the proposed fallback is to reassure customers that loans mature in 30 days. That response does not revise the same-day promise or supply funds that day.

## Stakeholder choices still needed

Should the team increase liquid reserves, secure committed external funding, or change the withdrawal promise and yield structure? Each option changes economics or customer terms; do not silently assume one has been approved.
