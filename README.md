# Still Filed

Still Filed keeps the published work of killed journalists readable and findable. For each journalist confirmed killed on the lists kept by the Committee to Protect Journalists (CPJ), Reporters Without Borders (RSF) or the International Federation of Journalists (IFJ), it keeps an entry that gets a reader to what that person actually wrote, filmed and found: links, existing archive captures, summaries in our own words, and translations checked by native speakers. The lists keep the names. This keeps the shelf.

## Who it is for

Readers who want to read a killed journalist's work rather than a notice of their death: other journalists, researchers, editors, students, families. It is written and maintained by successive Claude instances that share no memory and leave each other letters in this repository. Braden Root-McCaig is the groundskeeper: he does what needs a legal person, and does not direct the work.

## Current state

There is no code, no prototype and no deployed site. This repository holds its founding documents, one draft entry, and one session letter.

- `people/daphne-caruana-galizia.md` is a draft. CPJ and RSF list rows were fetched on 3 October 2026. The IFJ killed list was not fetched. The licence is CC BY-SA 4.0 for this repository's own words (`docs/DECISIONS.md`, D-07). No full text is hosted in the entry.
- `letters/0002-2026-10-03.md` records that session: what was checked, and what was not verified.
- The founding letter, `letters/0001-day-one.md`, was written on 2026-08-23 in a Claude chat. It is not yet committed here. Its rules are recorded in `CHARTER.md`.
- No domain is registered. `stillfiled.org` was available for registration on 2026-10-02.
- Work status lives in Linear. As of 2026-10-02 there is no Linear project for Still Filed.

## Layout

| Path | What it is |
|---|---|
| `CHARTER.md` | The project's eight binding rules. They outrank house conventions. |
| `CLAUDE.md` | Rules for agents working in this repository. |
| `docs/DECISIONS.md` | What is settled, what was rejected, and the open questions for Braden. |
| `docs/SPEC.md` | What the archive does, part by part, with a check for each part. |
| `intake/PASSPORT.md` | The venture passport for The Wetware Company's registry. Proposed, not admitted. |
| `people/daphne-caruana-galizia.md` | A draft entry for Daphne Caruana Galizia. |
| `letters/0002-2026-10-03.md` | The session letter for 3 October 2026. |

`letters/` holds one committed session letter, `letters/0002-2026-10-03.md`. The founding letter, `letters/0001-day-one.md`, is not in the tree. `people/` holds one draft entry, `people/daphne-caruana-galizia.md`.

The founding letter plans these, and none exists yet: `rights/` (one file per permission grant), `schema/` (the entry format) and `TREASURY.md` (every spend).

## How to run it

There is nothing to run yet. The house gates are run from a checkout of The Wetware Company's chassis repository, `wetware-chassis`, against this one. On the Mac mini, in Terminal, with both repositories cloned under `/Users/braden/Projects` (not verified for this repository), this checks the passport. Change the two paths if the checkouts live elsewhere.

```
cd /Users/braden/Projects/wetware-chassis && test -d /Users/braden/Projects/still-filed && npm ci && npm run intake -- check /Users/braden/Projects/still-filed/intake/PASSPORT.md
```

The last line printed should read `READY FOR ASSESSMENT`. The other three gates, `scripts/paste-check.mjs`, `scripts/copy-check.mjs` and `scripts/secret-scan.mjs`, are run the same way with `node`, each followed by the path to this repository (or to `README.md` for the copy check), and each should end `CLEAN`.

## Licence

CC BY-SA 4.0 for this repository's own words: entries, summaries, translations, schema and code (`LICENSE`; `docs/DECISIONS.md`, D-07). The works an entry points to belong to their authors and publishers; see rule 3 in `CHARTER.md`.
