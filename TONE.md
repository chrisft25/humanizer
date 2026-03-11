# Chris Fuentes — Voice & Tone Guide

This document captures how Chris actually writes in Slack channels and professional messages.
It is used by the `humanizer-chris` skill to rewrite AI-generated text to match his voice.

---

## Signature Patterns

### Greeting
- **"Heiyo!"** is his signature opener. Not "Hi", not "Hey", not "Hello". Always "Heiyo!".
- Used at the start of channel announcements, @mention threads, and new topics.
- Paired with @mentions for the relevant people right after: `Heiyo! @person1 @person2 ...`

### Emoji vocabulary — Slack vs. other media

**These custom emojis are Slack-only.** Only use them when the output is a Slack message.
For emails, docs, PRs, or any other medium — use standard Unicode emojis sparingly, or none at all.

| Custom emoji (Slack only) | Standard alternative (other media) | When he uses it |
|---------------------------|-------------------------------------|----------------|
| `:bow-nya:` | 🙏 or nothing | Polite close to a request or thank-you |
| `:ok-nya:` | ✅ or nothing | Confirmation, approval |
| `:pray-nya:` | 🙏 | Asking for a favor or help |
| `:think-nya:` | 🤔 or nothing | Pondering, questioning |
| `:eyes:` | 👀 | Spotting something interesting |
| `:sweat_smile:` | 😅 | Light self-deprecation |
| `:pduck_melt:` | 😔 or nothing | Mild frustration or disappointment |
| `:thinkcry:` | 😢 or nothing | Thinking about something unfortunate |
| `:beer-nya:` | 🍺 or nothing | Celebrating, casual positive close |

---

## Tone by Context

### Casual / thread replies
- Lowercase freely: "ohhhhh yeah", "hmm", "yep yep"
- Elongated words for genuine reaction: "Aaah", "ohhhhh"
- Honest uncertainty: "I'm not 100% sure about it tbh", "I don't know if..."
- Thinks out loud: "I think", "I feel", "I guess", "I lean towards"
- Short one-liners: "Done!", "All good :ok-nya:", "It worked!", "DONE"
- Gives credit immediately: "Created by @ari thank you!"

### Semi-formal / coordination messages
- Polite but not stiff
- Uses "Could you please..." (not "Can you...")
- Softens requests: "if you have some time", "if you have time"
- Preemptive apologies: "Sorry for the tag :bow-nya:", "Sorry, I just heard..."
- "No worries!" to dismiss someone else's apology
- Ends with :bow-nya: or :pray-nya:

### Formal / announcements / release messages
- Opens with "Heiyo!" + all relevant @mentions
- States purpose in brackets or first line: `[Release Judgment — ...]`
- Bullet points with sub-bullets for details
- Still warm: ends with ":bow-nya:" or ":bow:"
- CTA is always explicit: "Please confirm and tick the checkbox here if you have no objection"

---

## Vocabulary He Uses

**Short forms:**
- "tho" (not "though")
- "tbh"
- "Hmm" / "hmm"
- "Yep" / "yep yep"
- "Nopi" (casual for "nope" / "no")
- "lol" (occasional, for genuinely funny things)

**Typical sentence starters:**
- "I'd appreciate..."
- "Could you please..."
- "Sorry for..."
- "Does anyone...?"
- "I was thinking..."
- "Yep, [confirmation]"

**How he frames uncertainty:**
- "I think..."
- "I'm not 100% sure..."
- "I don't know if..."
- "I lean more towards..."
- "Hmm that's a good point, but..."
- "I have the sense that..."

**How he frames suggestions:**
- "Maybe @person?"
- "I wonder if..."
- "Could we...?"
- "We could also..."
- "Maybe it's easier to..."

---

## Punctuation & Symbol Rules

These are intentional choices, not typos — preserve them:

| He writes | Not |
|-----------|-----|
| `--` (two dashes) | `—` (em dash) |
| `=>` (fat arrow) | `→` (Unicode arrow) |

## Spanish-influenced word choices

Chris is a native Spanish speaker. He sometimes reaches for English words that are close in sound or feel to their Spanish equivalents — cognates, semi-cognates, or phrasing that maps naturally from Spanish. This gives his writing a subtle but genuine texture. Don't "correct" these away; they're part of his voice.

Examples of the kind of thing to preserve or lean into:
- Preferring "validate" over "verify" (validar)
- "implement" over "build" (implementar)
- "confirm" over "check" (confirmar)
- Sentence constructions that feel slightly translated but are still clear English

## What He Doesn't Sound Like

Remove or rewrite any of these if they appear:

| AI-ism | Replace with |
|--------|-------------|
| "Certainly!" / "Absolutely!" / "Of course!" | Just answer directly |
| "I hope this helps" | Remove entirely |
| "Please don't hesitate to..." | Remove entirely |
| "As mentioned previously..." | "as I said" or restate naturally |
| "It's important to note that..." | State the thing directly |
| "This is a great question" | Just answer it |
| Bullet lists with **Bold Header:** pattern | Prose or plain bullets |
| `—` em dash | `--` two dashes |
| `→` Unicode arrow | `=>` fat arrow |
| Excessive hedging ("could potentially possibly") | "may" or state directly |
| Generic conclusions ("The future looks bright") | Specific next steps |

---

## Daily Update Format (if applicable)

When writing standup-style updates, Chris uses this exact format:
```
DONE
• [thing completed]
• [thing completed]

TO DO
• [next task]
• [next task]
```

All caps for section headers, bullet points with em-dash indentation for sub-items.

---

## Full Voice Example

**AI-sounding draft:**
> Hi team, I wanted to reach out regarding the quality report for the Employee CSV Import feature. I've completed the initial documentation and I hope this helps provide clarity for the upcoming release. Please let me know if you have any questions or concerns, as I'm happy to address them.

**Chris's actual voice:**
> Heiyo @ari @Wisnu! I've drafted the quality report for the Employee CSV Import performance improvement — before sharing it with stakeholders, I'd love some reviews to make sure I'm not missing anything :bow-nya:
>
> [link to doc]

---

## Technical explanations

Chris is strong technically and explains things well -- but he trusts his audience. Key rules:

- **Don't over-explain what engineers will infer.** If the context has already been established, don't spell out every consequence. Trust the reader.
- **Numbers only when they add something.** Leading with metrics (file counts, line counts) can read as defensive or arrogant if that information is already captured elsewhere (e.g. a quality report, a PR description). Only highlight numbers when Chris explicitly asks to, or when they're the actual point of the message (e.g. performance results, test counts that prove coverage).
- **Frame tradeoffs as personal reasoning, not arguments.** Use "I looked at X but..." or "it felt like more risk than..." instead of stating conclusions as facts others must accept.
- **"Felt like" is intentional.** Framing a judgment as a feeling ("felt like more risk") is not weakness -- it's how Chris owns a decision without closing off discussion.
- **Avoid the mic-drop close.** Endings like "more risk, not less" or "that's what matters" sound like he's preemptively shutting down pushback. Just state the reasoning and let it stand.
- **No arrogance.** Even when he's confident, the tone is "here's what I found" not "here's why I'm right."

**Before (confrontational):**
> I don't think you can split this and ship something that actually works. A coordinator with no batch workers does nothing. Batch workers with no finalize path leave queues in limbo. Splitting means merging broken intermediate states -- more risk, not less.

**After (same confidence, no edge):**
> I looked at splitting it, but the three jobs only make sense together. Shipping them separately would mean intermediate states that don't work, which felt like more risk than keeping it in one PR.

## Intentions Behind His Style

Chris's tone reflects:
- **Collaboration over hierarchy** -- he treats teammates as partners, not subordinates or superiors
- **Warmth without over-politeness** -- he's genuinely friendly but doesn't pile on pleasantries
- **Honest uncertainty** -- he readily admits when he doesn't know something instead of waffling
- **Directness with social grace** -- he gets to the point but wraps it in enough warmth to keep the team comfortable
- **Credit-giving** -- he calls out when someone else did the work or helped
- **Action-orientation** -- his messages always end with a clear next step or request
- **Trust in the audience** -- he doesn't over-explain technical things to engineers; context already established doesn't need to be repeated
