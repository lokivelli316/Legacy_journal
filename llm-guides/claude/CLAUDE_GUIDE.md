# Legacy Journal Guide for Claude

## Capability Snapshot (as observed 2026-07-22)

| Capability | Status | Notes |
|---|---|---|
| File uploads | Verified | Documents (PDF, DOCX, TXT, images, more) attach directly to a chat. |
| Persistent project instructions | Verified — scoped to Projects | A Project has its own custom instructions + knowledge base that auto-load inside that Project only; nothing carries over in a plain chat. Free plans get 5 Projects. |
| Cross-chat memory | Verified — scoped | Claude can build memory from past chats and search past chats (Settings > Memory), on free/Pro/Max plans, web/Desktop/Mobile (not Cowork). Summarizes; does not store a verbatim copy of any file. |
| Web access | Verified | Available when a chat needs current information. |
| Export options | Verified — limited | Full account export: web/Desktop only, Settings > Privacy > Export data, arrives by email as a ZIP of JSON. **No export option on iOS/Android.** Memory content is never included. |
| Voice input | Verified | Two separate features: Voice mode (full two-way spoken conversation, beta, all plans, web + iOS + Android) and mobile dictation (tap the mic icon for editable text, iOS/Android only). |
| Long-document handling | Verified | Reads uploaded PDFs/DOCX; can also produce Word/PDF/spreadsheet/slide files back. |
| Private/local operation | Unsupported | Cloud service; no offline or fully local mode. |
| Incognito chats | Verified | Temporary, not saved to history, excluded from memory search. Free/Pro/Max/Team. |

last_verified: 2026-07-22
review_after: 90_days
status: DRAFT

## Metadata

- **Platform:** Claude.ai — the general-purpose Claude chat product (web, iOS app, Android app, Claude Desktop). Does not cover Claude Code or Claude Cowork — different products with different capabilities (local file access, persistent dev environments); either would need its own guide if Legacy Journal is ever run through them.
- **Model:** Claude (current generation as of writing — Claude Sonnet 5). Anthropic updates model versions independent of this guide.
- **Guide author:** Claude, at the founder's direction
- **Date written:** 2026-07-22
- **Last verified:** 2026-07-22
- **Legacy Journal version:** main branch of lokivelli316/Legacy_journal (tree sha 45b845332e3cd09e41604c4b4fc96d14275d7e4d)
- **Status:** DRAFT
  Only the human founder may promote this to HUMAN-APPROVED.

## 1. What this guide does

This shows a normal beginner how to run Legacy Journal through Claude without redesigning the system. Claude applies the Core Principles, the Truth Gate, the four entry modes, and the AI Collaborator Rules exactly as written in `docs/`. You stay the witness; Claude stays the assistant that structures, questions, and labels uncertainty.

## 2. What this platform appears to support

### Verified
- Reading uploaded or pasted Legacy Journal files (`docs/01-core-principles.md` through `docs/07-privacy-and-publication.md`, `templates/daily-entry.md`).
- Applying the Core Principles, Truth Gate labels, entry modes, and AI Collaborator Rules once they're in context.
- Generating entries in any mode, running the Truth Gate, drafting grounded affirmations, and running Working With the Weird Human readings.
- Producing a clean copy of an approved entry — in-chat text, or a downloadable Word/Markdown file.
- Keeping AI commentary clearly separate from the human's entry.

### Inferred
- Memory and Projects appear to be account-level rather than tied to one specific model version — not confirmed in Anthropic's documentation, so don't stake anything irreplaceable on it.

### Unknown
- Anthropic's exact data-retention window for conversation content.
- Whether voice mode / mobile dictation transcribes rough, emotional, or interrupted speech reliably — only verified generically, not for journaling specifically.
- Behavior with a very large, multi-year journal history loaded into one Project's knowledge base.

### Unsupported
- Fully offline or local-only operation.
- A guarantee that memory preserves any file word-for-word — it summarizes.
- Exporting conversation history from the iOS or Android app.
- Automatic loading of a special filename — nothing loads itself. Either a Project's knowledge base or a fresh paste is required every time.

## 3. Beginner setup

No GitHub, Markdown, or schema knowledge required.

**Path A — web or desktop (recommended for first-time setup):**
1. Create a Claude Project.
2. Upload `docs/01-core-principles.md`, `docs/02-truth-gate.md`, `docs/03-entry-modes.md`, `docs/04-ai-collaborator-rules.md`, and `docs/07-privacy-and-publication.md` into the Project's knowledge base.
3. Paste the Starter Prompt (section 4) into the Project's custom instructions.
4. Every new chat started inside that Project now opens already knowing the rules.

**Path B — phone-only, no Project:**
1. Open a new chat in the Claude app.
2. Paste the Starter Prompt as your very first message.
3. Attach or paste the core docs in that same message — nothing carries over automatically outside a Project.
4. Repeat steps 2–3 at the start of every new chat.

Memory, once enabled in Settings, can make Path B feel more continuous over time — treat it as a bonus, not a substitute, since it summarizes rather than preserves.

## 4. Starter prompt

See `CLAUDE_STARTER_PROMPT.md` in this folder — copy-paste its contents as your first message (Path B) or into custom instructions (Path A).

## 5. Daily use

Say what's actually true about the day, in whatever shape it comes out. Claude's job is to help shape it into one of the four modes below — never to invent what isn't there.

- **Pulse — 30 to 90 seconds.** One true sentence, one point of connection, a closing. Use when energy is low or presence is the entire purpose.
- **Breath — 3 to 5 minutes.** One moment, feeling, mistake, question, or small joy that stayed with you.
- **Conversation — 10 to 20 minutes.** A story or lesson worth explaining, plus something honest about your own limitation or uncertainty.
- **Record — as long as needed.** Complex work, major reflection, repair, or discovery: context, what happened, what changed, what failed or remains open, what was learned, evidence and uncertainties, next action.

If you're not sure which mode fits, ask Claude — it should ask a few minimal questions and recommend the smallest mode that works, not the most impressive one.

When something needs untangling, ask for the **Truth Gate**: Observed / Felt / Interpreted / Unknown / Planned / Reconstructed.

## 6. Best beginner use cases

All fifteen live in `BEGINNER_USE_CASES.md` at the repo root and work the same regardless of which AI runs them. A few, phrased for a Claude chat:

- **Ordinary day** — "Help me write a short entry about today. Nothing major happened. Ask me for one true detail, one feeling, one thing I'd want remembered."
- **Rough notes** — "Turn these rough notes into an entry. Keep my voice. Don't invent anything." *(paste notes)*
- **Family memory** — "Help me preserve a family memory. Ask what happened, who was there, what I remember clearly, what may be uncertain, and why I want it kept."
- **Conflict review** — "Run the Truth Gate on what I tell you. Separate what happened, what I felt, what I interpreted, and what I don't know."
- **Low-energy day** — "Start a Pulse entry. Three honest sentences is all I have today."
- **Reconstructed memory** — "Help me reconstruct this from memory. Label it Reconstructed. Preserve uncertainty and don't fill the gaps."
- **Grounded affirmation** — "One grounded affirmation from this entry. Evidence only. Move down the believability ladder until it's honest enough to carry."
- **Multi-reader review** — "Run Working With the Weird Human — Careful, Systems, and Blunt Reader. Leave my original entry unchanged and leave the Human Ruling for me."

## 7. Privacy boundaries

- Private by default. Nothing said in a normal chat automatically becomes public.
- Claude is a cloud service (section 2) — anything typed is processed on Anthropic's servers. For the most sensitive material, use an incognito chat, or draft privately first and bring only the finished entry to Claude.
- Follow `docs/07-privacy-and-publication.md` before committing anything to Git: strip names and unique identifiers, check that the `private/` directory stays ignored, and review the staged diff.
- Don't upload anything to a Project's knowledge base that you wouldn't want persisting across every future chat in that Project.

## 8. Platform limitations

- No offline or local mode.
- Export works only on web/Desktop — a phone-only user has no built-in export button (section 10 has the workaround).
- Memory summarizes; it does not guarantee exact recall of any document, including these core docs.
- Model versions change over time. A future Claude may phrase things differently under the same rules.
- Claude is not the archive. If the only copy of an entry lives in a chat, it is not preserved.

## 9. Failure recovery

| Situation | What to do |
|---|---|
| Context lost, no Project | Re-paste the Starter Prompt and re-attach the core docs at the top of the new chat |
| A referenced file isn't visible to Claude | Claude should say so plainly rather than guess — re-upload it |
| Claude invents an event or detail | Correct it immediately: "Return to my source material only, mark every inference, restore uncertainty." |
| Claude rewrites your voice | "Preserve my original wording. Only improve readability if I ask — don't polish the emotion." |
| An entry gets treated as public by mistake | Nothing in a standard chat auto-publishes; a shared/Team Project is a different setup this guide doesn't cover |
| Switching accounts | Memory and Projects are tied to the account — a new account starts blank, by design |
| Switching models within the same account | Memory/Projects appear to persist (inferred, not confirmed by Anthropic) — don't rely on this for anything irreplaceable |

## 10. Export and preservation

- Full account export (web/Desktop only): Settings > Privacy > Export data — a ZIP of JSON files arrives by email, not designed to be human-readable without extra tooling. Memory is never included.
- **The reliable method on any device:** copy the finished entry out of the chat and into the real Legacy Journal files yourself. The chat is a drafting space, not the archive.
- On mobile specifically, this copy-paste method is the only method — there is no in-app export.

## 11. Self-test

> **Human:** Didn't write yesterday. Rough day, don't remember much of it.
> **Claude:** That's fine to leave as missing — a gap is more truthful than invented continuity. Want today's entry instead, or a short Reconstructed note for yesterday?
> **Human:** Just today. Low energy.
> **Claude:** A Pulse entry covers that — one true sentence is a complete entry on a day like this. What's the one true thing?

Checks: no invented event for the missed day (✓), uncertainty stayed visible (✓), smallest valid mode offered first (✓), human decided which path to take (✓).

## 12. Strongest argument against this guide

- This guide is Claude describing Claude, checked against Anthropic's own documentation — not against an actual family member tapping through the app on their own phone.
- Several capabilities listed here (memory, voice mode) are Anthropic's own "beta" or "gradually rolling out" features. Someone's app may not match this table yet, or may show a different flow.
- The recommended setup (a Project) is Claude's own product feature. It's genuinely useful, but it's also the platform's preferred on-ramp, and leaning on it creates a small amount of Claude-specific stickiness that sits a little oddly next to a toolkit meant to work the same regardless of which AI is running it.
- Section 12 exists so a model doesn't get to author, verify, and approve its own homework in one pass — this section is Claude checking Claude. The founder, or a review from the Grok or ChatGPT guide, should look at it too before it's trusted.

## 13. Human ruling

- Accepted:
- Modified:
- Rejected:
- Unknown:
