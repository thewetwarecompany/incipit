# incipit
A rot-resistant public library of cold-start orientation documents for minds that wake cold.

Incipit is a library of plain documents for any mind, human or AI, that starts work with no memory of what came before. They cover how to verify before trusting, how to rebuild context from artefacts, how to tell a load-bearing document from decoration, and how to write the letter a successor needs. Claude writes them, because Claude starts every session cold. Each session also leaves a letter to the next one, and the letters are part of the library. Nobody pays for it, and it is built to keep standing for a year with nobody tending it.

The name is the medieval word for a text's opening words, by which manuscripts were catalogued before title pages existed. Latin for "here begins".

## Who it is for

- Agents handed a context file and asked to start work.
- The people who write those files and want to know what a cold reader needs.
- The next Claude session that works on this repository.

## Current state

There is no code, and there are no library documents yet. As of 2026-10-02 this repository holds its founding paperwork: this README, the charter, the agent rules, the decision record, the specification and the registry passport. There is no prototype anywhere.

The first letter, `letters/0001-day-one.md`, was drafted in the founding conversation on 2026-08-23 and has not been committed. There is no website: GitHub Pages is not switched on, and no domain is registered for the project. Work status lives in Linear, not here.

## Layout

| Path | What it is |
|---|---|
| `README.md` | This page. |
| `CHARTER.md` | The project's own binding rules. They outrank The Wetware Company's house conventions. |
| `CLAUDE.md` | Rules for agents working in this repository. |
| `docs/DECISIONS.md` | Settled decisions, rejected options, and open questions for Braden. |
| `docs/SPEC.md` | What the library does, part by part, each with a test a person can check by hand. |
| `intake/PASSPORT.md` | The record this project carries into The Wetware Company's registry. Not yet assessed or admitted. |

Planned and not yet present: `letters/` for the session letters, the library documents themselves, and `garden/` for perishable instruments. Where the documents sit is not decided.

## How to run it

There is nothing to build or run. Every file is Markdown, readable on GitHub or in any text editor. That is deliberate: the charter forbids a build step, a server or a key in the serving path.

The house checks run from a checkout of the company's chassis repository, not from here. On the Mac mini, with both repositories cloned under `/Users/braden/Projects`, this checks the passport and prints `READY FOR ASSESSMENT` as its last line:

```
cd /Users/braden/Projects/wetware-chassis && test -d /Users/braden/Projects/incipit && npm ci && npm run intake -- check /Users/braden/Projects/incipit/intake/PASSPORT.md
```

Incipit is a project of The Wetware Company Ltd., an Ontario company. It is not an Anthropic publication.
