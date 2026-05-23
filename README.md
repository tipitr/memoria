# Night Market Memory

A cozy-chaotic casual game with ADHD-friendly design hidden under a magical night-market fantasy.

## What it is

You are a teen courier in a strange market that only opens before sunrise. Customers ask for odd little orders: moon tea, blue buns, star plums, fox candy. You run through the plaza, collect the right items, ignore shiny wrong ones, deliver the order, and wake one lantern on the tree.

The game is not presented as therapy, productivity, or brain training. It is a small order-running game first.

## Why this direction

The earlier MOMENTUM room prototype was calm but not fun. It felt like a meditation/productivity app, not a game. The current direction follows proven indie/casual patterns:

- immediate verb
- short order loop
- visible payoff
- tactile item pickup
- story through customers
- progression through the market itself

## Current prototype

Vertical slice:

- One low-poly night-market plaza
- Three stalls
- Six collectible items
- Five customer orders
- Tap-to-move and keyboard movement
- Basket UI
- Wrong items make funny puffs with no penalty
- Deliveries light lanterns on the tree
- Orders briefly show, then fade into memory mode
- Returning to the customer repeats the order with no shame
- Difficulty adapts between one-, two-, and three-item orders
- Full run takes a few minutes

Play locally:

```bash
open index.html
```

or:

```bash
npx serve -p 8000
```

## Hidden ADHD layer

The support layer is disguised inside normal game actions:

| Skill area | Game disguise |
|---|---|
| Working memory | Remembering customer orders |
| Impulse control | Ignoring wrong shiny items after the prompt fades |
| Planning | Choosing a route through stalls |
| Time awareness | Future market-shift structure |
| Emotional regulation | Funny, low-shame reactions |

No in-game copy says ADHD, working memory, treatment, attention training, or cognitive skill.

## What it explicitly is not

- A therapy app
- A treatment
- A medication alternative
- An EndeavorRx competitor
- A brain-training app
- A productivity app

MOMENTUM / Night Market Memory does not claim to treat ADHD, reduce symptoms, or improve attention. It is a non-clinical game prototype that uses ADHD-friendly interaction principles.

## Design constraints

- Game first, support layer hidden
- No shame
- No harsh fail state
- No medical claims
- Short loops
- Immediate feedback
- Visible fiction-based progress
- Mistakes should be funny, not punishing

## Stack

- Three.js r128
- Single-file HTML prototype
- Low-poly 3D
- Web Audio API synth sounds
- Future: Supabase for progress, Anthropic API for customer/story variation, Vercel deploy

## History

This repo started as **MEMORIA**, a dark fantasy working-memory runner, then pivoted to **MOMENTUM**, a calm room prototype. Playtesting showed both were missing the core requirement: it must be a real game.

The current direction is **Night Market Memory**, based on the fast-follower research in `docs/fast-follower-game-research.md`.

Archived builds:

- `archive/memoria-runner.html`
- Git tag: `memoria-final`

## Project skills

`.claude/skills/` holds project-local guardrails:

- `momentum-clinical-advisor` — evidence boundary and ADHD-safe design audit
- `momentum-narrative-designer` — tone, voice, worldbuilding

## License

TBD.
