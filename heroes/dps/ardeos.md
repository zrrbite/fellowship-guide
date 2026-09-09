# Ardeos — Pyromancer (DPS)

**Identity:** Cinders convert into Burning Embers. Ardeos is a damage-over-time specialist built
around detonation and DoT acceleration, with Fire Frogs as a scaling AoE layer.

**Interrupt: Scorch.** All interrupts lock the target out of casting for **4 seconds**, except against dedicated boss timers. Plan on a **~20s cooldown**; see [interrupts.md](../../docs/interrupts.md).

## Stat priority

1. **Item level / Intellect**
2. **Haste** — lowers some cooldowns and GCDs, shortens casts, **and boosts DoT tick rates**
3. **Crit** — doubles ability damage and increases Fire Frog spawn rates
4. **Expertise** — a straightforward damage increase
5. **Spirit** — least valuable; refunds Cinders on Detonate but scales poorly here

> Haste is doubly valuable on Ardeos because it accelerates DoT ticks as well as your casts. It is
> not a generic filler stat for him.

## Talent build — Fire Ball (recommended starter)

| Tier | Talents |
|---|---|
| 2 | Slow Burn (2), Frog Squad (2) |
| 3 | Great Balls of Fire (2) |
| 4 | Backdraft (1), Flare Up (1), Apocalyptic Surge (1) |
| 5 | Agonizing Blaze (2) |
| 6 | Firestarter (2) |
| 7 | Undying Flame (2) |
| 8+ (1 pt each) | Cascading Inferno, Crash and Burn, Crackling Inferno, Rolling Flames, Pyrophibian Frenzy, Reign of Fire, Burning Initiative, Intensifying Inferno, Spontaneous Combustion |

**Progression path:**
1. Start with the Fire Ball talents for early-league viability.
2. On acquiring **Ring of Boomtastic Explosions**, swap **Backdraft** for **Cascading Inferno** or
   **Burning Initiative**.
3. Later, pick up **Rolling Flames** for extra funnel and single-target damage.

### Variants

| Build | Legendary | Use case |
|---|---|---|
| **Fire Frogs** | Exquisite Flaming Toad Cloak | Late-game AoE. In Season 3, Pyrophibian Frenzy triggers on **all** damage-over-time damage instances, which is what makes this build work. |
| **Engulfing Flames** | Draconic Bracers of the Devouring Flame | Pure single-target and priority damage. Requires supporting AoE talents to stay dungeon-viable. |

## Traits

**Major Traits (gear, 35-point budget)**
- **4/4 Visions of Grandeur** — the core damage multiplier
- 1/4 Brave Machinations
- 1/4 Martial Initiative
- Additional ranks in Amethyst Splinters and Emerald Judgement when budget allows

**Heroic Traits:** Seized Opportunity and Hunter's Focus, for the Crit and Haste bonuses

**Defensive Traits (weapon, 5-point budget):** King of the Hill and Heart of Stone; scale up at
higher difficulties

**Blessings**
- **S:** The Wayfarer — the high-uptime Haste buff
- **A:** The Sinister — note it does **not** affect Pyrophibian Frenzy Fire Frogs
- **Emerging:** The Vainglorious and The Vehement, which empower Infernal Wave

**Necklace Attunements**
- **S:** The Beetle, The Lake — 20% area damage reduction is substantial
- **A:** The Shadow, The Mountain
- **Avoid:** The Oak, which is tank-focused

## Gems

**Priority:** Sapphire > Amethyst > Emerald > Ruby > Topaz > Diamond

**Endgame target (with Seal of the Heskyr):** **10 Sapphire, 6 Emerald, 6 Amethyst**, then Ruby,
Topaz and Diamond as secondary fills.

**Sockets:** 4 guaranteed on Epic Rings, Cloak and Wrists.

## Gear

- **Sets:** Seal of the Heskyr + Death's Grasp. Dark Prophecy is a strong alternative given how
  well Ardeos scales with Haste.
- **Legendaries:** Ring of Boomtastic Explosions (general), Exquisite Flaming Toad Cloak (Frogs),
  Draconic Bracers of the Devouring Flame (single target).

## Single-target damage

**"It's all Detonate, always has been."** Detonate is the entire point of the hero; Searing Blaze,
Engulfing Flames, Fire Ball and Infernal Wave exist to fund it.

**How the engine works:** you accumulate **Cinders** through casts, and at **100 Cinders** you gain an
**Ember** to spend on Detonate. **Detonate's damage scales with your active DoTs — the more you have
applied, the harder it hits.**

### The misconception that costs the most damage

**Detonate does not consume your DoTs.** Players hold Detonate back to "preserve" their DoTs, or
re-apply everything after each cast. Neither is necessary. Keep DoT uptime high and spend Embers
freely.

**Rotation:**

1. Fire Frogs
2. Apocalypse
3. Fire Ball
4. Engulfing Flames ×2
5. Pyromania
6. Wildfire
7. **Detonate spam**

Between burn windows, refresh expiring **Searing Blaze** debuffs and spam **Infernal Wave** to
generate.

**Single target versus AoE:** the rotation barely changes — the real difference is *when* you time
your burn windows. In AoE you generate far more resource, so watch for **overcapping Embers**; on a
boss that pressure disappears and burn-window placement becomes the only lever.

## AoE damage

**The rotation barely changes.** Ardeos is unusual in this: the same burn-window sequence applies, and
the real difference is resource pressure rather than button order.

**Fire Ball is the only DoT that generates Cinders per tick.** On multiple targets those ticks
multiply, which makes Fire Ball disproportionately valuable in AoE and is the whole reason your
generation accelerates.

**So the AoE discipline is about not wasting the surplus:**

- **Watch for overcapping Embers.** You will generate far more than on a boss, and a capped Ember is
  simply lost damage.
- **Infernal Wave** remains your only spammable Cinder generator between Wildfire windows.
- Burn-window *timing* — not rotation — is the lever that separates good Ardeos play from average.

## Focus Next

| You are in | Focus on |
|---|---|
| **Contender** | Item level. Run the Fire Ball build and learn DoT-then-detonate sequencing. |
| **Adept** | ~180 ilvl. Get **Visions of Grandeur to 4/4** — it is your largest single multiplier. Start Sapphire gems. |
| **Champion** | Weapon traits: King of the Hill. Farm capstone sets. Build Haste for DoT tick rate. |
| **Paragon** | Your Legendary picks your build: Ring → Fire Ball, Cloak → Frogs, Bracers → Engulfing Flames. Lock in Seal of the Heskyr. |
| **Eternal** | Sapphire to node 10, then Emerald 6 and Amethyst 6. Consider Dark Prophecy as your second set. |
