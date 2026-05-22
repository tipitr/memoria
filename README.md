# MEMORIA

A dark fantasy narrative game for ADHD teens.

The clinical layer is invisible. The story is what the player experiences. Cognitive skills are trained through play, never named in the text.

## Status

Early prototype. Chapter 1 — *Lethe City* (Working Memory) — playable. Chapters 2–5 in design.

## Stack

- **Three.js r128** — 3D game engine
- **Anthropic API** — ECHO (NPC) dialogue, adaptive feedback
- **Supabase** — player progress
- **Vercel** — deploy
- **Meshy AI / Higgsfield / Nanobanana** — asset pipeline
- **Capacitor.js** — mobile wrap (planned)

## Design constraints (non-negotiable)

- No skill tree, no XP, no "EF mastery" UI
- No variable-ratio reward schedules
- No "brain training" / therapeutic claims in any surface
- Failure is narrative, never penalty
- ECHO never breaks the fourth wall
- Adaptive difficulty based on individual response time, not preset rounds
- ~25 min therapeutic session window (EndeavorRx precedent)

## Project skills

The `.claude/skills/` directory holds three project-local skills that govern design:

- **`memoria-clinical-advisor`** — audits chapters against Barkley EF model, EndeavorRx precedent, and transfer-effect literature. Refuses to rubber-stamp gimmicks.
- **`memoria-narrative-designer`** — keeps the story, voice, and world coherent. Refuses generic dark-fantasy tropes and any clinical leakage into the fiction.
- Third-party skills (Three.js, Supabase, accessibility, etc.) installed via `npx skills` — see `skills-lock.json`.

## Chapter structure

| Chapter | Place | Skill (hidden) |
|---|---|---|
| 1 | Lethe City | Working memory |
| 2 | The Threshold District | Response inhibition |
| 3 | The Cartographer's Hollow | Planning |
| 4 | The Drowned Village | Emotion regulation |
| 5 | The Garden of Once | Time awareness |

## Local setup

```bash
npm install
npx skills install   # restores third-party skills from skills-lock.json
```

## License

TBD.
