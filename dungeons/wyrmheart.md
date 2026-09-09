# Wyrmheart — Adventure (1 boss)

**Boss:** Apostate Veras · **Length:** 10-15 min · **Difficulty:** **S at Adventure — but see the
Champion note below**

**Drops:** Draconic Deceit (DPS/healer), Draconic Fury (tank)

At Adventure the dangerous mobs are avoidable and the boss deals relatively low damage even when
casts are not interrupted cleanly. This is the right dungeon for a warm-up run, for teaching a new
member, or for a night when the group is tired.

> **This rating does not survive the climb.** From Adept the boss gains Splintering Ice, and by
> Champion the fight is a genuine interrupt-discipline check. See
> [At Champion and above](#at-champion-and-above). Do not walk in expecting the Adventure fight.

## Route

**Take the left path** through the humanoid mobs — Tundra Stalkers, Deceitful Scholars, Blades of
Cithrel, Coldheart Assassins. It converges with the right-hand elemental path before the boss.

*Advanced option:* Chicken the Coldheart Assassin to simplify that pull, Shroud past the two worst
packs, and Chicken a Greater Ice Elemental. This is a good dungeon to practise relic use, because
mistakes are cheap here.

## Trash that kills casual groups

| Mob | What it does | What to do |
|---|---|---|
| **Deceitful Scholar** | **Rune of Detonation** channel; spawns Volatile Orbs that chase players and pulse damage | Interrupt or CC the channel. Kite orbs away from the group. |
| **Blade of Cithrel** | **Slicing Blades** channel; gains **30% haste at low health**; Ice Breaker leap | Interrupt Slicing Blades. Dodge the leap with mobility. |
| **Eldrin Chronomancer** | **Decripify** and **Temporal Manipulation** channels; applies Erosion of Time | Interrupt both. Dispel Erosion of Time. |
| **Greater Ice Elemental** | **CC-immune.** Burrowed Strike targets a player; Avalanche is a frontal. | **Stack on the Burrowed Strike target to split the damage.** Avoid the frontal. |

## Boss: Apostate Veras

A small circular arena that gets permanently smaller as the fight goes on. Everything below is in
service of one goal: kill him before Frigid Mists eats the floor.

| Ability | Recast | Interruptible | What happens | What to do |
|---|---|---|---|---|
| **Icy Death** | 12s | **Yes** | Short cast, heavy damage on the tank | **Two players rotate it.** The third never touches it — see below |
| **Splintering Ice** *(Adept+)* | 18s | No | Debuff on a random player; on expiry or dispel they take heavy damage and fire 6 projectiles | Dispel quickly **while the target stands still and clear of the group** |
| **Howling Blast** | 25s | No | Wide cone at the current target, lethal damage, **long knockback** | Stand on the boss's **flank**, never in front. Tank points it at a wall, then steps out |
| **Glacial Spikes** | 30s | No | Long channel, 6 spikes over time under 4 party members, erupting with a **knock-up** | Move in a **tight arc around the boss**, not outward |
| **Frigid Mists** | **33s** | **Yes** | Channel leaving **permanent** slowing, damaging puddles — the longer it channels, the more puddles | **Interrupt every cast, fast.** This is the fight's difficulty dial |

### The timer drift — why the fight feels random

Glacial Spikes recasts every 30 seconds. Frigid Mists recasts every 33 seconds. The two cycles drift
apart by **exactly 3 seconds per rotation** and realign every 330 seconds — about the length of a
Champion boss fight.

So once per pull there is a stretch of two or three consecutive cycles where **Frigid Mists begins
inside the Glacial Spikes channel**. This is not the boss randomising its casts. It is a fixed beat
frequency, and it is the stretch that wipes groups, because during the overlap:

- Erupting spikes **knock your interrupters into the air**, and an airborne character cannot kick.
- Everyone is scattered and stutter-stepping, so half the group is out of interrupt range.
- Howling Blast, drifting on its own 25s cycle, may knock the tank out of range at the same moment.
- **Icy Death has come up two or three times since the last Mists.** If everyone has been kicking it
  on reflex, all three interrupts can be down at the one moment that matters.

The fight does not punish you for kicking Icy Death. It punishes you for kicking it *with everybody*.

### Interrupt discipline

**You have three interrupts, not four** — healers do not get one — on roughly 20-second cooldowns.
Run the numbers over one Frigid Mists cycle:

| | Per 33 seconds |
|---|---|
| **Supply** | 3 interrupters × (33 ÷ 20) ≈ **4.95 kicks** |
| **Demand** | 1 Frigid Mists + 2.75 Icy Death ≈ **3.75 kicks** |

**There is enough, with margin.** The assignment that covers everything:

1. **Two players rotate Icy Death.** Two kicks on 20-second cooldowns produce one every 10 seconds
   on average, against a 12-second cast — full coverage. Alternate strictly; do not both kick the
   same cast.
2. **The third player banks for Frigid Mists and never touches Icy Death.** A single 20s cooldown
   covers a 33s cadence with room to spare.
3. **Mark it with the Interrupt Tracker** (default **V**). The banked player marks Veras, so everyone
   can see the kick is held and ready without anyone calling it out.
4. **Call the convergence.** The drift is a constant 3 seconds, so you get a full cycle of warning.
   When Mists arrives noticeably closer to Spikes than it did last time, the banked kicker says so
   and stands still on the boss through the next spike set, eating the knock-up to hold position.
   **This is the real constraint** — not cooldowns, but being airborne or knocked out of range at the
   moment the cast starts.
5. **A late kick still counts.** Puddle count scales with channel duration. An interrupt 1.5 seconds
   late is enormously better than no interrupt.
6. **Agree a retreat direction.** If you genuinely cannot cover a cycle, lose the arena from one
   side rather than from the middle.

> **Note:** interrupting a boss does **not** push back its next cast — boss cadences are on dedicated
> timers, so the 4-second cast lockout does not apply. Kicking Icy Death early buys you nothing
> except a cast prevented.

## At Champion and above

- **Splintering Ice is live** (Adept+) and adds an 18s dispel obligation on top of everything else.
- **A dungeon curse applies** (Adept+). Curses that touch movement or interrupts widen the overlap
  window considerably; read the curse before you pull.
- The encounter is a **DPS race against permanent area denial**. If you are covering every interrupt
  and still running out of floor, the answer is item level, not tactics — see
  [`docs/progression.md`](../docs/progression.md) for Champion targets (~190 entry, 240-250 exit).

### The three things to get right
1. **One player banks a kick for Frigid Mists while the other two rotate Icy Death.** Every missed
   Mists permanently shrinks the arena.
2. **Fight from the flank and turn tightly during Spikes.** Both knockbacks exist to push your
   interrupters out of range at the worst moment.
3. **Stack for Burrowed Strike** on the Greater Ice Elementals in the trash — splitting it is trivial
   and not splitting it kills someone.
