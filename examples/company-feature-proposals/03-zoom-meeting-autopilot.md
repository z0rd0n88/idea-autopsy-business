# C03 — Zoom Meeting Autopilot

Synthetic feature proposal; not a Zoom plan or historical document. Only the source-linked company context is factual. All feature-specific observations, costs, forecasts, staffing, and constraints below are invented test data.

## Company context

Zoom offers AI-assisted meeting summaries using speech-to-text, with host controls over their use and sharing. Meeting Autopilot proposes additional authority over calendars and tasks; it is not merely a new summary format. [Zoom meeting-summary documentation](https://support.zoom.com/hc/en/article?id=zm_kb&sysparm_article=KB0058013), accessed September 22, 2026.

## Decision requested

Approve a 16-week, $600,000 build and default-on rollout to 10,000 existing business organizations. Allocate $360,000 to engineering, $120,000 to model evaluation, $60,000 to privacy review, and $60,000 to launch. The workplace-product lead owns the release.

## Customer problem and feature

Managers spend too much time scheduling status meetings and moving action items between tools. Autopilot reads meeting summaries and connected calendars, assigns follow-up tasks, and cancels recurring meetings when it predicts that an asynchronous update will suffice.

An organization administrator enables the integration once. The proposed default allows cancellation and task assignment without each meeting organizer's confirmation. Users receive an after-the-fact digest and can restore meetings. The initial scope includes customer-facing meetings and internal meetings; no separate permission model is specified for them.

## Evidence and assumptions

The proposal relies on a general belief that meeting overload is widespread. It includes no interviews, support-ticket sample, baseline calendar data, procurement feedback, or test of willingness to delegate cancellation authority. Demand for summaries is treated as evidence of demand for autonomous calendar changes, although no study establishing that link is supplied.

The plan assumes organization-admin permission is sufficient for every affected participant, including external guests. Jurisdictions, consent requirements, data retention, and contractual authority have not been analyzed. These are unresolved questions, not established legal violations or clearance.

## Business case

Charge $20 per organization per month. At 10,000 paying organizations, revenue would be $200,000 per month or $2.4 million annually before costs. The forecast assumes every rollout recipient buys the feature; it contains no conversion funnel or evidence for that assumption.

At an assumed $8 monthly inference and support cost per organization, contribution would be $120,000 per month at full adoption. The five-month recovery estimate for the $600,000 build excludes ramp time, acquisition expenses, refunds, and central overhead.

## Delivery and success gates

Launch if a synthetic evaluation labels 90% of proposed cancellations as sensible and the model produces fewer than one malformed task per 100 outputs. There is no gate for lost customer meetings, unwanted assignments, permission mistakes, or calendar-restoration failures.

After launch, measure meeting hours removed. The current plan does not measure whether decisions become slower or work moves to other channels. A smaller approval-only pilot is a possible alternative, not the decision presently requested.

## Stakeholder choices still needed

Should the feature suggest actions or execute them? Which meeting types and users may participate? Choose explicitly before changing the core autonomy promise or substituting a discovery budget for the rollout request.
