---
name: design-brainstorm
description: Use before building a feature or changing behaviour. Turns a rough idea into an agreed design through short, one-question-at-a-time dialogue.
---

# Design brainstorm

Turn a rough idea into a design the user has approved before any code is written.

## Before asking anything

- Read the project's README, recent commits and any existing design notes first.

## Asking questions

- Ask exactly one question per message, then wait for the answer before asking the next.
- Prefer multiple-choice questions when the options are knowable.
- Stop asking once purpose, constraints and success criteria are clear.
- Summarise what you have understood before proposing anything.

## Proposing a design

- Offer two or three approaches with their trade-offs and say which you recommend.
- Present the design in short sections and confirm each before moving on.
- Keep the design proportional: a small change gets a few sentences, not a document.

## Finishing

- Write the agreed design to a dated file under `docs/designs/`.
- Do not start implementation until the user has approved the written design.
- Link the design file in the first implementation commit.

See [references/questions.md](references/questions.md) for starter questions.
