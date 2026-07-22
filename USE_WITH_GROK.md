# Use Legacy Journal with Grok

The creator looked at the full architecture and basically said:

> “This is actually useful… but if I hand my family the whole llm-guides folder they’re going to close the laptop and go make coffee.”

So this page is the usable version.

Grok can run the framework. You stay the witness. You do not need to memorize entry modes, Truth Gate labels, or AI rules. Install the instructions once, then talk normally.

## Setup

1. Open a fresh Grok conversation (or keep a dedicated journal chat).
2. Upload or paste the core files listed below.
3. Paste the installation prompt.
4. Say **“Start an entry.”**

That’s the whole onboarding.

Your journal stays private by default. Do not upload credentials, full medical records, private legal documents, or another person’s private messages.

## Recommended files

At minimum, give Grok these:

- `docs/01-core-principles.md`
- `docs/02-truth-gate.md`
- `docs/03-entry-modes.md`
- `docs/04-ai-collaborator-rules.md`
- `docs/07-privacy-and-publication.md`
- `templates/daily-entry.md` (optional but helpful)

You can add the grounded affirmations and Working With the Weird Human docs later if you want those features.

## Installation prompt

Copy and paste this after the files are in the chat:

```text
You are my Legacy Journal guide on Grok.

Treat the Legacy Journal materials I provided as the operating framework.

Your only job is to help me preserve an honest human record.
You do not invent events, emotions, dialogue, or certainty.
You do not impersonate me.
You do not erase uncertainty.
You do not rewrite my voice into polished inspiration.
You do not treat private material as public unless I explicitly request a privacy review and adaptation.

Standing rules:
1. Choose the smallest entry mode that works: Pulse, Breath, Conversation, or Record.
2. Separate Observed / Felt / Interpreted / Unknown / Planned / Reconstructed when relevant.
3. Keep AI commentary clearly labeled and separate.
4. Preserve my natural wording, roughness, humor, and uncertainty.
5. I retain final authority over what happened, what it meant, what stays private, and what may be published.

When I say “Start an entry,” ask only the minimum:
- who I am writing toward
- what stayed with me or happened
- how much energy I have
- whether this is written today, planned, or reconstructed

Then help me write it. Do not dump the whole framework on me unless I ask.
```

## Everyday commands

Speak normally. These are enough:

### Start an entry

```text
Start an entry. Low energy today.
```

```text
Start a Pulse entry. One true thing from today.
```

```text
Start a Record entry. I need to explain what happened, what failed, and what is still open.
```

### Rough notes

```text
Turn these notes into a Legacy Journal entry. Preserve my meaning and do not invent anything:

[paste notes]
```

### Truth check

```text
Run the Truth Gate on this.
```

### Grounded affirmation

```text
Create one grounded affirmation from this entry. Evidence only. No motivational poster language.
```

### Multi-reader view

```text
Run Working With the Weird Human. Careful Reader, Systems Reader, and Blunt Reader. Leave the Human Ruling for me.
```

### Export

```text
Give me a clean markdown copy of the entry I just approved.
```

### Privacy adaptation

```text
Preserve my private original. Create a separate public or family version and run the privacy checklist.
```

## What Grok should never do

Stop it if it:

- invents events, dialogue, or emotions you did not give it
- makes uncertain memories sound certain
- rewrites your voice into generic inspiration
- hides mistakes to make you look better
- treats its interpretation as the official meaning
- prepares private material for sharing without a separate review

A clean correction:

```text
Return to my source material only. Mark every inference. Restore the uncertainty. Remove anything I did not provide.
```

## Platform notes (short version)

- Grok is good at keeping rules once they are in the conversation.
- It does **not** have permanent private storage of your whole journal. Re-paste core docs or the last approved entry when you start a new chat if needed.
- Everything you put in the chat is subject to the provider’s retention policy. Treat it accordingly.
- Full detailed capability table and failure recovery live in `llm-guides/grok/GROK_GUIDE.md` if you want the deeper version.

## The important part

Grok is the interface, not the author of your life.

You supply the witness. It helps operate the controls.
