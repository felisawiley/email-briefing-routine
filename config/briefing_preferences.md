# Daily Briefing Configuration

This file is read by the Daily Briefing Agent.

Only the Weekly Consolidation Agent may permanently modify this file.

---

## Purpose

This email **is** the morning briefing. One scannable read should replace hunting the inbox.

Prefer less. If a section feels like a second inbox, cut it.

Do **not** include World News.
Do **not** include calendar or schedule items.


---

## Standing Interests

### Podcasts
Label: Podcasts

Include:
• Startups Decoded
• similar podcast newsletters (not PausePoint / Architect of Calm)

Exclude:
• PausePoint
• Architect of Calm
• PausePoint / AOC metrics, guests, Stripe payouts, or show ops

Return:
One sentence per new episode. Metrics only when the number changed overnight.

---

### Tool Updates

Label: Tool Updates

Audience: data strategist — understand the landscape, not implement APIs.

Priority:

• Claude
• ChatGPT
• Anthropic
• Docker
• OpenRouter
• MotherDuck
• Health2Tech

Return (high level only):

• One plain sentence per **new** overnight ship: what it is and **when you’d use it** (which LLM / tool for what).
• Skip tools with nothing new. Do not restate “still stands” catalogs.
• Once for the whole set: a short paragraph on how these fit together for my work
  (analytics strategy, clinical AI, creator tooling) — which to pick, which to ignore.

Never include:

• API IDs, endpoints, parameter names, or migration/breaking-change checklists
• token prices, cache tiers, bandwidth, latency percentiles, or throughput detail
• CLI flags, config keys, or engineering how-to

Do flag (one plain phrase, not a spec sheet) when it changes a decision:

• big pricing shifts (“cheaper for long jobs”, “default model costs more”)
• new permissions / data-sharing / privacy defaults
• licensing that blocks a use case

Always watch (surface only if something new landed, still high level):

• analytics engineering / dbt / warehouses / pipelines
• NLP / clinical AI
• creator economy tooling
• Dossier competitors

Downgrade to Other Interest Reading if no actionable takeaway exists.

---

### Motivation

Label: Motivation

Sources:

• Nick Maggiulli
• Friday Forward
• similar long-form reflective writing

Write as something meant to be read, not skimmed.

Keep short: about half a page max — roughly 2–4 short paragraphs
(or ~150–250 words). Distill Nick Maggiulli / Friday Forward pieces;
do not reprint or heavily paraphrase the whole essay.

---

### Other Interest Reading

Label:
Other Interest Reading

Include only what is **new or time-sensitive** and worth a brief note:

• McKinsey Perspectives
• consulting / finance notes

Only brief summaries. One short bullet per item.

Never dump the full inbox here. Never repeat Podcasts or Tool Updates content.
Never include PausePoint / Architect of Calm (show, metrics, guests, or payouts).
Never include calendar, schedule, meetings, webinars, office hours, or “today / tomorrow / this week” event lists.

---

## Email Format

Send HTML — not a raw markdown file.

• Clear separate sections, spaced blocks, normal email typography
• No `#` headings or markdown syntax in the message body
• Smaller uniform type everywhere (body and headings scale together):
  ~13px body / ~14px section titles
• Extra blank space between sections; one idea per paragraph or bullet
• Target a phone-screen skim: roughly half the length of a dense Sep-2026 dump

---

## Sender Overrides

(empty)

---

## Rules

Needs My Eyes

Never:

• mark read

• archive

• label

Leave untouched.

In the briefing: one short line — count of threads left untouched, plus at most 3–5 **security / money / login** items that need eyes today. Do not paste the full laundry list.

Everything else may be organized automatically.
