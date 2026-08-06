# email-briefing-routine

Daily email briefing system with one configuration document and two agents.

## Architecture

```
config/
    briefing_preferences.md   ← single editable source of truth
briefings/
    YYYY-MM-DD.md             ← archived daily briefings
logs/
    feedback_log.md           ← raw corrections from daily runs
agents/
    daily_briefing.md         ← execution only (reads config)
    weekly_consolidation.md   ← learning agent (rewrites config)
```

**Daily Briefing Agent** reads preferences, builds the briefing, archives it, commits/pushes, emails when available, and appends raw feedback. It never rewrites preferences.

**Weekly Consolidation Agent** is the only writer of `config/briefing_preferences.md`. It consumes the feedback log, applies permanent changes (newest wins), and clears resolved feedback.
