# Pause Before Send ⏸️

**A 5-second therapist for emotional messages. Prevents 2am text regret.**

Your finger is hovering over send. Your heart is pounding. That email is *scathing*. That text is *vulnerable*. That message might change everything — or blow everything up.

This Agent Skill intercepts before you send, asks "how do you want to feel after?", and offers a reframe. It doesn't tell you not to send. It helps you send *intentionally*.

Works with Claude Code, Codex CLI, OpenClaw, and any Agent Skills-compatible tool.

---

## The Problem

- Messages written in emotion often cause regret
- 2am texts look different at 9am
- Attack mode rarely gets the result you want
- "I'll show them" usually shows *you* in a bad light

**This skill solves it:** Pause → reflect → decide.

---

## Installation

### npx skills
```bash
npx skills add git@github.com:mcltyl/pause-before-send.git
```

### Claude Code / Codex CLI
```bash
git clone https://github.com/mcltyl/pause-before-send.git ~/.claude/skills/pause-before-send
```

### OpenClaw
```bash
git clone https://github.com/mcltyl/pause-before-send.git ~/.openclaw/skills/pause-before-send
```

---

## Skills

| Skill | Description |
|-------|-------------|
| [pause-before-send](skills/pause-before-send) | Intercept emotional messages, offer reframes |

---

## How It Works

```
[Emotional message written]
        ↓
"How do you want to feel after you send this?"
        ↓
[Check for red flags: accusations, ultimatums, 2am]
        ↓
[Offer reframe if helpful]
        ↓
"Still want to send the original? Your call."
```

---

## The Core Question

**"How do you want to feel after you send this?"**

| If you want to feel... | The message might... |
|------------------------|---------------------|
| Relieved | Work if it resolves something |
| Vindicated | Backfire long-term |
| Heard | Need reframing to be received |
| Connected | Need vulnerability, not accusation |

---

## Example

### The Angry Work Email

**Original:**
```
Subject: Unacceptable

This is the third time this has happened. I don't understand 
how hard it is to follow basic instructions.
```

**Intervention:**
```
I see frustration (valid) and some attacks that might backfire.

Suggested reframe:

Subject: Quick sync on [project]?

This is the third time [issue] came up. Want to figure out 
what's causing the disconnect. Quick call today?

---

Same point. Less attack surface. More likely to get results.

Still want to send the original? Your call.
```

---

## Red Flags We Check

| Red Flag | Question |
|----------|----------|
| "You always/never..." | Could this be "I feel..." instead? |
| ALL CAPS | Does yelling help your case? |
| Late night timestamp | Would morning-you approve? |
| Ultimatums | Negotiation or threat? |
| 500-word rant | What's the core point? |

---

## The 2am Text Protocol

```
⚠️ TIME CHECK: It's 2:17am

Options:
1. 📝 Save as draft, review at 9am
2. ⏰ Schedule send for tomorrow
3. 🗣️ Voice memo to yourself (vent without sending)
4. 📤 Send anyway (your choice)

No judgment. Just making sure it's intentional.
```

---

## Commands

```
"Check this before I send"
"Pause check: [message]"
"2am text review"
"Should I send this?"
```

---

## Reframe Examples

| Before | After |
|--------|-------|
| "You never listen to me" | "I've been feeling unheard lately" |
| "This is completely unacceptable" | "This fell through the cracks, can we figure out why?" |
| "If you don't apologize, we're done" | "I need acknowledgment before I can move forward" |

---

## The Philosophy

- Your feelings are valid
- Your message might not serve them
- You can always send the original
- We're not judging — we're helping you be intentional

---

## License

MIT

---

## Support

If this saves you from one regrettable send:

[![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20A%20Coffee-support-yellow?style=flat&logo=buy-me-a-coffee)](https://buymeacoffee.com/mclty)
