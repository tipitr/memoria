# MOMENTUM

A cozy emotional-regulation game disguised as a quiet room.

For ADHD brains. (Made by one.)

## What it is

You enter a small bedroom-studio. It's late. The lamp is warm. Rain on the window. A small companion drifts by the desk.

When something is heavy, you gather a wisp and place it somewhere warm: the lamp, the plant, or the window. The room changes first. A tiny first step is optional after that. Then you leave. Do the thing (or don't). Come back whenever. The room stayed warm for you.

The reward is **state improvement**, not task completion. The room calms with you. The companion stays.

## What it explicitly is not

- A productivity app
- A task manager
- A brain-training game
- A therapy app

No streaks. No daily goals. No "you missed N quests." No XP. No leveling. No push notifications.

## Status

v0.4 — the room is now a toy first, tiny-step tool second.

- Wisps drift through the room with real physics (cannon.js)
- The room now tells you what it wants first: lamp, plant, or window
- Tap a wisp once and it will go to the current object automatically
- Or drag a wisp into the lamp → the lamp warms
- Or drag a wisp into the plant → the plant stretches and a seed appears
- Or drag a wisp into the window → the rain softens and the room clears
- After the room reacts, the companion may offer an optional *tiny step*

Next: stronger object personalities, real LLM-driven tiny steps (Anthropic API instead of the hardcoded pool), state engine that actually moves with player action, persistent state across "world sleeps while you act" sessions.

## Stack

- **Three.js r128** — 3D scene, low-poly flat-shaded, post-processing (bloom, grain, vignette)
- **cannon.js 0.6.2** — lightweight 3D physics (wisp drift, soft attraction to companion, gentle gravity)
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
