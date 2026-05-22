# Project history

Honest record of what this project was, what it became, and why.

## v0 — MEMORIA (May 2026)

The project started as **MEMORIA**: a dark fantasy narrative game for ADHD teens. The thesis was that cognitive skills (working memory, response inhibition, planning, emotion regulation, time awareness) could be trained *invisibly* through story — five chapters, each disguising one Barkley executive-function construct as a story mechanic.

### What got built
- Chapter 1: a Three.js working-memory tap-the-sequence game in a place called Lethe City
- Two project skills: `memoria-clinical-advisor` and `memoria-narrative-designer`
- ECHO — a small companion NPC voiced through Web Audio synths
- A real opening story card, mid-run beats, per-shard memory fragments, and a closing reveal (a friend named Sam)

### What was learned
1. **Simon Says in a dark mood is still Simon Says.** The mechanic was a commodity. ADHD teens won't sit through a contemplative tap-the-orb game when their phones are full of Geometry Dash and Vampire Survivors.
2. **A runner with memory orbs solved the "boring" problem but introduced anxiety.** Forward motion + memory load + soft grief story = ADHD-anxious nervous system overload. The clinical advisor skill warned about exactly this. We built it anyway.
3. **Story tone matters more than story presence.** "She's losing him. Don't let go" creates pressure. "She's looking for someone. She remembers how" creates curiosity. Same mechanic, opposite body feeling.

The runner build is preserved at `archive/memoria-runner.html`. The final commit is tagged `memoria-final`.

## The pivot (May 2026)

A multi-agent brainstorm document (`momentum_game_v3_brainstorm.md`) reframed the project. Key insights:

- **Reward = state improvement, not task completion.** ADHD doesn't lack motivation; it lacks state-transition control. Reward the room becoming calmer, not the user completing tasks.
- **Coexist with cognitive weather. Don't fight ADHD.** Reframe the protagonist from "someone overcoming a deficit" to "someone navigating weather."
- **Recovery design — the room stayed warm for you.** No streak shame. No catch-up.
- **Exit velocity > engagement.** The best progression happens AFTER the user leaves the app. The "world sleeps while you act" loop.
- **One room MVP.** Scope discipline. One small space, fully polished, beats five chapters built rough.

The MEMORIA runner — competent, mood-correct, occasionally beautiful — failed the only test that matters: *does it leave the user better than it found them?* It did not.

## v1 — MOMENTUM (May 2026 onward)

The pivot. A cozy bedroom-studio. A small companion who is glad you came back. A verb (**gather**) that turns scattered intentions into tiny first steps. A room that responds to your real-life weather over real days.

The clinical thesis updates from *"cognitive training disguised as fantasy"* to *"emotional regulation disguised as a calm room."* The latter has more empirical support and zero gimmick risk.

What survives the pivot:
- The Three.js scene scaffolding
- The post-processing pipeline (bloom, grain, vignette) — perfect for cozy interiors
- The Anthropic API and Supabase integration plans
- The expert shortlist (same audience, same researchers)
- The discipline of the two project skills (now rewritten for MOMENTUM)

What was dropped:
- The Memory Runner mechanic
- Lethe City, Sam, the five chapters
- ECHO as defined
- The cognitive-training claim

The repo retains its old name (`memoria`) but the project is now MOMENTUM.

## Lessons

For anyone reading this later, including future-me:

1. Ship the prototype. Play it. Listen to your own nervous system. The skills know more than I do.
2. The clinical advisor said "urgency is the toxic input." I built urgency anyway. Don't.
3. The narrative designer banned "fight ADHD" framing. I built it anyway. Don't.
4. The audience is *already* anxious. The game's job is to subtract anxiety, not add story-flavored anxiety.
5. A multi-agent brainstorm from a different angle can save weeks of polish on the wrong thing.
6. Scope discipline (one room) beats ambition (five chapters).
7. The best ADHD design pushes you *out* of the app, not into it.
