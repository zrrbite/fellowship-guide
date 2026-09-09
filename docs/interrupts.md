# Interrupt and CC Cheat Sheet

One page. The single highest-leverage document here for a casual group, because missed interrupts
cause more wipes than bad gear ever will.

## How interrupts actually work

Four facts that govern every assignment on this page:

1. **Only Tanks and DPS have an Interrupt.** Healers do not. A standard party therefore has
   **three interrupts, not four** — tank plus two DPS.
2. **The cooldown is about 20 seconds** (Elarion's Disrupt and Rime's are both 20s). Some melee
   heroes are reported to have shorter ones; treat 20s as the planning number.
3. **A successful interrupt locks the target out of casting for 4 seconds** — *except against
   dedicated boss timers*. Kicking a boss does **not** delay its next cast. Boss cadences are fixed,
   so you cannot buy time by kicking early.
4. **Use the Interrupt Tracker.** Default key **V**. It marks the enemy you are targeting with your
   kick and shows your allies whether yours is ready. This is the tool that makes everything below
   work without anyone talking over each other.

## How to use this

**Assign targets before the pull.** "I have the caster on the left, you have the one on the right"
takes three seconds and prevents the two most common failures: everyone interrupting the same cast,
and nobody interrupting anything.

## The universal priorities

Regardless of dungeon, interrupt in this order:

1. **Anything that heals a mob** — Restore Vitality, Invigorate, Healing Waters, Unholy Restoration.
   Nothing wastes a casual group's time like a mob healing to full.
2. **Anything that buffs a whole pack** — Together Stronk! (20% DR), Greed's Embrace (80% damage
   reduction), Blood Scent, Frenzy. These turn a routine pull into a slog.
3. **Channelled group damage** — Sanguine Maelstrom, Mindrender Barrage, Dread Arc, Shadowgreed
   Eclipse, Hungering Vessels. These kill people.
4. **Casts targeting the tank** — Mossfire Bolt, Pain Bolt, Frostbitten Strength, Venom Bolt.
5. **Everything else.**

## Banking: the rule that actually wins boss fights

**An interrupt spent is an interrupt you do not have.** Several bosses pair a *cheap, frequent,
interruptible* cast with an *expensive, slow, interruptible* one. The failure is not that you lack
kicks overall — it is that all of them can be on cooldown at the one moment that matters.

**The fix is a rotation with one player held in reserve, not abstinence.** With three interrupts at
20 seconds, holding one back costs you very little and guarantees the expensive cast is covered.

### Do the arithmetic before you decide to skip a cast

Work in one cycle of the expensive cast, and compare supply against demand:

- **Supply** = 3 interrupters × (cycle length ÷ 20s cooldown)
- **Demand** = 1 expensive cast + (cycle length ÷ cheap cast recast)

| Boss | Cycle | Supply | Demand | Verdict |
|---|---|---|---|---|
| Apostate Veras ([Wyrmheart](../dungeons/wyrmheart.md)) | Frigid Mists, 33s | ~4.95 kicks | 1 + 2.75 Icy Death = ~3.75 | **Kick both.** Two rotate Icy Death, one banks Mists |
| Warlord Brogg ([Stormwatch](../dungeons/stormwatch.md)) | Dread Arc, 20s | ~3 kicks | 1 + *continuous* Charged Bolt | **Let Charged Bolt go.** Its recast is effectively zero, so no rotation can cover it |

The two cases genuinely differ. Icy Death at 12s is coverable by a two-person rotation — two kicks
on 20s cooldowns produce one every 10 seconds on average, comfortably inside a 12-second cast. Charged
Bolt is not coverable by anything, so kicking it is pure waste of a Dread Arc kick.

## Interruptible boss casts — the complete list

Most bosses in this game cannot be interrupted at all. Knowing which ones can is worth more than any
rotation, because it tells you when to stop holding a kick you will never use.

| Dungeon | Boss | Interruptible cast | Kick it? |
|---|---|---|---|
| Wyrmheart | Apostate Veras | Frigid Mists | **Always** — every miss permanently shrinks the arena |
| Wyrmheart | Apostate Veras | Icy Death | Yes — but only the **two** players not banking for Mists |
| Stormwatch | Warlord Brogg | Dread Arc | **Always** — it chains across the party |
| Stormwatch | Warlord Brogg | Charged Bolt | No — its recast is effectively zero, so no rotation covers it |
| Urrak Markets | Slavetrader Brull | Wild Bolt | **Freely** — it is the only kickable cast in the encounter |
| Scryer's Peak | Overlord Varux | Fatalistic Ritual | **Always** — break the shield first |
| Wraithtide Vault | Bael'Aurum | Shadowgreed Eclipse | **Always** — 8s of party-wide damage |
| Wraithtide Vault | Bael'Aurum | Hoard | Yes, if treasure piles are still up — it heals him per pile |
| Wraithtide Vault | Deathless Katrine | Quick Draw | Yes |
| Heart of Tuzari | Moar'Gore | Sacrificial Pyre | **No — deliberately.** The flames clear Tainted Blood stacks |
| Xul | Vel'korath | Tormenting Visions | Yes |
| Xul | Vel'korath | Sinister Vessels | Yes |
| Xul | Vel'korath | Hungering Vessels | **Always** — party-wide channel |

**Every other boss in the game has no interruptible cast at all.** That includes Sin-Magir, Malgut
the Fetid, Sinthara, Xurath, the Godfall Titan, and all three bosses of both Cithrel's Fall and
Ransack of Drakheim. In those fights your kicks are for the trash on the way in, and holding one
"for the boss" is wasted.

## Things that look interruptible and are not

Pressing a kick at these does nothing. Each has a different answer.

| Cast | Where | The actual answer |
|---|---|---|
| **Godrot Eclipse** | Malgut, Everdawn Grove | **Akari's charge stun.** You have 7.5 seconds |
| **Furious Tantrum** | Gorestained Butcher; Drazhul | Group healing cooldowns. There is no interrupt |
| **Creeping Decay** | Brull, Urrak Markets | Tank mitigation |
| **Glacial Spikes** | Apostate Veras | Move in a tight arc; it knocks you up |
| **Ruinous Starfall** | Sin-Magir | Destroy the orbs — the cast itself is unstunnable |
| **Soulpiercer** | Dunesnare Hunter, Empyrean Sands | **Dispel**, not interrupt |
| **Skittershard death DoT** | Everdawn Grove | Dispel; a Mass Dispel relic if you pull several |

## Mobs that are immune to CC

Pressing CC on these does nothing. Plan around them, tank them, or kill them.

| Mob | Dungeon | What it does |
|---|---|---|
| Gravebreaker Brute | Empyrean Sands | Splash damage within 4 yards of the tank |
| Nightbound Magi | Empyrean Sands | Constellation of Ruin — everyone spreads and soaks a circle |
| Water Elemental | Sailor's Abyss | Heals mobs; stack in melee to deny Hydrobolt |
| Deepbound Magi | Sailor's Abyss | Shadow Eruption AoE and damage amp |
| Hollowed Corsair | Sailor's Abyss | Cleaving melee with stacking bleed — face away from group |
| Bully Basher | Silken Hollow, Stormwatch | Together Stronk! gives nearby mobs 20% DR |
| Greater Ice Elemental | Wyrmheart | Burrowed Strike — stack to split; avoid the Avalanche frontal |
| Executioner | Stormwatch, Heart of Tuzari | Damage scales with your missing health; cleaves — face away |
| Enforcer | Godfall Quarry | Armor reduction; Reflective Shield — move away, do not hit it |
| Enraged Earth Elemental | Godfall Quarry | Shatter stacks damage amplification |
| Bloodstone Goliath | Everdawn Grove | Coalescing Bloodstone stacks — use defensives |
| Gorestained Butcher | Urrak Markets | Furious Tantrum, heavy group damage |
| Icebite Reaver | Ransack of Drakheim | Creeping Frostbite, +5% damage taken per stack |
| Shadow of Ulmorgat | Ransack of Drakheim | Focus the Fiend whose symbol does not match the totems |
| Spellbound Golem | Cithrel's Fall | Splits into three Ice Shardlings on death |
| Barbarous Lasher | Heart of Tuzari | Reflects 25% of damage taken back at you |
| Hulking Bulgore | Heart of Tuzari | Charges when kited; enrages at 50% |

## Interrupt targets by dungeon

### Empyrean Sands
- **Greedspawn Sentinel** — Greed's Embrace: stacking DoT plus haste to nearby mobs, and **80% damage reduction**. Top priority.
- **Water Elemental** — Healing Waters, Hydrobolt
- **Acolyte of Sinnari** — Sinnari's Wrath (3s cast)
- **Nightbound Magi** — Shadow Bolt
- **Dunesnare Hunter** — Soulpiercer is **dispellable, not interruptible**

### Sailor's Abyss
- **Water Elemental** — Healing Waters
- **Deepbound Magi** — Call of the Abyss (priority), Necrotic Bolt, Shadow Eruption; group-soak Harrowing Solitude
- **Tormented Spectre** — Anguish Unleashed (priority)

### Silken Hollow
- **Bully Basher** — Together Stronk! (20% DR)
- **Gravesnare Kidnapper** — **every** cast of Kidnap
- **Rotheart Recluse** — Heartstopper must be dispelled immediately or it kills
- **Venom Drinker** (Vayr's Legacy) — CC the Poisonado chasing the tank

### Wyrmheart
- **Deceitful Scholar** — Rune of Detonation; kite the Volatile Orbs it spawns
- **Blade of Cithrel** — Slicing Blades; gains 30% haste at low health
- **Eldrin Chronomancer** — Decripify and Temporal Manipulation; dispel Erosion of Time

### Stormwatch
- **Bully Basher** — Together Stronk! *(Adept+)*
- **Stormscreamer** — Ball Lightning, Crackling Bolt; Sky Zapper *(Adept+)*
- **Profane Invoker** — Shadow Bolt; Wither *(Adept+)*
- **Ashen Arsonist** — Flame Blast; Big Oogha Flame *(Adept+)*

### Godfall Quarry
- **Godfall Wardstone** — Searing Beam. Interrupting or CCing makes them **Vulnerable**, so the kick is also a damage buff.
- **Quarry Stalker** — Poisonous Strike, then dispel the poison
- **Nezari Bolter** — Bolt Barrage
- **Arcane Warden** — Psionic Horror

### Everdawn Grove
- **Desecrator** — Volley channel; someone must soak the Infernal Explosive circle
- **Corrupted Totemic** — Shadow Lob (priority) and Restoration (it heals); CC the Corrupted Prayer channel
- **Horned Seer** — Pain Bolt, Orb of Blood; Sanguine Offering *(Adept+, priority)*
- **Skittershard** — cannot be interrupted; dispel the death DoT fast, Mass Dispel relic is ideal

### Urrak Markets
- **Hellcaller** — Restore Vitality (healing)
- **Urrak Slaver** — Barred Chain *(Adept+)*
- **Urrak Witch** — Mossfire Bolt (tank), Grasping Vines, Jungle Rot
- **Horned Seer** — Pain Bolt (tank), Orb of Blood; Sanguine Offering *(Adept+)*

### Scryer's Peak and Ruins of Regath
- **Meandering Acolyte** — Unholy Restoration (healing). Top priority in Ruins of Regath.
- **Heskyr Magus** — Sanguine Maelstrom and Blood Bolt. Dispel the stacking debuff before 10 stacks.
- **Sanguine Echo** — Blood Bolt
- **Sanguine Disciple** — Sanguine Ritual; interrupting weakens the adds it spawns
- **Stalking Grim** — Piercing Howl silences casters; Blood Scent stacks +10% damage, haste and HP

### Xul, the Blood Monolith
- **Heskyr Magus** — Blood Bolt, Sanguine Maelstrom
- **Sanguine Disciple** — Sanguine Ritual
- **Heskyr Zealot** — Frenzy
- **Sanguine Echo** — Shake It Off
- **Heart of Rot** — Consume, Blood Boil *(Nightmare)*

### Cithrel's Fall
- **Eldrin Sentinel** — every cast of Shattering Barrier
- **Deceitful Scholar** — Rune of Detonation, Arcane Strike
- **Corrupter** — Drain Life, Ice Bolt; dispel Freezing Blood **before** it expires

### Heart of Tuzari
- **Hellcaller** — Restore Vitality, Demonic Lash
- **Barbed Roots** — Toxic Spores, which they channel **only if no melee is in range**
- **Ashen Arsonist** — Flame Blast, Big Oogha Flame
- **Profane Invoker** — Shadow Bolt, Wither

### Wraithtide Vault
- **Tide Witch** — Sunken Gale, Dreadwater Bolt. Also spawns from Marrow's Cannonball Troops
- **Soulpowder Buccaneer** — Soulpowder Shot
- **Greedbound Prism** — Mindrender Barrage, heavy group damage
- **Greedspawn Sentinel** — Greed's Embrace (80% damage reduction)
- **Scuttlejack Cannoneer** — Shackle Blast, Blunder Boom
- **Bilgerat** — Vermin Tide, which spawns Gunpowder Rats

### Ransack of Drakheim
- **Ashen Arsonist** — Big Oogha Flame
- **Craven Hiisi** — CC the Bonk Noggin channel
- **Icebite Reaver** — Frostbitten Strength (CC-immune, must be interrupted)
- **Bleakfrost Mystic** — Invigorate (healing)
- **Bleakfrost Slaver** — Barbed Chain; linked players stand together
- **Coldbrine Fiend** — Icy Annihilation, Brine Bolt
- **Nightmist Whisperer** — Blinding Fear; CC or dispel the Silence
