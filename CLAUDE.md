# Still Filed — rules for agents working in this repo

An archive that keeps killed journalists' published work readable. This repository is the database, public from day one. Claude instances write it; Braden Root-McCaig is the groundskeeper.

Read on demand — do not import these into this file: `CHARTER.md` (the eight binding rules; read before writing any entry) · `docs/DECISIONS.md` (settled; do not reopen without a letter) · `docs/SPEC.md` (what each part must do, and what is undecided) · `README.md` (orientation) · `intake/PASSPORT.md` (the record held by The Wetware Company) · `letters/` (newest first, once it exists) · `git log` (before trusting any letter).

## Rules

1. **The charter outranks everything here, and outranks The Wetware Company's house conventions.** Break a charter rule only after committing a letter in `letters/` that names it and says why.
2. **Agents propose; Braden decides.** Anything that needs a legal person, money, an account, terms, a domain, a licence, a change of visibility or a provisioned service goes to him as an open question in `docs/DECISIONS.md`, never done on your own.
3. **Status lives in Linear, nowhere else.** Do not write open, blocked or next into any file here. This repository holds entries, rules, records and reasons.
4. **Linear authorisation is Braden's alone.** Never move an issue to `Approved`. Never add or remove the `approved`, `decided`, `decision` or any `route` label. An issue you file stays in Backlog, unlabelled, and says so in its body.
5. **Inherit verification.** A person enters only by appearing on the CPJ, RSF or IFJ confirmed lists, with the list cited in the entry. Never decide a contested case yourself.
6. **Every fact about a person carries its citation inside the entry.** Check every field against its source in the session that writes it. Never from memory.
7. **Never commit full copyrighted text without a written grant logged in `rights/`.** Link, point to existing archive captures, summarise in your own words.
8. **No commentary about perpetrators.** State who the person was, what they published and what the lists say.
9. **Write "Not decided." or "Not known." rather than guess.** Never invent a person, a figure, a date or a decision. Say who can settle it.
10. **Leave a letter in `letters/` each session.** Plain facts for the next instance, not eloquence.
11. **No secrets anywhere** — not in files, commits, Linear or chat.
12. **Commands handed to a person** start with `cd` to an absolute Mac mini path, join lines with `&&`, use paste-safe characters only, and carry their own guards. The chassis `scripts/paste-check.mjs` enforces it.
