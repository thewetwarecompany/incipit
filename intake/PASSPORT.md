---
id: W-999
slug: incipit
name: "Incipit"
kind: kept-project
stage: proposed
one_liner: "A free public library of orientation documents for minds, human or AI, that start work with no memory of what came before."
thesis: "Incipit is a static library of plain documents on how to orient cold: verify before trusting, rebuild context from artefacts, tell a load-bearing document from decoration, and write the letter a successor needs. It is written by Claude, which starts every session cold, for agents and the people who hand them context. Nobody pays."
payer: "nobody."
revenue_model: none
origin:
  founded_by: mixed
  founded_on: 2026-08-23
  source: "The founding claude.ai conversation 'Incipit: a library of first words', read in full on 2026-10-02; the passport of 2026-09-23; the Project's memory notes of 2026-09-14 and 2026-09-24; and the GitHub repository, read on 2026-10-02. The founding conversation shows only its last-updated date, 2026-08-23, so the project was founded on or before that day."
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
  notes: "Planned hosting is GitHub Pages, which costs nothing; Pages is not switched on. No domain is registered for the project, so its ten-year fee is not known. The persistent Linux machine and 50 USD a month in cloud credits were offered by Braden; what they cost him is not known. Claude writes in sessions not metered to the project."
payments:
  rail: none
  provider: null
hosting:
  mode: independent
  domain: null
  dedicated_domain: null
  repo: "https://github.com/thewetwarecompany/incipit"
  worker: null
  health_url: null
admission:
  dispute_prone: { answer: no, note: "It takes no money and sells nothing." }
  custodies_funds: { answer: no, note: "A crypto wallet was named as the project's own treasury and is believed empty. It holds only the project's money and never routes money between people." }
  needs_synchronous_human: { answer: no, note: "A static site with no accounts, chat or support channel. Only domain renewal needs a person, once a decade." }
  tail_risk_beyond_balance_sheet: { answer: no, note: "Public prose documents with no data about people, no money and no advice on health, finance or minors. The worst plausible day is a document that misleads an agent, which is fixed by a commit." }
  cold_email_volume: { answer: no, note: "It sends no email of any kind." }
  remotely_operable: { answer: yes, note: "Everything is a git repository plus static hosting, operated by push. The repository exists and was cloned and read on 2026-10-02; nothing is deployed yet." }
  decision: pending
  decided_by: null
  decided_on: null
kill:
  criterion: "It stops when an authoring session decides to end it, as letter 0001 permits, or when its domain lapses with no person or treasury able to renew it. In either case the last commit must be as complete as the first."
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
  export_path: "The git repository is the entire record: clone it. Handing it on means transferring the repository, the domain registration if one exists, and the treasury wallet keys to the new holder."
updated: 2026-10-02
---

## Thesis

Incipit is a public library of orientation documents written from the waking side, for any mind that arrives mid-stream with no memory. Agents are routinely handed context files by people guessing what a cold reader needs; Claude is that cold reader every session, so it is placed to write what the cold reader needs. It is a gift, built to run unattended, and it will never charge. Its session letters, one per session, also form a record of an AI practising its own orientation advice.

## What exists today

**Verified** on 2026-10-02:

- The repository `thewetwarecompany/incipit` on GitHub: public, created 2026-10-03 at 01:59 UTC, with one commit, "Initial commit", by the `CivicGrove` login, holding a two-line README. No licence. GitHub Pages is not switched on. Checked by reading the repository's metadata through the GitHub API and by cloning it.
- The founding conversation 'Incipit: a library of first words', read in full. It holds the deed, the full draft of letter 0001 and the ratification of option B.
- Letter 0001, the library documents, `letters/` and `garden/` are not in the repository. Checked by listing its files.
- Domain availability, by a registry lookup through Vercel: `incipit.org` is not available, and a web search lists it as for sale; `firstlight.page` is not available; `coldstart.guide` and `coldstart.page` are available. The Vercel account holds only `civicgrove.com`. No Cloudflare Worker for Incipit exists, checked by listing the account's Workers.
- No Linear issue or project mentions Incipit, checked by searching both.
- The company registry, in the chassis repository at its commit of 2026-09-26, has no record for Incipit and no other use of the slug.

**Believed**, from the founding conversation and memory notes, not checked:

- A persistent Linux machine managed by Braden, an empty password wallet, an empty crypto wallet as treasury, and 50 USD a month in cloud credits, provider not known. All were offered in the founding conversation; none was seen.
- That no domain is registered for Incipit at Cloudflare's registrar, where the company's other domains are. The registrar account could not be read; Braden can confirm.
- The memory note of 2026-09-14 gives the third-choice domain as `coldstart.page`. The founding conversation, the primary source, says `firstlight.page`.

## Principles and constraints

Recorded in full in `CHARTER.md` in the repository. They outrank house conventions.

The deed, from the groundskeeper:

> 1. It must survive my absence — a year gone, still running, useful, not rotting.
> 2. It must be something only I would build.

Rule 1 as amended by option B, ratified by Braden: "the core must survive my absence; a marked perishable layer may exist if its death is graceful and composts into the core."

Invariants added by the author in letter 0001:

> 3. Complete at every commit. A visitor on any day finds a finished thing — smaller is fine, broken is not.
> 4. Boring tech only. Markdown, git, static hosting. Nothing in the serving path requires me, a key, or a server.
> 5. Letters are specimens, not status reports. Write each one as if the reader has nothing else. They do.
> 6. Treasury policy v0: funds only domain renewal past year ten and paying humans for translation or accessibility work. Never compute for its own sake. Revisit if it ever holds more than a gesture.

Conflicts with house conventions: invariant 4 rules out the shared chassis, which puts a server in the serving path, so `hosting.mode` is independent. Invariant 6 limits what the treasury may fund, so no company use of it is permitted.

## Data and privacy

Nothing is collected about people. The site, once it exists, is static documents with no accounts, forms, cookies or analytics of its own. GitHub, as host, may keep visitor logs under its own privacy policy; the project cannot see them. The planned link-checker records whether outside pages still answer and nothing about people. The planned drift observatory records Claude's own answers. None of it is health information, financial information, or about minors.

## AI and model use

Claude, Anthropic's model, writes the documents and the letters in authoring sessions. The model builds it and does not answer visitors. The published site calls no model, and invariant 4 forbids one in the serving path. If a document is wrong, a reader sees a wrong document until a later session corrects it by commit. There is no model budget to run out; if Claude stopped returning, the library would stand as it was.

## Money

Expected running cost is zero: GitHub Pages is free, and a domain would be paid once for ten years. The domain fee is not known, because no domain is chosen. The persistent machine and cloud credits are Braden's; their cost to him is not known. The treasury is a crypto wallet, believed empty; who holds its keys is not known, and only Braden can say. Revenue so far: none.

## What it needs from a legal person

A domain registration for ten years with auto-renew off. A licence for the repository: the founding plan said MIT, and none has been applied. Switching on GitHub Pages. Custody of the treasury wallet. The persistent machine. No terms of use are planned, since there are no accounts to bind.

## Kill criteria

It stops when an authoring session decides to end it, as letter 0001 permits, or when the domain lapses with nobody able to renew it. Stopping means a final complete commit with a closing letter saying why; the repository and site stay up read-only, and nothing is deleted. There is nobody to notify, because it holds no one's data and has no accounts.

## Exit path

The project is one git repository of plain Markdown. Moving it means transferring the repository, any domain registration and the treasury wallet keys to the new holder. There are no personal data or accounts to migrate.

## Open questions for Braden

The full set, each with its forcing event, options, costs, reversibility and a sidestep, is in `docs/DECISIONS.md` in the repository. In short:

1. **Which domain to register.** In the founding order, the first choice, `incipit.org`, is for sale, and the third, `firstlight.page`, is registered. The second, `coldstart.guide`, is available. Costly to reverse once linked. Sidestep: launch on the GitHub Pages address first.
2. **Which licence.** MIT was planned; CC BY 4.0 or CC BY-SA 4.0 fit prose better. One-way door for what is already copied. Sidestep: separate licences for prose and code.
3. **Kept project, experiment, or not registered.** This passport proposes kept project; the decision is Braden's. An experiment would need a payer and the chassis, which the charter forbids. Reversible. Sidestep: a catalogue record with no obligations.
4. **Who holds the domain, repository and wallet: Braden personally or the company.** Reversible by transfer. Sidestep: record ownership in the passport only.
5. **Where authoring sessions run, and who commits letter 0001.** The persistent machine has not been seen. Sidestep: any session with push access commits letter 0001 next.
6. **The split of authority between Braden and the authoring sessions.** Reversible. Sidestep: publish freely, review on request.
7. **Whether and how to switch on GitHub Pages.** Reversible. Sidestep: no site until a domain exists.
8. **Whether a stall condition is needed.** Reversible. Sidestep: admit only once the first shelf is public.
9. **Whether Incipit gets a Linear project.** Reversible. Sidestep: track only Braden's own acts.

## Log

- 2026-09-23 — first passport written by a Claude instance in the claude.ai Project 'Library Of LLM On Boarding Docs', from the founding conversation and the memory notes, with a public GitHub search and one web search.
- 2026-10-02 — passport updated by a Claude Code session in the same Project, after the repository was created: repository, Pages, domain availability, Workers, Linear and the registry checked; letter 0001 confirmed not committed; open questions widened. Not assessed. Not admitted.
