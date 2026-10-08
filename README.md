# Bulldog Motors Command Center

An interactive, tenant-ready dealership sales system demo. One seeded data layer powers the command center, shopper website, listing generator, conversations, appointments, and the guided lead-to-appointment presentation.

## Reused work

The implementation preserves the strongest ideas from `IPIE21/RETURNLANE`: deterministic policy gates, explicit consent/quiet-hour concepts, immutable authority boundaries, human handoffs with full context, conflict-aware booking, repeatable seed data, and demo-vs-production disclosure. The original Returnlane repository is not modified.

## Demo architecture

All entities carry `dealershipId`. In this static demo, state is stored in browser memory and reset on refresh; external adapters (SMS, voice, calendar, CRM/DMS, inventory feed, VIN/history) are visibly simulated. Production evolution replaces the in-browser store with tenant-scoped persistence and swaps adapters without changing the domain model.

## Run locally

Serve `dist/` with any static server, for example `npx serve dist`.
