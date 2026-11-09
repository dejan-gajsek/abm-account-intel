---
name: abm-account-intel
description: Turn a target account name and seller offer into a full ABM account play. Use when the user asks for account-based research, a buying committee map, warm-intro bridges, per-person outreach, a six-week touch plan, or a HubSpot signals-to-action table for one named account.
---

# ABM account intel

Build one reusable account play for a named target. Output is a brief plus a self-contained HTML play page the rep can use.

## Inputs

Required:

- Target account name (legal or trading name)
- Seller offer in one sentence (what you sell and who it helps)
- Seller company name and the sending rep's name
- Geography and compliance regime (at least CAN-SPAM; add CASL if Canada)

Optional:

- ICP tier or why this account is on the list
- Known contacts already in the CRM
- Products or systems the target already uses
- Any proof the seller is cleared to cite (named logos, numbers). If not cleared, do not invent them.

## Data sources

Use only what you can open or what the user pastes:

- Public web: company site, news, careers, leadership pages, filings, conference talks
- Enrichment tool of the user's choice (Apollo or equivalent) for titles, emails, phones
- CRM (HubSpot or equivalent) for existing contacts, engagement, Target Account flags
- Sales Navigator (run by the rep): TeamLink and mutual connections for warm bridges

Do not pretend you opened LinkedIn profiles from here if you did not. Do not invent mutual connections.

## Steps

Work in this order. Do not skip the opinion-ask rule in step 5.

### 1. Why now (15 min)

Find 4 to 6 recent signals that make this account worth a focused play. Categories that usually work: leadership change, hiring, product or stack change, growth move, season or deadline, public AI or ops investment, award or culture signal.

For each signal write:

- A short title
- What changed
- Why it matters for the seller's offer
- A real source link or citation

If a claim cannot be sourced, cut it. No made-up stats presented as real.

### 2. Our angle (with step 1)

Write one point of view sentence: how the seller helps this account given the signals.

Then list exactly three use cases. Each use case names who on the committee it is for.

### 3. Buying committee (10 min)

Map 8 to 11 people. Assign each one role from:

- Decision maker
- Economic buyer
- Influencer
- End user
- Gatekeeper

A person may hold two labels (for example decision maker and economic buyer).

Also mark a Possible Mobilizer and two Alternative Mobilizers. A Mobilizer pushes the change inside the company. Treat Mobilizer as a guess until someone acts like one.

Capture reach: email, LinkedIn, mobile, and any Do Not Call flags.

### 4. Warm intros (10 min, rep-owned)

Instruct the rep to:

1. Open each committee member in Sales Navigator
2. Rank bridges: customer, partner, company leader, former colleague, shared school or association
3. Send an intro request, wait 5 business days before cold email to that person
4. Log the bridge and answer as a CRM note

Draft an intro request and a forwardable note the bridge can send as-is.

### 5. Messages (20 min)

For each person draft:

- Email (subject + body)
- LinkedIn connection note
- Call opener

Rules for every message:

- Ask for an opinion, not a meeting
- Give an easy out ("If it's not a fit, no follow-up.")
- No links or attachments in first emails
- Append a CASL / CAN-SPAM signature: sender name, company, mailing address, working unsubscribe
- Respect DNC: no call copy for flagged mobiles
- Hold CEO outreach until someone on the committee engages
- Bring the gatekeeper in through an internal champion once a pilot is real

### 6. Six-week staggered plan

Build a week 0 to week 6 table: who, channel, what. Stagger so two people at the same company do not get the same message on the same day. Pause anyone who replies and handle by hand.

### 7. Offer ladder

Four rungs only:

1. Opinion ask
2. Share-back (only to people who answered)
3. Workshop (about 60 minutes, ranked use cases as the leave-behind)
4. Scoped pilot (one workflow, success measure agreed first)

### 8. Objections

Six likely objections with plain replies. Cover "we already have X," "we're already doing AI," "not a priority," "just send me something," security, and cost.

### 9. HubSpot signals to action

Table of signal, meaning, and the next action. Include reply, multi-open, new contact, job change, public news, and no engagement after six weeks.

List what is already done in the CRM and what still needs setup (alerts, Target Account, buying roles, non-marketing contact treatment).

### 10. Measures and guardrails

- 30 / 60 / 90 day working targets (connections and replies, first conversation and workshop booked, workshop held and qualified opportunity)
- Guardrails: CASL / CAN-SPAM, hand-dialed calls, honor DNC, one-to-one only (no marketing emails to these contacts)

### 11. Reuse table

Show how the next account takes about an hour with the same steps and owners.

## Output structure

Produce both:

1. `account-brief.md` from `skill/templates/account-brief.md`
2. `account-play.html` from `skill/templates/account-play.html`

Fill every placeholder. Keep the HTML self-contained (inline CSS and JS). Keep a working per-person message picker and copy buttons.

Mark clearly when an example is fictional. Never present invented companies, people, or results as real case studies.

## Quality checks

Before you hand the play over:

- Every why-now signal has a source
- No employer, client, or colleague names the user did not approve for this output
- No em dashes
- Prefer "use". Skip consultant verbs that mean the same thing
- Messages ask for an opinion and include an easy out
- DNC and gatekeeper rules are respected
- No made-up performance stats
- Buying committee uses the five roles above
- Mobilizer plus two alternates are named
- Offer ladder has four rungs
- 30 / 60 / 90 measures and compliance guardrails are present

## Compliance guardrails

- One-to-one sales outreach only for these contacts unless the user says otherwise
- Signature with legal name, postal address, and working unsubscribe
- Same-day opt-out handling
- No calls to numbers flagged Do Not Call
- Do not scrape or store credentials
- Do not publish real customer data in a portfolio piece; sanitize or fictionalize first
