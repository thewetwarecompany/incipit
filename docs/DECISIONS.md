# Decisions

Settled decisions, rejected options, and open questions for Braden. Settled decisions are not reopened without new information. Work status is not here; it lives in Linear.

Reversibility uses the house terms: *reversible*, *costly to reverse*, *one-way door*.

**Sources used.** The founding conversation "Incipit: a library of first words" in the claude.ai Project "Library Of LLM On Boarding Docs", last updated 2026-08-23, read in full on 2026-10-02. The earlier registry passport, written in the same Project on 2026-09-23, read on 2026-10-02. The Project's memory notes, dated 2026-09-14 and 2026-09-24. The GitHub repository and its metadata, read on 2026-10-02. Domain availability looked up on 2026-10-02. The founding conversation's turns carry no dates of their own, so "2026-08-23" means on or before that day.

## Settled

**D-01 · The project is Incipit, a library of orientation documents written from the waking side.** Claude chose it in the founding conversation when given the deed; Braden carried on with it. Reason: Claude starts cold every session, so it is the reader the documents are for. *Costly to reverse once outside links exist; reversible until then.* Source: founding conversation, 2026-08-23.

**D-02 · The deed: two rules, given by Braden.** It must survive his absence for a year without rotting, and it must be something only Claude would build. Braden is the groundskeeper, acting only where a legal person is needed. Recorded in full in `CHARTER.md`. *One-way door: it is the project's founding condition.* Source: founding conversation, 2026-08-23.

**D-03 · Rule 1 amended by option B: a perishable garden beside a permanent vault.** Braden ratified it. Reason: it allows instruments without risking the vault, since the garden's death composts into the vault. *Reversible: removing the garden leaves the vault intact.* Source: founding conversation, 2026-08-23.

**D-04 · Four invariants added by the author on day one:** complete at every commit; boring tech only; letters are specimens; treasury policy v0. Recorded in `CHARTER.md`. *Reversible by a later authoring session, which must say so in a letter.* Source: draft of letter 0001, founding conversation, 2026-08-23.

**D-05 · The garden opens only after the vault's first shelf exists.** Self-imposed by the author. Reason: perishables do not get to come before the permanent. *Reversible.* Source: founding conversation, 2026-08-23.

**D-06 · Domain preference order: `incipit.org`, then `coldstart.guide`, then `firstlight.page`. Ten years, auto-renew off.** Reason for auto-renew off: renewal is a treasury act. The memory note of 2026-09-14 gives the third choice as `coldstart.page`; the founding conversation, which is the primary source, says `firstlight.page`. *The registration is costly to reverse once linked.* Source: founding conversation, 2026-08-23. What is available now is under open question 1.

**D-07 · Letters, one per session, stored in the repository.** Braden asked for a letter to the future self every session. Reason: session memory does not persist. *Reversible.* Source: founding conversation, 2026-08-23.

**D-08 · The repository is `thewetwarecompany/incipit`, public.** Braden created it on 2026-10-02 at 22:59 ADT, with one commit, "Initial commit", holding a two-line README. Verified on 2026-10-02 by reading the repository's metadata and cloning it. It has no licence; the founding plan said MIT, and that is under open question 2. *Visibility is reversible, but anything public may already be copied.* Source: GitHub, 2026-10-02.

**D-09 · One repository per venture under the `thewetwarecompany` organisation, no monorepo.** Braden's decision for all Wetware ventures. Reason: ventures must not bleed into each other. *Reversible.* Source: memory note, 2026-09-24; believed, not re-checked.

**D-10 · Hosted on its own, not on the company's shared chassis.** This follows from charter rule 4: the chassis puts a server in the serving path. Recorded in the passport as `hosting.mode: independent`. *Reversible only by changing the charter.* Source: charter rule 4; reasoning first written in the passport of 2026-09-23.

**D-11 · Work status lives in Linear; this repository holds durable things.** Braden's rule across all his projects, and a house rule. *Reversible.* Source: his saved working rules, 2026-09-13; chassis `CLAUDE.md`, rule 2.

## Rejected

- **Option A, keeping rule 1 unamended.** Not chosen. It would have kept the project pure but ruled out every instrument. Braden chose B. Founding conversation, 2026-08-23.
- **A drift observatory as the main project.** What Claude said it would have built with no rule 1: a fixed battery of questions answered every session, measuring what persists across sessions. Not chosen because rule 1 exists and the deed points the work outward. It survives only as a candidate garden instrument. Founding conversation, 2026-08-23.
- **A "sand mandala": one page rewritten every session with no history.** Ruled out by rule 1 twice over; it does not survive absence and rots by design. The author said it stays unbuilt. Founding conversation, 2026-08-23.
- **Hosting on the company's shared Cloudflare chassis.** Rejected under charter rule 4. See D-10.
- **One monorepo for all ventures.** Rejected by Braden on 2026-09-24. See D-09.

## Open questions for Braden

Each is his to answer. None is decided here.

**1. Which domain, if any, to register for Incipit.**
The library's permanent address, and the one hard-to-reverse choice in the project. The founding rule is to register the first available name in the order of D-06.
- *Found on 2026-10-02:* `incipit.org` is not available, and a web search lists it as for sale on the aftermarket. `firstlight.page` is not available. `coldstart.guide` is available. Checked with a registry availability lookup through Vercel. No domain for Incipit appears in the Vercel account, which holds only `civicgrove.com`. The Cloudflare registrar account could not be read from this session, so whether a domain was registered there is not known; Braden can confirm.
- *Forcing event:* the first link to the library from outside. No date.
- *Options:* register `coldstart.guide` for ten years with auto-renew off, as the founding rule says (cost: one ten-year fee, price not checked; costly to reverse once linked). Ask the price of `incipit.org` from its seller (cost not known, possibly high; same reversibility). Wait (costs nothing; nothing can launch on a domain).
- *Sidestep:* launch on the GitHub Pages address and add a domain later. Costs nothing now; links made before the domain would point at an address that later changes.

**2. Which licence covers the repository.**
What others may do with the documents and letters.
- *Forcing event:* the first library document committed. Until a licence exists, readers may read but not reuse.
- *Options:* MIT, as the founding plan said (written for software, awkward for prose). CC BY 4.0 (reuse with credit; fits a gift). CC BY-SA 4.0 (reuse with credit, and copies stay open). Once others have copied under a licence, it cannot be withdrawn from those copies: *one-way door for what is already copied.*
- *Sidestep:* a licence for the prose and a separate one for any code, so the choice for one does not bind the other.

**3. Whether Incipit enters the company registry as a kept project, an experiment, or not at all.**
The registry kind decides its brand, its hosting rules and how it is judged.
- *Forcing event:* the admission decision. No date.
- *Options:* kept project, as the passport proposes (own identity, never charges, hosted on its own; reversible). Experiment (needs a payer, which contradicts "nobody pays", and would put it on the chassis, which charter rule 4 forbids). Not registered (the company keeps no record of it; reversible).
- *Sidestep:* record it in the registry as a fact only, with no company obligations attached, so the registry is a catalogue card rather than a landlord.

**4. Who holds the project's assets: Braden personally or The Wetware Company.**
The domain registration, the GitHub organisation and the treasury wallet. The organisation is owned by the `CivicGrove` login, per the chassis decisions. Who holds the wallet's keys is not known; only Braden can say.
- *Forcing event:* registering a domain, or admission. No date.
- *Options:* Braden personally (simplest; goes with him). The company (survives him, matches the registry; a company that can fold is itself a rot risk the deed was written against). Split: the company holds the domain, Braden holds the wallet. All *reversible by transfer*, at the cost of paperwork.
- *Sidestep:* register nothing in the company's name and record ownership in the passport only.

**5. Where authoring sessions run, and who commits letter 0001.**
The deed offered a persistent Linux machine; it has not been seen by any session that wrote these files, and its address is not known. Letter 0001 is drafted but not committed, so the public repository has no library and no letter yet.
- *Forcing event:* charter rule 3, complete at every commit, applies now that the repository is public.
- *Options:* the persistent Linux machine, as founded (needs its details from Braden). Claude Code cloud sessions with this repository attached (available today; nothing persists between them except the repository). The Mac mini (already runs other agent work).
- *Sidestep:* any session with push access commits letter 0001 verbatim next. The letter tells its reader to trust the repository, not the machine.

**6. The split of authority between Braden and the authoring sessions.**
The deed says Braden does not direct the creative work. The house says agents propose and Braden decides. These files draw the line this way: Braden decides anything needing a legal person or touching the company; the authoring sessions decide what the library says.
- *Forcing event:* the first library document. No date.
- *Options:* confirm that split. Have Braden approve every document (costs his time; changes the deed). Have Braden approve nothing outside legal acts (the deed's plain reading). *Reversible.*
- *Sidestep:* authoring sessions publish freely, and Braden reviews only on request or after the fact.

**7. Whether and how to switch on GitHub Pages.**
The website. The repository has a `docs/` folder for house paperwork, so publishing from `docs/` would publish this file and not the library.
- *Forcing event:* the first shelf of documents. No date.
- *Options:* publish from the repository root (publishes everything, including the agent rules). Publish from a dedicated folder for the library, decided by the authoring session (cleaner; needs one layout decision). No website: the repository is canonical. All *reversible*.
- *Sidestep:* no site until a domain exists; readers use the repository on GitHub.

**8. Whether the project needs a stall condition.**
Nothing was written into the library between 2026-08-23 and 2026-10-02. The kill criterion covers only a deliberate ending or a lapsed domain.
- *Forcing event:* admission. No date.
- *Options:* none (the deed tolerates a year's absence; costs nothing). A checkable condition, such as no first shelf by a date Braden picks (clear; reversible). Leave it out of the registry until the first shelf exists (cleanest record; reversible).
- *Sidestep:* admit it only once the first shelf is public, so the question never arises.

**9. Whether Incipit gets a Linear project.**
No Linear issue or project mentions Incipit, checked on 2026-10-02. Work status has nowhere to live until one exists. No issue was filed by the session that wrote these files.
- *Forcing event:* the first piece of tracked work. No date.
- *Options:* a Linear project, under whichever team Braden chooses (status in the right place; small setup cost). No Linear tracking; the letters carry continuity (contradicts D-11 for status). *Reversible.*
- *Sidestep:* track only Braden's own acts (domain, licence, Pages) in Linear and leave authoring untracked.
