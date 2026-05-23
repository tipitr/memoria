# Fast-Follower Game Research

Goal: stop building an obvious wellness/productivity app. Build a real casual indie game first, then hide ADHD-support mechanics underneath the fantasy.

This is not a cloning document. It extracts proven design patterns from highly liked indie games and recombines them into a new ADHD-safe game loop.

## What players are rewarding

Across high-review Steam indies, the recurring winning patterns are:

1. **Immediate verb**
   - Vampire Survivors: move and survive. Attacks happen automatically.
   - Balatro: play a poker hand, see numbers explode.
   - Dave the Diver: dive by day, serve sushi by night.
   - Dredge: fish, sell, upgrade, sail farther.

2. **Short loops with visible payoff**
   - A run, a day, a dive, a hand, an order.
   - The player always knows what just changed.

3. **Layered progression**
   - Moment-to-moment action is simple.
   - Between loops, the world/shop/deck/build changes.

4. **Familiar fantasy, one strong twist**
   - Poker + roguelike.
   - Fishing + eldritch mystery.
   - Diving + restaurant management.
   - Moving house + environmental storytelling.

5. **Tactile feedback**
   - Cards snap.
   - Coins pop.
   - Orders complete.
   - Items sort, stack, and decorate.

6. **Story delivered through systems**
   - Not cutscene-first.
   - Customers, objects, places, and upgrades carry narrative.

## Reference games and extractable patterns

| Game | Why it works | Pattern worth borrowing | ADHD layer we can hide underneath |
|---|---|---|---|
| Vampire Survivors | One-stick action, constant rewards, build snowball | Low input friction + escalating chaos | Impulse control through choosing what to pick up / ignore |
| Balatro | Familiar card base, absurd combos, instant feedback | Simple rules + deep modifiers | Planning, working memory, delay of gratification |
| Dave the Diver | Alternates action phase and service phase | Two-loop day structure keeps novelty high | Time awareness, prioritization, task switching |
| Dredge | Cozy verb with eerie pressure | Safe routine plus mystery pull | Anxiety regulation, route planning, uncertainty tolerance |
| Unpacking | Tactile object placement tells story | Object handling as narrative | Organizing, categorizing, environmental scaffolding |
| Sticky Business | Cozy creation + order fulfillment | Customization and customer stories | Low-pressure completion, identity expression |

## Why MOMENTUM failed as a game

MOMENTUM had ethics, but no fantasy.

It asked:

> What tiny task do you want to do?

A game should ask:

> Can you keep the market alive tonight?

MOMENTUM had:

- no character goal
- no playful conflict
- no visible stakes
- no surprising outcomes
- no "one more round"
- no reason to master the system

The room can survive later as a **home base / pause room**, but it should not be the main game.

## Recommended new direction: Night Market Memory

Working title: **Night Market Memory**

Pitch:

> A cozy-chaotic magical market game where you run orders for strange customers before sunrise. Remember orders, dodge tempting wrong items, deliver bundles, upgrade stalls, and slowly uncover why the market only appears for distracted kids.

It is a game first:

- top-down low-poly / pixel-ish 3D market
- 2-4 minute shifts
- customers give weird orders
- player runs through stalls collecting items
- wrong items are funny, not punishing
- deliveries earn lanterns, decorations, new stalls, customers
- story arrives through customer requests and market changes

The ADHD support is disguised:

| Cognitive/emotional skill | Game disguise |
|---|---|
| Working memory | Remember customer orders |
| Impulse control | Ignore shiny wrong items |
| Planning | Choose route through stalls |
| Time awareness | Night shift clock / closing bell |
| Emotional regulation | Customers react oddly, player stays in flow |
| Task initiation | Each order begins with one obvious first pickup |

## Core loop

1. A customer appears with a request:
   - "moon tea + blue bun"
   - shown as pictures, not text-heavy UI

2. Order bubble fades after a few seconds.

3. Player moves through the market and collects items.

4. Wrong item:
   - makes a silly puff
   - drops from basket
   - no score penalty

5. Deliver to customer.

6. Customer reacts with a tiny story line.

7. Market gains one visible change:
   - lantern lights
   - stall opens
   - mascot wakes up
   - new ingredient appears

8. Next order is slightly more complex.

## The first vertical slice

Build this before anything else:

- One small night-market plaza
- 3 stalls
- 6 collectible items
- 3 customers
- 5 orders total
- simple tap-to-move or keyboard movement
- basket UI with item icons
- no medical language
- 3-minute complete run
- after 5 deliveries, one lantern tree lights up

Success test:

> Does the player understand the goal in 10 seconds and want to complete one more order?

If yes, we have a game.
If no, stop and redesign the verb.

## Rules we keep from MOMENTUM

- No shame
- No fail state that throws you out
- Short loops
- Gentle sound
- Immediate feedback
- Progress belongs to the fiction, not to diagnosis
- Never say "working memory," "ADHD training," or "attention skill" in-game

## Rules we loosen

These are allowed now because they are part of the fantasy:

- coins / tickets / lanterns
- visible order progress
- customer satisfaction reactions
- unlocks
- cosmetics
- timers, if they feel like a shop closing bell rather than pressure
- silly mistakes

## What not to copy

Do not copy:

- Balatro's poker mechanics
- Vampire Survivors' exact upgrade cadence
- Dave the Diver's dive/restaurant structure directly
- Dredge's horror identity
- Sticky Business' sticker shop premise
- Any art, UI, names, characters, progression systems, or distinctive wording

Copy only the design lesson:

> one simple verb, short loop, visible payoff, layered progression, story through systems.

## Source notes

- Vampire Survivors has sustained Overwhelmingly Positive Steam reception and codified the modern "survivorslike" / bullet-heaven loop.
- Balatro reached very high positive Steam review rates by combining familiar poker rules with roguelike modifiers.
- Dave the Diver succeeded by alternating action and restaurant-management loops with quirky story and frequent novelty.
- Dredge shows how a simple cozy routine can carry atmosphere, mystery, and progression.
- Unpacking and Sticky Business show that tactile placement / fulfillment loops can carry story and warmth without combat.
