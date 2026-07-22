# Legacy Journal

**A privacy-first, AI-assisted journaling toolkit for preserving an honest human record.**

Legacy Journal is designed for people who want to leave behind more than polished highlights. It supports short entries, long-form reflection, mistakes, uncertainty, ordinary days, recovery, lessons, humor, and optional AI commentary—without allowing AI to replace the human witness.

## Core promise

- Long entries can carry complexity.
- Short entries can carry presence.
- Missing days do not need to be fabricated.
- Planned drafts do not become history until reality confirms them.
- AI may organize, question, summarize, or challenge.
- The human author retains final authority over meaning and publication.

## What is included

- Four entry modes: **Pulse, Breath, Conversation, and Record**
- Fifteen reusable daily-entry skeletons
- A **Truth Gate** for separating observation, emotion, interpretation, uncertainty, plans, and reconstruction
- Grounded affirmations that avoid motivational-poster language
- An optional multi-AI commentary layer called **Working With the Weird Human**
- Privacy and publication checklists
- Reusable prompts
- A machine-readable JSON schema
- Neutral example entries containing no real personal history

## Quick start

1. Copy `templates/daily-entry.md`.
2. Choose the smallest entry mode that can preserve what matters.
3. Write one true thing.
4. Add one point of connection to the intended reader.
5. Label uncertainty rather than inventing certainty.
6. Keep private entries outside the public repository.
7. Add AI commentary only when it helps rather than crowds the human voice.

## Suggested private layout

```text
my-legacy-journal/
├── private/                 # Never commit; ignored by .gitignore
│   ├── entries/
│   ├── attachments/
│   └── source-notes/
├── public/                  # Deliberately reviewed material
├── templates/
└── exports/
```

## Start here

- [Core principles](docs/01-core-principles.md)
- [Truth Gate](docs/02-truth-gate.md)
- [Entry modes](docs/03-entry-modes.md)
- [AI collaborator rules](docs/04-ai-collaborator-rules.md)
- [Grounded affirmations](docs/05-grounded-affirmations.md)
- [Working With the Weird Human](docs/06-working-with-the-weird-human.md)
- [Privacy and publication checklist](docs/07-privacy-and-publication.md)

## Privacy warning

This repository is a toolkit, **not a recommended place for raw private journal entries**. Git history is durable. Removing a file later does not guarantee that its earlier contents disappear from clones, forks, caches, or commit history.

## License

MIT. Use it, adapt it, translate it, and build something humane with it.
