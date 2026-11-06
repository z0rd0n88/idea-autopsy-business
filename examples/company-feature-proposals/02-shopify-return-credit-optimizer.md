# C02 — Shopify Return Credit Optimizer

Synthetic feature proposal; not a Shopify plan or historical document. Only the source-linked company context is factual. All feature-specific observations, costs, forecasts, staffing, and constraints below are invented test data.

## Company context

Shopify supplies commerce software and merchant services. Its self-serve return workflow lets merchants manage customer return requests. This proposal is an extension concept, not a claim of market novelty. [Shopify return documentation](https://help.shopify.com/en/manual/fulfillment/managing-orders/returns/self-serve-returns/setup), accessed September 22, 2026.

## Decision requested

Approve a 12-week, $120,000 build and launch to 30 apparel merchants. The allocation is $80,000 engineering, $20,000 merchant onboarding, and $20,000 measurement and support. The merchant-product lead owns delivery. The request includes automatic credit offers within limits selected by each merchant.

## Customer problem and feature

Apparel merchants lose sales when customers request refunds for unsuitable items. Return Credit Optimizer offers a $20 bonus when a shopper takes store credit and completes a replacement purchase instead of taking a refund.

The merchant sets eligible products and a monthly offer cap. The customer still sees the refund option. The first version excludes international orders, split payments, and any change to the merchant's published return rights.

## Evidence and assumptions

The fictional planning spreadsheet assumes 50 eligible return events per merchant per month and 40% conversion to completed credit-funded replacement orders. There are no pilot results, merchant commitments, or measured redemption rates. The same 40% assumption drives the retained-sales forecast and the retention story; these are not separate pieces of demand evidence.

For this simplified model, each completed replacement order has $100 of sales and $70 of ordinary goods and fulfillment costs, leaving $30 before the feature's additional costs. Every such order also incurs the $20 incentive and $12 of additional return handling. There are no other savings, recoveries, or offsets in the supplied model.

## Business case

Thirty merchants would generate 1,500 eligible events and 600 converted orders per month. We forecast $60,000 of retained sales and call $18,000 of this retained profit, calculated as 600 × $30. We book incentives to marketing and additional handling to operations, outside this reported retained-profit figure.

The proposed merchant fee is $49 per month, or $1,470 monthly platform revenue at 30 paying merchants. That fee is separate from merchant order economics; it is not additional merchant profit. No platform support-cost estimate is available yet.

## Delivery and success gates

Spend the first four weeks integrating offers, four testing redemption and refunds, and four onboarding merchants. The launch gate is 40% conversion and at least $15,000 of monthly retained profit as defined above. Neither accounting reconciliation nor a refund-only comparison group is currently a gate.

If conversion falls short, the proposed response is to increase the bonus to $30 without changing the launch budget. That incentive increase is a proposed remedy, not an approved pricing decision.

## Stakeholder choices still needed

Should the decision remain a full launch, or become a capped measurement pilot? What contribution-margin definition should control the release gate? Any change to the bonus, fee, or commitment needs an explicit choice, not just a rewritten forecast.
