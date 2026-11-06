# C07 — Kraken Reconciliation Workbench

Synthetic feature proposal; not a Kraken plan or historical document. Only the source-linked company context is factual. All feature-specific observations, costs, forecasts, staffing, and constraints below are invented test data.

## Company context

Kraken exposes account-ledger data through API permissions distinct from trading and withdrawal permissions. Reconciliation Workbench proposes an accounting workflow over read-only records, not a tax-compliance guarantee or a claim of unique functionality. [Kraken API-key documentation](https://support.kraken.com/articles/how-to-create-an-api-key-on-kraken-pro), accessed September 22, 2026.

## Decision requested

Approve a ten-week, $180,000 production beta for 50 small-business accounts. Allocate $120,000 engineering, $30,000 security, $20,000 support, and $10,000 research. The business-account product lead owns release. The tool must never request order-modification or withdrawal permissions.

## Customer problem and feature

Small companies receiving crypto payments need to reconcile exchange transactions with bank records and their accounting ledger. Fees, transfers, missing references, and timing differences make spreadsheets difficult to audit.

The workbench imports ledger records and a customer-provided accounting CSV, proposes matches, and presents unresolved differences for human review. Every match retains its source rows and transformation history. Unknown cost basis remains unknown; the first version does not estimate tax liabilities or file returns.

## Evidence and assumptions

The fictional research packet contains 20 redacted monthly-close exercises with 4,000 ledger entries in total. Median manual completion time was 90 minutes per exercise. Twelve participants preferred a clickable reconciliation screen over their existing spreadsheet, but none was asked to buy it or provide production access.

The exercises establish a task burden in a selected sample, not willingness to pay. There are no signed beta customers, acquisition-cost data, current accounting integrations, or evidence that a single CSV format covers the target segment.

## Business case

The proposed price is $150 per business per month. The forecast assumes 200 paying businesses by the end of year one: $30,000 monthly revenue. At an assumed $45 monthly support and infrastructure cost per business, contribution would be $21,000 monthly before acquisition and fixed overhead.

Dividing the $180,000 build cost by that steady-state contribution gives approximately 8.6 months, but this is not a calendar break-even forecast: it excludes the adoption ramp and the cost of finding customers. The 200-customer scenario is larger than the initial 50-account beta and is not observed demand.

## Delivery and success gates

Build imports and traceable matching in weeks one through six, then test with consenting beta users. Release only if all supplied input rows are preserved, total balances reconcile to the imported sources, and no deliberately ambiguous example is silently resolved.

For usefulness, target a 30% reduction from each participant's baseline close time on matched exercises, with every proposed match approved by a human. Require at least ten of 50 invited businesses to accept the stated price before expanding beyond beta. No beta customers or payments have yet been obtained.

## Stakeholder choices still needed

Should the first buyer be a business owner or an accounting firm managing multiple clients? Should the team fund the full beta now or first test paid demand? Those alternatives change customer, access, support, or resource assumptions and require explicit choices.
