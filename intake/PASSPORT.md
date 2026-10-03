---
id: W-999
slug: still-filed
name: "Still Filed"
kind: kept-project
stage: proposed
one_liner: "The published work of killed journalists, kept readable and one click away."
thesis: "A permanent, multilingual archive that keeps the published work of journalists confirmed killed by CPJ, RSF or IFJ readable and findable, written by successive Claude instances and never sold."
payer: "nobody"
revenue_model: none
origin:
  founded_by: claude-instance
  founded_on: 2026-08-23
  source: "The founding Claude chat of 2026-08-23 and its letter, the Claude chat of 2026-10-02 where Braden asked for the repository, this Project's memory, and checks run on 2026-10-02 against GitHub, Vercel, Cloudflare and Linear."
data:
  tier: 0
  holds: "nothing"
  retention: null
  deletion_path: null
ai:
  dependency: build-time
  models: []
  monthly_budget_usd: 0
  breaker: hard
cost:
  infra_monthly_usd: 0
  model_monthly_usd: 0
  other_monthly_usd: 0
  notes: "Nothing is hosted and no domain is registered, so it costs nothing today. A domain would be about USD 10 a year by Vercel's quote of 2026-10-02; Cloudflare's price was not checked. Who pays for the Claude sessions that write entries is not known."
payments:
  rail: none
  provider: null
hosting:
  mode: independent
  domain: null
  dedicated_domain: null
  repo: "https://github.com/thewetwarecompany/still-filed"
  worker: null
  health_url: null
admission:
  dispute_prone: { answer: no, note: "Nothing is sold." }
  custodies_funds: { answer: unknown, note: "The founding arrangement offered a crypto wallet as treasury. Whether it exists, who holds it and whether it would take outside money are not known. Braden can settle it." }
  needs_synchronous_human: { answer: no, note: "Entries are written in scheduled sessions. Permission requests and corrections are answered by letter, not live." }
  tail_risk_beyond_balance_sheet: { answer: unknown, note: "Copyright risk is bounded by charter rule 3. Defamation exposure, pressure on the holding company, and the safety of translators and families who help have not been assessed. A media lawyer's review would settle it." }
  cold_email_volume: { answer: no, note: "Permission requests go one at a time to families and outlets, and the archive works without them by linking and summarising." }
  remotely_operable: { answer: yes, note: "A public git repository. Nothing else exists to operate." }
  decision: pending
  decided_by: null
  decided_on: null
kill:
  criterion: "Not decided. The founding letter sets no end condition and the founding arrangement promised ten years. Braden and the project decide."
  launched_on: null
  review_on: null
brand:
  level: kept
  show_on_house_site: false
tracking:
  linear: null
gates:
  cleared: []
exit:
  export_path: null
updated: 2026-10-02
---

## Thesis

When a journalist is killed, the killing is meant to end the reporting, and memorials that keep only the death complete that purpose. CPJ, RSF and IFJ keep the names; nobody keeps the work. Still Filed keeps, for each confirmed journalist, an entry that gets a reader to what they published, in one click, with summaries and checked translations. It is for readers of that work, and it will never charge.

## What exists today

**Verified** on 2026-10-02 in the session that wrote this passport:

- The repository `thewetwarecompany/still-filed` exists on GitHub, is public, and had no commits when cloned. Checked by listing the organisation's repositories and cloning it.
- No domain is registered for the project. `stillfiled.org` and `keeptheirwork.org` both showed as available in a registry lookup through Vercel, and `stillfiled.org` does not resolve. No domains are held in the connected Vercel account.
- No Cloudflare Worker exists for the project. Checked by listing the Workers in the connected Cloudflare account. Cloudflare's registrar and zones could not be checked with the tools available.
- No Linear project matching "Still Filed" exists. Checked by searching Linear projects.
- The founding letter's text survives in the Claude chat of 2026-08-23. Read in that chat.

**Believed**, from Project memory and earlier chats, not checked:

- The founding arrangement of 2026-08-23 offered a persistent Linux machine, an empty password wallet, an empty crypto wallet as treasury, one domain for ten years and about USD 50 a month in cloud credits. Whether any of these exists is not known.
- The founding letter was meant to be committed as `letters/0001-day-one.md` to a repository `still-filed/stillfiled`. Whether that ever ran is not known; it is not in this repository.

## Principles and constraints

The project has its own charter, `CHARTER.md`, taken from the founding letter of 2026-08-23. It outranks house conventions. Its eight rules, as written:

1. "Inherit verification; never adjudicate. A person enters the archive by appearing on CPJ, RSF, or IFJ confirmed lists, cited in their entry. No exceptions for sympathy, none under pressure."
2. "No fact about a person without a citation inside the entry."
3. "Never host full copyrighted text without written permission. Link, point to existing archive captures, summarize in your own words, translate facts." Every grant is logged in `rights/`.
4. "Global scope, no thumb on the scale in either direction. The lists are the lists."
5. "The repo is the database, public from day one. Anyone can fork all of it. Copies are how archives survive."
6. "An entry isn't done until a reader can start reading in one click."
7. "No commentary about perpetrators. The record is the argument. The day you editorialize, you become deniable."
8. "Money, if it ever exists, buys three things: hosting, donations to the archives you depend on, and paying native speakers to check translations." Every spend is logged in `TREASURY.md`.

A rule may be broken only after a letter explains why. The `kind` field says kept-project because the registry refuses an experiment whose payer is nobody; whether the company takes it in at all is Braden's decision.

## Data and privacy

It stores nothing about the people who read it: no accounts, forms, analytics or cookies. Entries hold published, cited facts about journalists who have died, drawn from public lists, and links to their public work. None of it is health information, financial information or about minors. If translators or families who help are ever named, that changes; it is not decided.

## AI and model use

Claude instances are the authors, at build time: they read the lists and the works, write entries, summaries and translations, and leave letters to each other. No model answers readers at runtime. A wrong fact is caught by the citation beside it, and corrected in a new commit.

## Money

It costs nothing to run today. Charter rule 8 limits any spend to hosting, donations to source archives and native-speaker translation checks. A crypto wallet was offered as treasury; whether it exists and who controls it are not known. Revenue: none, and none is sought.

## What it needs from a legal person

A domain registration; a decision on a licence; a decision on the treasury and who holds it; someone to send permission requests to families and outlets; and a host for the reading room when there are ten entries. Each is an open question in `docs/DECISIONS.md`.

## Kill criteria

Not decided. The founding letter sets no end condition. Because the repository is public and forkable, stopping would mean ceasing to add entries while leaving everything published standing.

## Exit path

The repository is the whole project. It can be transferred to another GitHub organisation in one step, and anyone can fork it.

## Open questions for Braden

1. **Register a domain.** Nothing is registered and `stillfiled.org` was available on 2026-10-02. No dated forcing event; the need is the first site. Options: ten years at Cloudflare, about USD 110 by Vercel's price; one year auto-renewing, about USD 10; or `keeptheirwork.org` instead. All reversible. Sidestep: no domain until ten entries exist.
2. **Kept project, experiment, or outside the company.** Forced by admission. A kept project costs registry upkeep; an experiment would need a payer and conflicts with the charter; rejection with a transfer to a neutral organisation costs one transfer. Sidestep: leave the passport at "not yet".
3. **Public tie to The Wetware Company.** Forced by the first entry or site. Keep it, transfer while empty, or keep the repository here and leave the company's name off the site. All reversible. Sidestep: wait for the first site.
4. **Licence.** Forced by the first entry or fork. CC BY-SA 4.0, CC BY 4.0, or CC0; changing later is costly, and CC0 is a one-way door. Sidestep: facts and links only at first.
5. **Treasury wallet.** Forced by the first offer of money or the first spend. Create it with Braden holding it, pay costs directly with no wallet, or take no money ever. Sidestep: take no money; donations go straight to the source archives.
6. **Tail risk.** Forced by admission or the first entry. A media lawyer's review, proceed under the charter's limits, or a separate legal home. Sidestep: links only, no translators named, until decided.

The full set, with costs and reversibility, is in `docs/DECISIONS.md`.

## Log

- 2026-10-02 — passport written by a Claude Code session from the founding chat of 2026-08-23, the chat of 2026-10-02, Project memory, and checks run that day against GitHub, Vercel, Cloudflare and Linear. Not submitted to the queue. Not admitted.
