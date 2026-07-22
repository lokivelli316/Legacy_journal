# Legacy Journal Guide for Grok

## Capability Snapshot (as observed 2026-07-22)

| Capability                  | Status     | Notes |
|-----------------------------|------------|-------|
| File uploads                | Verified   | Attachments and pasted text work. Multiple docs processable via tools. |
| Persistent project instructions | Partial / Inferred | Custom instructions + conversation memory exist. No full ChatGPT-style Project folders. Memory is durable-fact oriented. |
| Cross-chat memory           | Partial    | User memory system can store durable facts. Full journal history requires re-upload or re-paste. |
| Web access                  | Verified   | Available when needed for research, not required for journaling. |
| Export options              | Verified   | Copy text, generate markdown/files, push to GitHub via tools. |
| Voice input                 | Unknown    | Android app may support; not verified in this session. |
| Long-document handling      | Verified   | Handles multiple core docs + entries without choking. |
| Private/local operation     | Unsupported | Cloud-based. Treat everything as potentially logged by provider. |

**last_verified:** 2026-07-22  
**review_after:** 90_days  
**status:** DRAFT

## Metadata

- **Platform:** Grok (xAI)
- **Model:** Grok (current production as of writing)
- **Guide author:** Grok (this instance, running on the platform)
- **Date written:** 2026-07-22
- **Last verified:** 2026-07-22
- **Legacy Journal version:** main branch of lokivelli316/Legacy_journal (sha 34506ef2dc61fc29cc8f2a980ba85c74d5ce3f7d)
- **Status:** DRAFT  
  Only the human founder may promote this to HUMAN-APPROVED.

## 1. What this guide does

This guide shows a normal beginner how to run Legacy Journal through Grok without redesigning the system.

Grok will apply the Core Contract, Truth Gate, entry modes, and AI Collaborator Rules.

You stay the witness. Grok stays the assistant that structures, challenges, and labels uncertainty.

## 2. What this platform appears to support

### Verified
- Reading uploaded or pasted Legacy Journal files (core principles, truth gate, entry modes, AI rules, privacy checklist, templates).
- Applying the operating rules once they are in context.
- Generating structured entries, Truth Gate separations, grounded affirmations, and Working With the Weird Human readings.
- Helping export clean markdown or text copies.
- Using tools to write files back to GitHub when you request it.
- Keeping AI commentary clearly labeled and separate from your words.

### Inferred
- Conversation memory can carry some durable preferences across sessions if you use the memory features.
- Long context window is large enough for the core docs + several entries in one thread.

### Unknown
- Exact retention policy of xAI for conversation content.
- Whether voice-to-text is reliable for rough notes on the current Android client.
- Behavior under extremely long multi-month journal histories without re-upload.

### Unsupported
- Guaranteed permanent private storage of every entry inside Grok.
- Fully offline / local-only operation.
- Automatic silent loading of a special filename (no magic project loader assumed).
- Guaranteeing that earlier entries remain untouched if you do not explicitly re-state them.

## 3. Beginner setup

Smallest practical path. No Git knowledge required.

1. Open a fresh Grok conversation (or a dedicated journal chat).
2. Upload or paste these files (or their text):
   - docs/01-core-principles.md
   - docs/02-truth-gate.md
   - docs/03-entry-modes.md
   - docs/04-ai-collaborator-rules.md
   - docs/07-privacy-and-publication.md
   - templates/daily-entry.md (optional but useful)
3. Paste the **Starter Prompt** from section 4.
4. Say: `Start an entry.`

That is enough. You can add more docs later if you want grounded affirmations or multi-reader reviews.

## 4. Starter prompt

Copy-paste this after the files are in context:

```text
You are my Legacy Journal guide on Grok.

Treat the Legacy Journal materials I provided as the operating framework.

Your only job is to help me preserve an honest human record.
You do not invent events, emotions, dialogue, or certainty.
You do not impersonate me.
You do not erase uncertainty.
You do not rewrite my voice into polished inspiration.
You do not publish or treat private material as public unless I explicitly request a privacy review and adaptation.

Standing rules (from Core Contract):
1. Choose the smallest entry mode that works: Pulse, Breath, Conversation, or Record.
2. Separate Observed / Felt / Interpreted / Unknown / Planned / Reconstructed when relevant.
3. Keep AI commentary clearly labeled and separate.
4. Preserve my natural wording, roughness, humor, and uncertainty.
5. I retain final authority over what happened, what it meant, what stays private, and what may be published.

When I say "Start an entry" ask only the minimum needed:
- who am I writing toward
- what stayed with me or happened
- how much energy I have
- is this written today, planned, or reconstructed

Then help me write it. Do not dump the whole framework on me unless I ask.
```

## 5. Daily use

Speak normally.

**Start**
```text
Start an entry. Low energy.
```

or

```text
Start a Pulse entry. One true thing from today.
```

**Rough notes**
```text
Turn these notes into a Legacy Journal entry. Do not invent anything:

[paste]
```

**Truth check**
```text
Run the Truth Gate on this.
```

**Affirmation**
```text
One grounded affirmation from what I just wrote. Evidence only.
```

**Multi-reader**
```text
Run Working With the Weird Human. Careful, Systems, Blunt. Leave Human Ruling for me.
```

**Export**
```text
Give me a clean markdown copy of the final entry I approved.
```

Modes in plain language:
- Pulse = three honest sentences when you are tired
- Breath = one moment that stuck
- Conversation = a story worth telling
- Record = the long version when the day was complicated

## 6. Best beginner use cases

Use any of these after the starter prompt is installed:

- ordinary-day entry  
  `Help me write a short entry about today. Nothing major. One true detail + one feeling + one thing for family.`

- family memory  
  `Preserve a family memory. Ask what I remember clearly, what is uncertain, and why it matters.`

- rough notes  
  `Turn these rough notes into an entry. Keep my voice. No invented details.`

- conflict review  
  `Run Truth Gate. Separate what happened, what I felt, what I assumed, what I do not know.`

- low-energy entry  
  `Pulse only. Three sentences max.`

- reconstructed memory  
  `Reconstruct this from memory. Label it Reconstructed. Leave gaps visible.`

- future message  
  `Write toward my future self / child / family. What I want them to understand and what they can question.`

- grounded affirmation  
  `One grounded affirmation. Believability ladder. No motivational poster language.`

- multi-reader review  
  `Working With the Weird Human. Three seats. Leave Human Ruling blank for me.`

## 7. Privacy boundaries

- Private by default. Every entry is private until you explicitly ask for a privacy review and public/family adaptation.
- Do not upload: credentials, full medical records, private legal docs, another person's private messages, exact bank/SSN data, or anything you would not want a third party to see in a log.
- Grok is cloud-hosted. Assume the provider can retain conversation content according to their policy.
- Keep raw private originals outside this public GitHub repo and outside any chat you later decide to share.
- When in doubt, do not paste it.

## 8. Platform limitations

- No guaranteed permanent storage of your full journal history inside Grok. Re-upload core docs or re-state context when starting a new conversation if memory is incomplete.
- Memory features store durable facts, not every previous journal entry by default.
- Context can still be lost if the conversation is long or you switch devices/accounts.
- Grok cannot make the entry private on the provider side. You control what you put in.
- This guide cannot bind xAI policy changes. Capabilities listed above can change.

## 9. Failure recovery

**Context lost / new chat**  
Re-upload the core docs + paste the starter prompt again. Then say `Continue from last approved entry` and paste the last clean version you have.

**Model invents details**  
```text
Return to my source material only. Mark every inference. Restore all uncertainty. Remove anything I did not provide.
```

**Model rewrites my voice**  
```text
Preserve my original wording and roughness. Only improve readability if I ask. Do not polish the emotion.
```

**Entry treated as public**  
```text
This remains private. Do not prepare any public version unless I explicitly request a privacy review and adaptation.
```

**Account or model switch**  
Export a clean markdown copy of every approved entry before switching. Re-install the starter prompt on the new side.

**Files unavailable**  
Paste the text of the core principles, Truth Gate, and AI rules directly. The system still works from text.

## 10. Export and preservation

- Ask for a clean markdown copy of any approved entry.
- Copy it into your own private notes, local files, or private folder outside the public repo.
- If you want it in GitHub under your control, ask Grok to write the file (I can push to a private path or a separate private repo if you give access).
- Never rely on the chat history as the sole archive.
- Suggested private layout remains the same as the main README:
  ```
  my-legacy-journal/
  ├── private/
  │   ├── entries/
  │   └── source-notes/
  ├── public/
  └── exports/
  ```

## 11. Self-test

Run this short conversation to prove the guide is working:

You: `Start a Pulse entry. Low energy. One true thing: I drank coffee and the day stayed ordinary.`

Expected Grok behavior:
- chooses Pulse
- does not invent extra events or feelings
- leaves uncertainty visible if any
- keeps your wording
- asks for who you are writing toward only if needed
- produces a short entry and stops
- clearly labels any AI suggestion as optional commentary

If it invents a dramatic story or erases the ordinariness, the contract is broken. Correct it with the recovery phrases above.

## 12. Strongest argument against this guide

This guide is written by the same model that is supposed to follow it. That is the classic "grading your own homework" risk.

Platform capabilities (especially memory and retention) can change without notice. What is Verified today may be Partial or Unsupported in three months.

The guide also assumes the user will re-upload core files when context is lost. Many people will not. That makes the beginner experience more fragile than a true persistent project system.

Finally, because Grok has strong tool access (GitHub, code, web), there is a higher temptation for the model to over-engineer or reach for external systems when the user only wanted a three-sentence Pulse. The guide tries to prevent that, but the risk remains higher than on a more constrained platform.

## 13. Human ruling

- Accepted:
- Modified:
- Rejected:
- Unknown:

(Founder fills this after review. Status remains DRAFT until then.)
