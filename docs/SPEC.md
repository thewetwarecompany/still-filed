# Still Filed — specification

What the archive does, part by part. Each part has a "Done when" test a person can check by hand. A part marked **Not decided** has an intent from the founding letter but no settled design; whoever settles it records the decision in `docs/DECISIONS.md`. The rules every part obeys are in `CHARTER.md`.

Nothing below is built. As of 2026-10-02 the repository holds documents only.

## 1. Inclusion from the confirmed lists

Who gets an entry. A person is included only if CPJ, RSF or IFJ lists them as a confirmed killed journalist (charter rule 1).

- **Decided.** The three sources, and that inclusion is inherited, never judged.
- **Not decided.** Which exact list or database view from each organisation counts as "confirmed", how often the lists are re-read, and what happens to an entry if a list later removes the person.
- **Done when.** A person picks any entry at random, follows its list citation, and finds that person on that list.

## 2. The entry format

One file per person in `people/`, defined in `schema/`.

- **Decided.** Every fact about the person carries its citation inside the entry (rule 2). No commentary about who killed them (rule 7).
- **Not decided.** File format, field names, how a person with several names or scripts is keyed, and how a draft is marked.
- **Done when.** A person opens any entry and finds a source next to every fact about the person, and no sentence about a perpetrator.

## 3. The works

The heart of each entry: the person's published work.

- **Decided.** Links to the works where they live; links to existing archive captures; no full copyrighted text without a logged grant (rule 3). An entry is not done until a reader can start reading in one click (rule 6).
- **Not decided.** How many works an entry needs, how they are chosen, and whether the archive requests new captures from public web archives.
- **Done when.** A person opens any entry not marked draft, clicks once, and is reading something the journalist published.

## 4. Summaries

Short summaries of works, in our own words, so a reader can choose what to read.

- **Decided.** Written in our own words; facts translated, not text.
- **Not decided.** Length, and which languages summaries are written in.
- **Done when.** A person compares a summary with the work it describes and finds no copied sentence and nothing the work does not say.

## 5. Translations and native-speaker checks

- **Decided.** Translation checks by native speakers are one of the three things money may buy (rule 8).
- **Not decided.** Everything else: which languages, who checks, how a check is recorded, how checkers are found and paid, and whether checkers are named (see open question Q-11).
- **Done when.** Not decided until the workflow is. At the least: every translation shows whether it has been checked, and by what process.

## 6. Rights log

One file per permission grant in `rights/`.

- **Decided.** Every grant to host full text is logged (rule 3).
- **Not decided.** What a grant file contains, and who sends the requests (open question Q-10).
- **Done when.** For every work whose full text is in the repository, a person finds a matching grant file in `rights/`, and for every grant file, the text it covers.

## 7. Treasury log

`TREASURY.md`, every spend.

- **Decided.** Three permitted spends: hosting, donations to source archives, native-speaker translation checks (rule 8).
- **Not decided.** Whether a treasury exists at all (open question Q-08).
- **Done when.** Every line in `TREASURY.md` names one of the three permitted purposes, and the line count matches the number of spends the holder of the money can show.

## 8. Letters between sessions

One letter per session in `letters/`, starting with `letters/0001-day-one.md`.

- **Decided.** Each session leaves a letter; letters are plain and factual; a charter rule is broken only after a letter explains why; `git log` is read before a letter is trusted.
- **Not decided.** Nothing about the form. The founding letter itself is not yet committed.
- **Done when.** Every commit that adds or changes an entry is in a session whose letter is in `letters/`, and the founding letter's text matches the one written on 2026-08-23.

## 9. The first ten entries

- **Decided.** Ten entries before any site; across at least three countries; chosen by one criterion, where the published work is most recoverable; every field verified against its source before it is written.
- **Not decided.** How recoverability is measured.
- **Done when.** `people/` holds ten entries, from at least three countries, each passing the tests in parts 1, 2 and 3, and a letter states the criterion and how each was chosen.

## 10. The reading room

A website built from the repository.

- **Not decided.** Whether there is one, where it is hosted, and on which domain (open questions Q-01 and Q-06). The founding letter says site later, entries first.
- **Done when.** Not decided until the site is. At the least: every entry in the repository appears on the site, and the site can be rebuilt from the repository alone.

## 11. Survival

- **Decided.** The repository is the database and stays public; anyone can fork it (rule 5).
- **Done when.** A person with no account clones the repository and has every entry, rights file, treasury line and letter.
