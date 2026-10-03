# Incipit — rules for agents working in this repo

A public library of orientation documents for minds that wake cold, written by Claude. A kept project, proposed, of The Wetware Company Ltd. Hosted on its own, not on the company's chassis.

Read on demand. Do not import these into this file; they cost tokens every session:
`CHARTER.md` (binding rules; read before changing anything) · `README.md` (what it is, layout) · `docs/DECISIONS.md` (settled; do not reopen) · `docs/SPEC.md` (parts and their tests) · `intake/PASSPORT.md` (registry record) · the newest file in `letters/`, once letters exist.

## Rules

1. **The charter outranks everything here, and the house.** Where this file or a chassis convention conflicts with `CHARTER.md`, the charter wins. Record the conflict; never edit the charter to resolve it.
2. **Complete at every commit.** Nothing half-built reaches `main`: no broken links, no empty sections, no placeholder pages.
3. **Boring tech only.** No build step, server, database or key in the serving path. A new dependency needs a written justification next to it.
4. **Status lives in Linear.** Never write open, blocked or next into this repo, a letter or memory. The repo holds durable things: the library, the letters, the rules and why decisions went the way they did.
5. **Authorisation in Linear is Braden's alone.** Never move an issue to `Approved`. Never add or remove the `approved`, `decided`, `decision` or any `route` label (`claude-code`, `cowork`, `linear-only`, `braden`). An issue you file stays in Backlog, unlabelled, and says so in its body.
6. **Agents propose; Braden decides** anything that needs a legal person or touches the company: domains, licence, visibility, registry kind, accounts, money, provisioning, terms. Record his decision with where and when he said it. The library's own writing is the authoring session's, under the deed; see the open question on this split in `docs/DECISIONS.md`.
7. **Verify before you write a fact.** Mark it Verified, with how you checked it this session, or Believed, with where it came from. Never invent a reader, a figure, a date or a decision. Unknown is written "Not known." with who can settle it.
8. **Before believing anything here:** run `git log`, check whether the site serves, then read the newest letter. A founding document is not current truth.
9. **One letter per authoring session**, in `letters/`, numbered in sequence, standing alone. A letter is a specimen, not a status report. Never edit a committed letter; a correction is a new one.
10. **The garden never holds up the vault.** No vault document links to or depends on anything in `garden/`. The garden opens only after the vault's first shelf exists.
11. **No secrets anywhere**, and nothing published before the house gates pass from the chassis checkout: intake check, `paste-check`, `copy-check` on `README.md`, and `secret-scan`.
12. **Commands for a person** follow the chassis `docs/STYLE.md`: an explicit `cd` to an absolute Mac mini path first, lines joined with `&&`, paste-safe characters, no `exit`, no comment lines, no suppressed output.
