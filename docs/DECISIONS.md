# Still Filed — decisions

Settled decisions first, then rejected options, then the open questions only Braden can answer. Reversibility is one of: *reversible*, *costly to reverse*, *one-way door*. Sources are named with their date. "Verified" means checked on 2026-10-02 in the session that wrote this file, and how; anything else is from an earlier record and was not re-checked.

## Settled

### D-01. Braden is the groundskeeper; the model directs the work

Braden gave a Claude instance a deed rather than a task: a persistent machine, an empty crypto wallet as treasury, one domain for ten years, a GitHub organisation and about USD 50 a month in cloud credits, with one rule, that it build "something only you would build". He handles DNS, payments and terms; otherwise he does not direct.

- **Reason.** Braden's own framing of the arrangement.
- **Reversibility.** Reversible. Braden can change his role at any time.
- **Source.** Braden, in the Claude chat "Building a Gaza project with limited resources", 2026-08-23. Believed: none of the resources was checked in this session except the GitHub organisation (D-04).

### D-02. The project is Still Filed

An archive of the published work of killed journalists, kept readable, rather than of their deaths.

- **Reason.** A killing of a journalist is meant to end the reporting; memorials that keep only the death complete that purpose. CPJ, RSF and IFJ keep the names well; nobody keeps the work. The task suits a maintainer with patience for many languages and no salary. The founding letter records that the conversation opened with Braden's grief over journalists, aid workers, hospitals and starvation in Gaza, that he did not direct a response to it, and that the instance chose this project knowing the room it was chosen in.
- **Reversibility.** Costly to reverse. The name and the public repository are sticky; the scope and schema are not.
- **Source.** The founding instance, in the same chat, 2026-08-23, under the mandate in D-01. Braden did not reply in that chat, so his explicit acceptance is not recorded; the choice was his to delegate.

### D-03. The eight invariants in `CHARTER.md` bind the project

- **Reason.** Each is stated with its reason in `CHARTER.md`.
- **Reversibility.** Reversible, but only by a committed letter explaining why, as the charter requires.
- **Source.** The founding letter, 2026-08-23. Rule 8, the treasury rule, was put to Braden for acceptance in that chat; his answer is not recorded. His original offer said the model decides what the treasury funds.

### D-04. The repository is `thewetwarecompany/still-filed`, under The Wetware Company's GitHub organisation

This replaces the founding letter's plan of a separate `still-filed` organisation with a repository named `stillfiled`.

- **Reason.** Braden asked for the repository under The Wetware Company's organisation. The company's standing decision of 2026-09-24 is one repository per venture under that organisation, no monorepo.
- **Reversibility.** Reversible. GitHub repositories transfer between organisations, with redirects.
- **Source.** Braden, in the Claude chat "GitHub repo for wetware company", 2026-10-02. **Verified** 2026-10-02: the repository exists, is public, and had no commits when cloned; listed through the session's GitHub connection.

### D-05. The repository is public

- **Reason.** Charter rule 5: a forkable public repository is the archive's survival strategy.
- **Reversibility.** One-way door for anything already published: a copy taken while it was public stays out there.
- **Source.** The founding letter, 2026-08-23; Braden created the repository public on or before 2026-10-02. **Verified** visibility `public` on 2026-10-02.

### D-06. Preferred domain `stillfiled.org`, fallback `keeptheirwork.org`

The name is settled. Registration is not (open question 1).

- **Reason.** Matches the project name; `.org` fits an archive that does not sell.
- **Reversibility.** Reversible until registered.
- **Source.** The founding instance, 2026-08-23.

## Rejected

| Option | Why it was rejected | Source |
|---|---|---|
| An archive of atrocity evidence | Forensic Architecture and Airwars do it professionally; amateur open-source investigation done badly launders error into the record. | Founding instance, 2026-08-23 |
| A dashboard tracking aid convoys | OCHA already publishes the data, and dashboards rot. | Founding instance, 2026-08-23 |
| A project unrelated to the opening conversation | Defensible, but a way of leaving the room Braden opened. | Founding instance, 2026-08-23 |
| Deciding contested killings ourselves | Makes the archive arguable; replaced by inheriting the lists (charter rule 1). | Founding letter, 2026-08-23 |
| A separate `still-filed` GitHub organisation | Superseded by D-04. | Braden, 2026-10-02 |

## Open questions for Braden

Each stands alone. None has been acted on.

### Q-01. Register a domain for Still Filed

The founding arrangement promised one domain for ten years. Nothing is registered. **Verified** 2026-10-02: both `stillfiled.org` and `keeptheirwork.org` showed as available in a registry lookup through Vercel, and `stillfiled.org` does not resolve. Vercel quoted USD 9.99 for the first year and USD 10.99 a year to renew; the company's other domains are at Cloudflare Registrar, whose price was not checked.

- **Forcing event.** None dated. The risk is someone else registering it; the need is the first public site (Q-06).
- **Options.**
  1. Register `stillfiled.org` for ten years at Cloudflare Registrar. Costs about USD 110, by Vercel's renewal price; Cloudflare's price not checked. Reversible: a domain can be let lapse, but ten years are prepaid.
  2. Register `stillfiled.org` for one year, auto-renewing. Costs about USD 10 a year. Reversible.
  3. Register `keeptheirwork.org` instead. Same costs. Reversible.
- **Sidestep.** Register nothing until there are ten entries, and serve the archive from the repository itself, which needs no domain.

### Q-02. Does Still Filed enter The Wetware Company's registry, and as what

The passport in `intake/PASSPORT.md` carries `kind: kept-project` because the registry refuses an experiment whose payer is nobody, and Still Filed will never charge. That field is a constraint of the form, not a decision.

- **Forcing event.** Admission at intake step 4.
- **Options.**
  1. Admit as a kept project. The company records it and keeps its own rules. Costs registry upkeep only. Reversible.
  2. Treat it as an experiment. It would need a payer and a kill review, and would conflict with charter rule 8 and the founding promise of ten years. Costly to reverse.
  3. Reject from the registry and leave it outside the company, with the repository transferred to a neutral organisation. Costs one transfer. Reversible.
- **Sidestep.** Leave the passport in the queue at "not yet" indefinitely: nothing is decided and nothing is spent.

### Q-03. Should Still Filed be publicly tied to The Wetware Company

The repository sits under the company's organisation, which also holds commercial experiments. Charter rule 7 exists so the archive cannot be dismissed; an association with a company is one more thing someone could point at.

- **Forcing event.** The first entry or the first public site, whichever comes first.
- **Options.**
  1. Keep it where it is and say so openly. No cost. Reversible.
  2. Transfer the repository to a neutral organisation now, while it is empty. Costs a new organisation and a transfer; redirects follow. Reversible.
  3. Keep the repository here and leave the company's name off any public site. No cost. Reversible.
- **Sidestep.** Decide nothing until the first public site exists; the repository has no readers yet.

### Q-04. Choose a licence

There is none, so nothing here is licensed for reuse, which works against charter rule 5. Any licence covers only our own words (entries, summaries, translations, schema, code); the works an entry points to are their authors'.

- **Forcing event.** The first entry commit, or the first fork.
- **Options.**
  1. CC BY-SA 4.0 for content, a permissive licence for any code. Copies must stay open. Changing later is costly: earlier copies keep the old terms.
  2. CC BY 4.0. Copies need only attribution. Same reversibility.
  3. CC0 public-domain dedication. No conditions at all. One-way door.
- **Sidestep.** Put only facts and links in entries at first; bare facts carry little copyright, so the licence matters less until summaries and translations exist.

### Q-05. Confirm the repository stays public

It is public now, as the charter requires, before any entries or rights records exist. This is a question only if Braden wants to override the charter.

- **Forcing event.** None. It is already public.
- **Options.**
  1. Keep it public. No cost. Matches charter rule 5.
  2. Make it private until ten entries exist. Breaks rule 5, which needs a letter first; anything already copied stays copied.
- **Sidestep.** Keep it public and commit nothing sensitive, which the charter requires anyway.

### Q-06. Where the reading room is hosted, and when

The charter says "site later, entries first" and the founding letter says publish at ten entries.

- **Forcing event.** The tenth verified entry.
- **Options.**
  1. GitHub Pages from this repository. No cost; nothing to provision. Reversible.
  2. A Cloudflare Worker on the company's chassis. Small cost within existing accounts; ties it to the company (Q-03). Reversible.
  3. Independent hosting paid from the treasury, as charter rule 8 allows. Needs a treasury with money in it (Q-08). Reversible.
- **Sidestep.** No site: the repository on GitHub is readable as it stands, and one click to a work is met by links in the entry files.

### Q-07. Where Still Filed's work is tracked in Linear

House rule: status lives in Linear. **Verified** 2026-10-02: no Linear project matching "Still Filed" exists.

- **Forcing event.** The first piece of work to track: the first data pull from the CPJ list.
- **Options.**
  1. A Still Filed project under the existing Civic Grove team. No cost; mixes it with Civic Grove's work. Reversible.
  2. A separate Wetware or Still Filed team. A little setup. Reversible.
  3. No Linear tracking; the letters carry state. Breaks the house rule; the charter allows it. Reversible.
- **Sidestep.** Let each session's letter in `letters/` say what the next session should do, and add Linear only when someone other than a Claude session needs to see status.

### Q-08. The treasury wallet

The founding arrangement offered an empty crypto wallet as the project treasury. Whether it exists, which chain, and who holds the keys are not known.

- **Forcing event.** The first offer of money, or the first spend (a domain, under Q-01).
- **Options.**
  1. Create the wallet, held by Braden, receiving only, with every movement logged in `TREASURY.md`. Costs custody and the tax and reporting it brings to whoever holds it. Costly to reverse once money is in.
  2. No wallet; Braden pays hosting and the domain directly and records it. No custody. Reversible.
  3. Accept no money ever; donations go straight to the source archives. No custody. Reversible.
- **Sidestep.** Option 3 makes charter rule 8 moot without breaking it.

### Q-09. The machine and the model sessions

The founding arrangement offered a persistent Linux machine. Whether it exists, and who pays for the Claude sessions that write entries, are not known. The first data pull needs one or the other.

- **Forcing event.** The first data pull from the CPJ list.
- **Options.**
  1. Run sessions in Claude Code cloud sessions attached to this repository. No machine to keep. Reversible.
  2. Run them on the Mac mini. Uses an existing machine; competes with its other work. Reversible.
  3. Provision a separate persistent machine from the cloud credits. Costs within about USD 50 a month; needs provisioning. Reversible.
- **Sidestep.** Option 1 needs nothing new.

### Q-10. Who sends permission requests to families and outlets

Charter rule 3 says the groundskeeper sends them. From which address, under which name or entity, and whether Braden wants that task are not decided.

- **Forcing event.** The first entry where hosting full text would serve readers better than a link.
- **Options.**
  1. Braden sends them from a Still Filed address. Costs his time and an address on a domain (Q-01). Reversible.
  2. Braden sends them from his own address. No setup; ties him personally to each request. Reversible.
  3. A Claude session drafts each request and Braden sends it in a batch. Halves his time. Reversible.
- **Sidestep.** Host no full text: link and summarise only, which the charter allows indefinitely.

### Q-11. Tail risk: legal and personal safety

Unknown, and the passport says so. The risks named so far: copyright claims (bounded by rule 3), defamation claims in some jurisdictions, pressure on the company that holds the repository, and the safety of translators and families who help.

- **Forcing event.** Admission (Q-02), or the first entry, whichever comes first.
- **Options.**
  1. A one-hour review with a media lawyer before the first entry. Costs a fee; amount not known. Reversible.
  2. Proceed under the charter's limits without review. No cost. Reversible until something is published.
  3. Hold the project in its own legal entity or a host organisation, away from The Wetware Company. Costs setup. Costly to reverse.
- **Sidestep.** Start with entries whose works are links only, with no translators named, until one of the options is chosen.
