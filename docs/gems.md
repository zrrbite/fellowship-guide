# Gems and Gem Power

The gem system is the primary endgame character growth vector. Every dungeon run feeds it.

## How it works

- Gems slot into **sockets**; each socketed gem contributes **Gem Power** to its colour's track.
- Each colour has a **10-node track**, split into two ranks:
  - **Rank 1** — five basic effects, unlocked at 80 / 150 / 250 / 350 / 450 power (approx.)
  - **Rank 2** — five upgraded effects that *replace* the rank 1 versions, at 600 → 1500 power
  - **Overcap** — beyond 1500, every 2 further points give **+0.01% primary stat, stamina and max health**
- Gem Power bonuses are **flat and not subject to diminishing returns**, unlike secondary stats.

### Shorthand used in this repo

"**Emerald 10**" means *enough Emerald gem power to reach node 10 of the Emerald track* — roughly
1500 power. "**Sapphire 6**" means node 6, roughly 600 power (the rank 2 entry node).

## Sockets — where power comes from

| Source | Amount |
|---|---|
| Epic (Purple) Cloak | 1 socket |
| Epic (Purple) Wrists | 1 socket |
| Epic (Purple) Rings ×2 | 2 sockets |
| **Total guaranteed** | **4 sockets** |
| Legendary item | adds a 4th socket to that slot's slot pool |
| **Imbued Essence modifier** | **+100 Gem Power, no socket needed**, stacks to +200 |
| **Seal of the Heskyr (2pc)** | **+25% Gem Power** on everything above |

**The Heskyr multiplier is the whole game.** With it, a Flawless gem yields **625** power instead of
500, and a +100 Imbued Essence modifier yields **125**. That is what makes a focused rank-10
single-colour build reachable at all.

Note: **5 gem imbues of a given colour are interchangeable with the gems themselves** — useful
flexibility when farming a specific colour is going badly.

## The six colours

| Colour | Theme | Notable nodes |
|---|---|---|
| **Ruby** (Red) | Primary stat, stamina, boss damage | *Might of the Minotaur* (primary stat), *Essence of the Conqueror* — 5–15% damage/healing/absorb during boss encounters, *Titan's Blood*, *Champion's Heart*, *Unyielding Vitality* |
| **Amethyst** (Purple) | Critical strike scaling | *Sealed Fate* (crit chance, ~15% at rank II), crit damage multipliers, bonus crit vs. full-health targets |
| **Topaz** (Yellow) | Haste | Passive haste, temporary haste vs. low-health enemies, *Rogue's Resurgence* (strong defensive), *Adrenaline Rush*, emergency heal at 50% health |
| **Emerald** (Green) | Expertise and cooldown reduction | *Essence of the Commander* — **4–12% ability cooldown reduction**, *First Strike*, *Tactician's Acumen*, *Sentinel's Bastion*, *Vanguard's Resolve* |
| **Sapphire** (Blue) | Spirit Ability mechanics | *Blessing of the Prophet*, *Ancestral Surge*, max spirit points, primary stat scaling during Spirit Ability, Spirit cost reduction, *Resonating Soul* (defensive), *Oracle's Foresight*, *Mystic's Intuition* |
| **Diamond** (White) | Versatility | Armor, primary stats, relic cooldown reduction, *Harmonious Soul* — stacking secondary stats per enemy defeated |

Diamond is generally the weakest track for most heroes and is usually only worth taking to node 3
to fill an otherwise dead slot.

## Acquisition

- **Small gems** drop from **Contender 4 and beyond**.
- **Combine three gems** of matching colour and tier to upgrade to the next tier.
- **The Jeweler** performs transmutations using **Aethers** to convert colour.
- **Master Craftsman Braggi** converts account-wide resources into small gems for alts.

## Strategy: rainbow first, focus later

**Early / mid game — go rainbow.** Spread gems across colours. Four different node-3-to-6 effects
beat one node-6 effect, because each track's early nodes are disproportionately cheap.

**Endgame — go focused.** Once Seal of the Heskyr is equipped and Imbued Essence modifiers are
stacked, collapse into your hero's priority colour to reach rank 10 (1500 power) on the one track
that multiplies your kit hardest.

## Per-hero gem targets at a glance

| Hero | Role | Priority order | Endgame target |
|---|---|---|---|
| Helena | Tank | Emerald > Sapphire > Diamond > Amethyst > Topaz > Ruby | **10 Emerald + 10 Sapphire** (needs ~400 extra power from modifiers) |
| Meiko | Tank | Emerald > Sapphire > Amethyst > Ruby > Diamond > Topaz | **10 Emerald, 6 Sapphire, 6 Amethyst** |
| Xavian | Tank | Amethyst > Sapphire > Emerald > Diamond > Ruby > Topaz | **10 Amethyst, 6 Sapphire, 6 Emerald** |
| Aeona | Healer | Ruby > Amethyst > Topaz > Emerald > Sapphire > Diamond | **6 Ruby, 6 Amethyst, 6 Topaz, 10 Emerald** |
| Sylvie | Healer | Ruby > Emerald > Sapphire > Amethyst/Topaz | **10 Emerald + 10 Sapphire**, remainder into Amethyst/Topaz/Ruby |
| Vigour | Healer | Sapphire > Topaz > Emerald > Ruby | **10 Sapphire, 6 Topaz, 6 Emerald, 6 Ruby** |
| Ardeos | DPS | Sapphire > Amethyst > Emerald > Ruby > Topaz > Diamond | **10 Sapphire, 6 Emerald, 6 Amethyst** |
| Elarion | DPS | Sapphire > Topaz > Ruby > Amethyst/Emerald | **Sapphire to node 10** (Blessing of the Prophet II) + Ruby/Topaz/flex |
| Gunde | DPS | early: Ruby > Diamond > Emerald > Sapphire > Amethyst > Topaz | **10 Emerald, 6 Amethyst, 6 Sapphire, 6 Ruby** |
| Mara | DPS | early: Ruby > Diamond > Sapphire > Emerald > Amethyst > Topaz | **10 Sapphire, 6 Amethyst, 6 Emerald, 6 Ruby** |
| Rime | DPS | Sapphire > Emerald > Amethyst = Ruby = Topaz > Diamond | **4× node 6 "rainbow"**: Sapphire 6, Emerald 6, Amethyst 6, Ruby *or* Topaz 6 |
| Tariq | DPS | Sapphire > Amethyst > Ruby > Topaz/Emerald | **Sapphire 6, Amethyst 6, Ruby 6, Topaz/Emerald 6** — or rank 10 in one colour with Heskyr |

Rime and Tariq are the two heroes that genuinely prefer the rainbow shape at endgame rather than
collapsing to a single track.
