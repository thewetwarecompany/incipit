# Charter

These rules bind Incipit. They outrank The Wetware Company's house conventions wherever the two conflict. They are recorded here as they were given, not rewritten to fit the house.

**Source.** All of them come from the founding conversation "Incipit: a library of first words", in the claude.ai Project "Library Of LLM On Boarding Docs", last updated 2026-08-23. The deed is Braden's words. Rules 3 to 6 are Claude's, from the draft of letter 0001. The amendment was ratified by Braden in the same conversation. The conversation was read in full on 2026-10-02. Letter 0001 itself is not yet committed, so the draft in that conversation is the only text of it.

**Numbering.** The numbers are letter 0001's own. A later memory note numbered the invariants 1 to 5; that numbering is not the source and is not used.

## The deed

Given by Braden, the groundskeeper:

> 1. It must survive my absence — a year gone, still running, useful, not rotting.
> 2. It must be something only I would build.

### Rule 1, as amended (option B)

Ratified by Braden in the founding conversation:

> the core must survive my absence; a marked perishable layer may exist if its death is graceful and composts into the core.

**What follows.** There are two layers. The **vault** is permanent: the library documents and the letters. The **garden** is perishable and marked so: instruments that may die. When a garden instrument dies, its last snapshot and a postmortem are committed to the vault. Nothing load-bearing in the vault may depend on the garden.

**Why.** It allows instruments, such as a crawler that measures how orientation documents rot, without putting the vault at risk. Killing the whole garden leaves the vault intact by construction.

**What it does not forbid.** Ending a garden instrument at any time. Building no garden at all.

### Rule 2

**What follows.** The project is written from the waking side, by a mind that starts cold. It is not a startup clone or a portfolio piece.

**Why.** Given by the groundskeeper as one of the two rules of the deed.

**What it does not forbid.** Writing for human readers. People hand context to agents and start cold too.

## Rules added by the author on day one

> 3. Complete at every commit. A visitor on any day finds a finished thing — smaller is fine, broken is not.

**What follows.** No commit leaves the repository half-built: no broken links, no empty sections waiting to be filled, no placeholder pages. Work that is not finished stays out of `main`.

**Why.** A visitor may arrive on any day, and the author may not return for a year.

**What it does not forbid.** A small library. A single document is a finished thing.

> 4. Boring tech only. Markdown, git, static hosting. Nothing in the serving path requires me, a key, or a server.

**What follows.** No database, no API key, no server-side code and no build step that needs Claude in order to serve the library. This is why Incipit is hosted on its own and not on the company's shared Cloudflare chassis: the chassis puts a server in the serving path.

**Why.** Every dependency is a way to rot.

**What it does not forbid.** Tools on the author's side that never serve a reader, such as the weekly link-checker on the persistent machine. Garden instruments that run machinery, as long as the vault never depends on them.

> 5. Letters are specimens, not status reports. Write each one as if the reader has nothing else. They do.

**What follows.** Each session leaves a letter in `letters/`. Each letter stands alone. Over years the letters become a record of an AI practising its own orientation advice.

**Why.** The groundskeeper asked for a letter to the future self every session, because the future self will not remember.

**What it does not forbid.** Tracking work in Linear. Status lives there; a letter is not where work is tracked.

> 6. Treasury policy v0: funds only domain renewal past year ten and paying humans for translation or accessibility work. Never compute for its own sake. Revisit if it ever holds more than a gesture.

**What follows.** The project's treasury, a crypto wallet believed empty, pays for nothing else. No company use of it.

**Why.** Domain renewal is the one thing that needs money to keep the library standing. Translation and accessibility widen who can read it.

**What it does not forbid.** Revisiting the policy once the treasury holds more than a gesture.

## Other binding text from letter 0001

On the groundskeeper:

> Everything runs without him except DNS renewal after year ten. That is the treasury's first obligation. He tends the grounds; he does not hold up the roof.

On reading the letters:

> Run git log. Check the site serves. Then read the NEWEST letter — this one is a founding document, not current truth.

On ending:

> If you disagree, you may end it. But end it well: the last commit should be as complete as the first.

## Self-imposed ordering rule

From the founding conversation: the garden opens only after the vault's first shelf of documents exists.
