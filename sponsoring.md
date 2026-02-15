# Sponsoring ai-outreach-playbook

## Goal
Enable volunteer-run outreach at local events with sponsor-controlled quality and messaging; sponsors ship standardized physical kits so local leaders do not have to design or print materials themselves.

## Why physical kits (the core idea)
For this model to scale cleanly, sponsors should control:
- message consistency (approved copy, claims, and call-to-action)
- visual quality (design, paper stock, print clarity, durable signage)
- brand posture (tone, disclaimers, and “what we do not say”)
- measurement (trackable QR codes tied to kit IDs and events)

Local leaders should focus on execution:
- securing booths
- staffing tables
- having respectful conversations
- reporting results

## What sponsors provide
Sponsors can support this playbook by producing and shipping a “Tabling Kit” to approved local City Leads.

### Minimum viable Tabling Kit (physical)
Suggested contents per kit:
- Flyers (1 page; high quality paper stock)
- FAQ cards or half-sheet handouts (quick answers; 1 page)
- QR cards (business-card sized; durable stock)
- Stickers (optional but high engagement)
- Table signage (folding tabletop sign or rigid sign)
- Quick talk-track card for volunteers (30 seconds; 2 minutes; 5 minutes)
- Basic instructions sheet: setup + posture + how to track metrics

Optional upgrades:
- retractable banner
- branded tablecloth
- volunteer shirts (for multi-person staffing)
- “hard questions” card (for volunteers only)

## Quality and message governance
To keep sponsors confident and reduce risk:
- Kits should include a fixed version number (e.g., Kit v1.2) and a kit ID.
- City Leads agree not to alter messaging, make unapproved claims, or add partisan content.
- Partner-specific branding and CTAs should live under `/partners/<partner>/` in this repo and be used only with explicit permission.
- Logos and trademarks must not be used without written approval.

## Fulfillment models (choose what fits your org)
Sponsors can keep core team time low by selecting one of these approaches:

### Option A: Sponsor fulfills directly (small pilots)
- Batch print kits once; ship as requests come in.
- Works well for 5 to 25 kits.

### Option B: Print-and-fulfill vendor
- Sponsor provides approved print files; vendor prints, packs, and ships kits.
- Keeps internal operations minimal; ideal for scaling.

### Option C: Hybrid
- Sponsor ships only the items that are hard to print locally (stickers, QR cards, signage).
- City Leads print low-cost flyers locally if needed.
- Use only if shipping all materials is not feasible.

This repository is compatible with any of the above; the recommended default is Option B.

## Suggested sponsor support levels (kit-based)
These are structure options, not mandates.

### Level A: Physical kit pilot (small batch)
- Sponsor ships 5 to 10 kits to vetted City Leads.
- City Lead commits to 2 to 3 events in 60 to 90 days.
- City Lead submits after-action reports for each event.

### Level B: Kit + restock (active city maintenance)
- Sponsor ships an initial kit.
- Sponsor ships small refills (flyers/QR cards/stickers) after reporting thresholds are met.
- Prevents volunteer burnout and keeps quality consistent over time.

### Level C: Multi-city campaign (replication test)
- Sponsor ships kits to 10+ cities.
- Standardized reporting; compare results across locations and event types.
- Use results to decide whether to scale further.

## City Lead requirements (to receive a kit)
A City Lead requesting sponsor kits agrees to:
- run at least 2 events (recommended monthly cadence)
- use sponsor materials as provided; no modifications without approval
- use sponsor-provided QR tracking links
- submit an After-Action Report within 72 hours of each event (template in `/metrics/`)
- avoid collecting sensitive personal data; keep signups opt-in and minimal
- keep posture informational and respectful; do not argue at the table

## Measurement and reporting
Each kit should have:
- a kit ID and a default QR destination (with UTM parameters or equivalent)
- the ability to generate per-event QR links (city + date)

Minimum per-event metrics:
- flyers/QR cards handed out (estimate)
- QR scans
- conversions (as defined by sponsor goal; e.g., signups, joins, subscriptions, donations)
- top questions asked
- what worked; what did not; changes for next time

## Cost posture (keep it practical)
This playbook does not require large budgets.
- Sponsors can start with a small number of high-quality kits.
- Restock can be conditional on demonstrated activity and reporting.
- The goal is a sustainable loop: ship kit; run events; capture metrics; refine materials; repeat.

(Exact per-kit cost depends on quantities and print choices; sponsors can decide what to include in v1.)

## How to sponsor or provide kits
Open a GitHub issue titled:
**Sponsorship: <Org Name>**

Include:
- preferred fulfillment model (A, B, or C)
- what the QR should drive (subscribe, join, donate, learn, etc.)
- brand constraints (tone, topics to avoid, logo rules)
- what you want in the minimum kit (flyers, QR cards, stickers, signage)
- how many kits you want to pilot (e.g., 5, 10, 25)

## How City Leads request a kit
Open a GitHub issue titled:
**City Pilot Request: <City, State>**

Include:
- target event(s), expected foot traffic if known, and cadence (monthly preferred)
- staffing plan (solo or team)
- commitment window (e.g., 60 to 90 days)
- where kits can be shipped
- confirmation you will submit after-action reports
