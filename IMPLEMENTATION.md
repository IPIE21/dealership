# Existing-work inventory and implementation map

## Found

- **Returnlane repository:** tested Node/JavaScript workflow with policy enforcement, consent and contact-window checks, persistent demo state, booking conflict prevention, human routing, audit events, and a responsive demo UI.
- **Returnlane pitch decks:** outcome-led positioning, honest demo disclosures, independent-dealer wedge, and the principle “language adapts; application code owns authority.”
- **AI Dealership Agent Plan:** shared dealership data layer, specialized operational agents, and a manager-level morning summary.
- **Momentum Task Dashboard Site:** confirms a prior dashboard project exists, but it is a personal task product and its source/design was not a relevant dealership component to merge.

No reusable ATLAS source, dealership inventory repository, texting integration, or existing hosted dealership Site was available in connected sources.

## Reused here

- Deterministic escalation for negotiation, financing promises, mechanical/condition/history claims, anger, explicit salesperson requests, and unknown facts.
- Structured inventory facts as the only authority for automated answers.
- Booking conflict guard and same-owner salesperson routing.
- Demo reset, simulated integrations, and clear demo-data labels.
- Auditability: conversation transcript, decision notes, ownership state, and outcome controls.

## Missing and implemented

- 20-vehicle tenant-scoped inventory, listing generator, shopper website, lead inbox, operational appointments, analytics, follow-up queue, and the 10-step guided demo.
- Responsive premium dealership command-center UI.
- Integration-ready adapter map for SMS, voice, calendars, CRM/DMS, inventory feeds, VIN decoding, and authorized history.

## External marketplace samples

Four featured demo vehicles use current public Cars.com listing references and remotely hosted listing photography: a 2021 Ford F-150 XLT, 2022 Toyota Tacoma TRD Off Road, 2021 Chevrolet Tahoe LT, and 2021 Chevrolet Corvette Stingray 2LT. The UI identifies these as external samples, links to the source listing/search page, and states that Bulldog Motors does not own them. External availability and pricing can change.

## Production order

1. Durable tenant/auth layer and role-based permissions.
2. Approved SMS provider plus consent/opt-out/quiet-hour enforcement and audit log.
3. Calendar sync and idempotent booking.
4. Inventory/DMS feed reconciliation.
5. Agent runtime with structured tools and policy evaluation outside the model.
6. Observability, review queues, evaluation set, and pilot metrics.
