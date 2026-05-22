# MOMENTUM

A cozy emotional-regulation game disguised as a quiet room.

For ADHD brains. (Made by one.)

## What it is

You enter a small bedroom-studio. It's late. The lamp is warm. Rain on the window. A small companion drifts by the desk.

When something is heavy, you gather a wisp — and a *tiny first step* appears. Then you leave. Do the thing (or don't). Come back whenever. The room stayed warm for you.

The reward is **state improvement**, not task completion. The room calms with you. The companion stays.

## What it explicitly is not

- A productivity app
- A task manager
- A brain-training game
- A therapy app

No streaks. No daily goals. No "you missed N quests." No XP. No leveling. No push notifications.

## Status

v0.1 — the room exists. No interaction yet. Just sit in it.

Next: the gather mechanic. Wisps drifting toward the companion → tiny quests.

## Stack

- **Three.js r128** — 3D scene + post-processing (bloom, grain, vignette)
- **Anthropic API** — light LLM assistance for task-classification → tiny-quest generation (planned)
- **Supabase** — state persistence across the "world sleeps while you act" loop (planned)
- **Capacitor.js** — mobile wrap (planned)
- **Vercel** — deploy

## History

This project pivoted from **MEMORIA** — a dark fantasy narrative working-memory game — in May 2026 after playtests revealed that the runner format created ADHD anxiety. The multi-agent brainstorm at `momentum_game_v3_brainstorm.md` reframed the entire approach: from cognitive training to emotional regulation, from grief to curiosity, from a chapter game to a room.

The final MEMORIA commit is tagged `memoria-final`. The runner build is preserved at `archive/memoria-runner.html`.

## Design constraints (non-negotiable)

- Reward = state improvement, not task completion
- No streaks, percentages, daily goals
- No push notifications, ever
- The room is always welcoming on return — no catch-up screens, no shame
- The game wants you to leave it (exit velocity > engagement)
- Companion never judges, pushes, prescribes, or moralizes
- State vars (energy, overwhelm, focus, momentum, noise) are computed, never displayed
- No "challenge mode" / "perfect day" / completable room

## Project skills

`.claude/skills/` holds project-local guardrails:
- **`momentum-clinical-advisor`** — audits every feature against ADHD intervention research and ethics
- **`momentum-narrative-designer`** — governs tone, voice, copy. Bans productivity language.
- Third-party skills via `npx skills` — Three.js, Supabase, accessibility, etc.

## Local setup

```bash
npm install                # nothing to install yet — single file prototype
npx skills install         # restore third-party skills from skills-lock.json
```

Open `index.html` directly, or:

```bash
npx serve -p 8000
```

## License

TBD.
