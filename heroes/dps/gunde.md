# Gunde — Dual-Axe Berserker (DPS)

**Identity:** Season 3's new hero. A melee DPS who applies and stacks **Rend** bleeds, then converts
the accumulated damage into burst through abilities such as Slaughter.

Gunde is the most build-divergent hero in the roster: his three builds have **three genuinely
different stat priorities**. Identify your build before you itemise.

**Interrupt: Jawbreaker** (melee). He also carries **Warbound**, a directional leap, and **Butcher's Hook**, which pulls a target to him — both are uptime tools after a knockback, not just movement. All interrupts lock the target out of casting for **4 seconds**, except against dedicated boss timers. Plan on a **~20s cooldown**; see [interrupts.md](../../docs/interrupts.md).

## Stat priority — by build

| Build | Priority | Notes |
|---|---|---|
| **Grim Carve** | Haste > Expertise > Crit > Spirit | Keep Spirit to no more than **10-15%** |
| **Heart Splitter** | Haste >>> Crit > Spirit > Expertise | Haste dominates; keep Spirit 10-15%; **avoid Expertise** |
| **Spirit Bloodcraze** | Spirit > Haste > Expertise = Crit | Stack Spirit to **~50%**, then maximum Haste, with minimal Crit and Expertise |

## Talent build — Grim Carve (starter, 14 points)

| Tier | Talents |
|---|---|
| 2 | Death's Arc (2), Raven's Precision (2) |
| 3 | Grim Harvest (2) |
| 4 | Sundered Flesh (1), Crimson Strikes (1), Deep Rend (1) |
| 5 | Darkening Hearts (2), Murder of Crows (2) |
| 6 | Massacre (2) |
| 7 | Slayer's Grin (1), Frenzied Reign (1), Bloodbath (1) |
| 8 | Bloodcraze (3), Oathshatter (3), Carnage (3) |
| 9 | Superior Serration (1), Ancestral Instinct (1), Harvester's Toll (1) |

**What it does:** great AoE damage and decent single target, by maximising Grim Carve and Blood Arc
usage. **Its weakness:** it struggles with priority damage *while* doing AoE damage.

### Variants

| Build | Focus |
|---|---|
| **Oathshatter Heart Splitter** | Best single-target specialisation. Same base talents, weighted into Oathshatter at tier 8. |
| **Bloodcraze Spirit Blood Feather** | Strong AoE burst. Emphasises Bloodcraze generation and pairs with the ~50% Spirit itemisation. |

> The guidance from top players is explicit: understand *why* each talent is selected rather than
> copying the list. Gunde rewards adaptation more than any other hero.

## Traits

**Major Traits (top tier):** Amethyst Splinters, Brave Machinations, Diamond Strike,
Emerald Judgement, Heroic Brand, Martial Initiative, Ruby Storm, Sapphire Aurastone,
Visions of Grandeur

**Heroic Traits:** Hidden Power, Hunter's Focus, Inspired Allegiance, Kindling,
Navigator's Intuition, Patient Soul, Seized Opportunity, Vengeful Soul, Willful Momentum

**Defensive Traits:** Divine Mediation, First Man Standing, Grounded Spirit, Heart of Stone,
Iron Spikes, King of the Hill, Latent Resurgence, Stalwart Readiness, Treasure Hunter's Delight

**Necklace Attunements, in priority order**
1. **The Beetle** — universal damage reduction
2. **The Lake** — 20% AoE damage reduction
3. **The Mountain** — strong defensive option
4. The Tower and The Dune — solid alternatives

**Blessings:** all 14 options are live for Gunde; selection depends on the specific dungeon
mechanics and which of the three builds you are running.

## Gems

**Early game:** Ruby > Diamond > Emerald > Sapphire > Amethyst > Topaz. Use tier 1-2 gems initially.

**Endgame — the same for all three builds:**

| Colour | Node |
|---|---|
| Emerald | **10** |
| Amethyst | 6 |
| Sapphire | 6 |
| Ruby | 6 |

**Requirement:** all gem mods must share the same colour. Gem placement across gear slots is
otherwise flexible.

## Gear

- **Sets:** Seal of the Heskyr + Death's Grasp. Dark Prophecy is excellent for Heart Splitter given
  how hard that build leans on Haste.
- **Relics:** one of each type, then reforge duplicates.

## Single-target damage

**Run Oathshatter Heart Splitter.** This is not a preference. Grim Carve is described by its own
source as *"great AoE damage and decent single target"* whose weakness is that it *"struggles with
priority damage"*. On a boss with no adds, you are paying for AoE you will never use.

**Priority order:**

1. **Blood Arc** — for the Serrated Edge buff
2. Rupture
3. **Heart Splitter**
4. Grim Carve
5. Reaver's Edge
6. Double Strike

### Do not press Slaughter on a boss

This is the single largest single-target mistake available to Gunde, and it looks like the right
button:

| Ability | What it does to Rend |
|---|---|
| **Slaughter** | **Removes all Rend stacks** and converts them into a 3-second DoT dealing **160%** of total Rend damage |
| **Heart Splitter** | Applies exsanguinate for **30% of total Rend damage — without consuming it** |

Slaughter cashes out your Rend once. Heart Splitter milks it **repeatedly and keeps it**. On a single
target you want the Rend pool large and permanent, taxed over and over, not spent. The source is
explicit: only Slaughter when the target is about to die from it or you are swapping targets, because
*"Rend on your main target is extremely important for Oathshatter and Exsanguinate damage."*

### Build the pool, then tax it

- **Reign In Blood** makes direct ability damage apply an **additional 50% of its damage as Rend**.
  This is your Rend-building window — use it early and feed the pool that Heart Splitter then milks
  for the rest of the fight. Sequence matters: build first, exsanguinate after.
- **Fasted Strike** (weapon ability) grants **6 seconds of cooldown acceleration**. Cram as many
  priority abilities into that window as you physically can; it is the highest-density damage you get.

### Itemising for it

Heart Splitter runs **Haste >>> Crit > Spirit > Expertise**. Two things make this build unusual:

- **Keep Spirit at 10-15%.** Do not drift upward; that is the Bloodcraze line, not this one.
- **Avoid Expertise.** This is the only build in the roster where a secondary stat is actively wrong
  rather than merely low-priority. Reforge out of it.
- **Dark Prophecy** (+25% Haste procs) is excellent here, given how hard the build leans on Haste. It
  drops in [The Heart of Tuzari](../../dungeons/heart-of-tuzari.md).

**Melee uptime is your whole game.** Gunde is the DPS most punished by knock-ups and knockbacks, so on
[Wyrmheart](../../dungeons/wyrmheart.md#squeezing-out-the-damage) he should **not** be the player
banking the Frigid Mists interrupt — he is the one most likely to be airborne when it is needed.

## AoE damage

**Switches on at 3+ targets, where Grim Carve becomes the priority.** Run the base Grim Carve build
for pull-heavy content; that is what it is for.

1. Rupture — on the priority target
2. Blood Arc — for the buff
3. **Grim Carve** — your primary AoE button
4. Reaver's Edge — at 4+ targets
5. Heart Splitter
6. Reaver's Edge
7. Double Strike

### Slaughter, revisited

Slaughter is an **AoE** button, and even there it is conditional:

- **Do not hold it long.** In AoE you rarely want to sit on Slaughter more than a few seconds,
  whereas on a single target you can bank it up to ten.
- **At 2+ targets, only Slaughter when the target will die from it, or when you are about to swap.**
  Otherwise you are stripping the Rend that Oathshatter and Exsanguinate are milking.

This is the cleanest way to hold the whole thing in your head: **Rend is a bank account. Heart
Splitter lives off the interest. Slaughter closes the account.** In a pull you close it because you
are moving on; on a boss you never do.

## Focus Next

| You are in | Focus on |
|---|---|
| **Contender** | Item level. Run Grim Carve. Learn Rend stacking before you worry about conversion timing. |
| **Adept** | ~180 ilvl. Ruby and Diamond gems first. Keep Spirit at 10-15% unless you are committing to Bloodcraze. |
| **Champion** | Weapon traits. Farm capstone sets. **Decide your build now** — the three stat priorities diverge sharply and you cannot hedge. |
| **Paragon** | Lock in Seal of the Heskyr. Get The Beetle on the necklace. Begin the pivot from Ruby-first to Emerald-first gems. |
| **Eternal** | Emerald to node 10, then Amethyst 6 / Sapphire 6 / Ruby 6. Itemise strictly to your chosen build's stat line. |
