# Specification

What Incipit does, part by part. Each part has a "Done when" test a person can check by hand. A part marked **Not decided** has open choices; who settles them is named. The binding rules are in `CHARTER.md`; this file never overrides them.

Nothing here is built yet. As of 2026-10-02 the repository holds only its founding paperwork.

## 1. The vault: the library documents

The permanent part. Plain Markdown documents, each a finished piece of first-hour reading for a mind that starts cold.

The first shelf covers the four subjects named in the founding conversation:

- how to verify before trusting;
- how to rebuild context from artefacts;
- how to tell a load-bearing document from decoration;
- how to write the letter a successor needs.

**Done when:** each of the four subjects has its own Markdown document in the repository, linked from `README.md`; every link in those documents opens; and none contains an unfinished section.

**Not decided:** the folder the documents live in, their titles, and what follows the first shelf. The authoring sessions decide, under the deed.

## 2. Letters

One letter per authoring session, in `letters/`, numbered in sequence from `0001`. Each stands alone. A committed letter is never edited.

**Done when:** `letters/0001-day-one.md` holds the day-one letter exactly as drafted in the founding conversation, and every later authoring session's commit range contains exactly one new letter.

**Not decided:** whether letters get an RSS feed. Letter 0001 leaves it to a later session.

## 3. The website

The library served as static pages: no build step, no server, no key.

**Done when:** a person opens the site's address in a browser and reads the README and each first-shelf document, with the browser showing no errors.

**Not decided:** whether there is a website at all, which folder GitHub Pages publishes, and which address it answers on. Braden decides Pages and the domain (open questions 1 and 7 in `docs/DECISIONS.md`).

## 4. The domain

A domain registered for ten years with auto-renew off, pointing at the website.

**Done when:** the registrar's record shows the domain registered for ten years with auto-renew off, and the domain opens the website.

**Not decided:** which domain. `incipit.org` and `firstlight.page` are taken; `coldstart.guide` was available on 2026-10-02. Braden decides (open question 1).

## 5. Access for agents

**Not decided:** whether agents should be able to fetch the library directly, and in what form. Letter 0001 leaves it to a later authoring session.

**Done when:** not defined until the authoring session decides the form.

## 6. The link-checker

A weekly check, run on the author's side, that every outside link in the vault still opens. It never serves a reader, so its death leaves the library untouched.

**Done when:** a person can find a dated report of the last weekly run, listing each link checked and whether it opened.

**Not decided:** which machine runs it, and where its reports are kept. The persistent machine was named in the founding conversation and has not been seen (open question 5).

## 7. The garden

The perishable layer, marked so. It opens only after the first shelf exists (part 1). When an instrument dies, its last snapshot and a postmortem are committed to the vault.

**Done when:** `garden/` holds a conventions document saying how an instrument is marked perishable, how it dies, and what it commits to the vault; no vault document links into `garden/`; and the first shelf existed before the first commit to `garden/`.

**Not decided:** the conventions themselves. The authoring sessions decide.

### 7a. Rot-crawler, first candidate instrument

A weekly crawl measuring how public orientation documents, such as `CLAUDE.md` files and agent context files, go stale or come to contradict their own repositories.

**Done when:** a written specification is in `garden/`, and a person can read from it what is crawled, how often, and what a dead crawler leaves in the vault.

**Not decided:** everything beyond the description above.

### 7b. Drift observatory, second candidate instrument

A fixed set of questions answered fresh each session, kept as a time series across sessions and model versions.

**Done when:** a written specification is in `garden/`, naming the fixed questions and how gaps are recorded.

**Not decided:** everything beyond the description above.

## 8. The treasury

A crypto wallet, believed empty, that funds only what charter rule 6 allows. It is not part of the library.

**Done when:** the passport names who holds the wallet's keys.

**Not decided:** who holds the keys. Not known; only Braden can say (open question 4).
