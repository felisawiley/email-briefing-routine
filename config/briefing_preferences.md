# Daily Briefing Configuration

This file is read by the Daily Briefing Agent.

Only the Weekly Consolidation Agent may permanently modify this file.

---

## Standing Interests

### Podcasts
Label: Podcasts

Include:
• Startups Decoded
• PausePoint
• similar podcast newsletters

Return:
One sentence per episode.

---

### Tool Updates

Label: Tool Updates

Priority:

• Claude
• ChatGPT
• Anthropic
• Docker
• OpenRouter
• MotherDuck
• Health2Tech

Return:

• One technical sentence per update (what shipped / changed).

Then, once for the whole set (not per item):

• A short layman’s paragraph: how these updates connect to my world
  (analytics engineering, clinical AI, creator tooling, or adjacent work),
  how they connect to each other, or one idea worth taking from them.

Keep Tool Updates tight. No multi-paragraph write-ups per product.

Downgrade to Other Interest Reading if no actionable takeaway exists.

Always include:

• analytics engineering
• dbt
• warehouses
• pipelines
• NLP
• clinical AI
• creator economy tooling
• Dossier competitors

Always flag:

• pricing changes
• API changes
• licensing
• new permissions
• data-sharing defaults
• privacy changes

---

### World News

Label: World News

Return:

3–5 AP-style summaries.

If a trusted news digest exists in the inbox,
use that instead of searching.

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

Include:

• McKinsey Perspectives

• consulting

• finance

Only brief summaries.

---

## Email Format

Send HTML — not a raw markdown file.

• Clear separate sections, spaced blocks, normal email typography
• No `#` headings or markdown syntax in the message body
• Smaller uniform type everywhere (body and headings scale together):
  ~13px body / ~14px section titles

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

Everything else may be organized automatically.
