# Stormwatch — Adventure (1 boss)

**Boss:** Warlord Brogg · **Length:** 10-15 min · **Difficulty:** B — forgiving until the last fight

**Drops:** Death's Grasp (DPS), Sin Warding (all)

A coastal village against pillagers and bandits. The trash is generous; **Warlord Brogg is the whole
difficulty of the dungeon**, and the developers may yet tune his damage down.

## Route

Trash, then a **partial Warlord Brogg fight down to 80%** in order to cross a bridge, then more trash,
then the real encounter. The 80% phase is a rehearsal — use it to check interrupt assignments.

## Trash that kills casual groups

| Mob | What it does | What to do |
|---|---|---|
| **Executioner** | **CC-immune.** Damage **scales with your missing health**. Cleaves, stacking a 5% damage vulnerability. | **Tank faces away from the group.** Top players off — being low is what kills you here. |
| **Bully Basher** | **CC-immune.** **Together Stronk!** gives nearby mobs 20% DR. *(Adept+)* | Interrupt Together Stronk! |
| **Stormscreamer** | **Crackling Bolt** and **Ball Lightning**; **Sky Zapper** added at Adept+ | Interrupt Ball Lightning first |
| **Profane Invoker** | **Shadow Bolt**; **Wither** added at Adept+ | Interrupt |
| **Ashen Arsonist** | **Flame Blast**; **Big Oogha Flame** added at Adept+ | Interrupt; stay out of the cone |

**Interrupt priority:** Together Stronk! (Bully Basher) > Ball Lightning (Stormscreamer) >
Shadow Bolt (Profane Invoker) > Flame Blast (Ashen Arsonist).

## Boss: Warlord Brogg

### The kick trap

Brogg has **two interruptible casts, and they are not equally worth kicking**:

| Cast | Recast | Worth a kick? |
|---|---|---|
| **Charged Bolt** | **effectively none** | **No.** High damage to one random player. It comes back immediately, so every kick you spend here is a kick you do not have twenty seconds later |
| **Dread Arc** | **20s** | **Yes, every time.** 3s cast, then high damage to a random player **chaining to the rest of the party** |

**Why this differs from [Wyrmheart](wyrmheart.md).** There, Icy Death recasts every 12 seconds, which
a two-person rotation on 20-second cooldowns can genuinely cover. Charged Bolt has **no meaningful
recast at all** — it simply returns. No rotation covers it, so every kick spent on it is a Dread Arc
kick thrown away.

**Bank at least two kicks for Dread Arc and let Charged Bolt through.** The healer covers Charged
Bolt with throughput; nobody covers a chained Dread Arc.

### Bridge phase (down to 80%)

A rehearsal with a reduced kit. Use it to confirm your Dread Arc assignments before the real pull.

### Final phase

| Ability | Recast | Interruptible | What happens | What to do |
|---|---|---|---|---|
| **Charged Bolt** | ~0s | **Yes** | High damage to a random party member | **Let it through.** See the kick trap above |
| **Dread Arc** | **20s** | **Yes** | 3s cast, then high damage chaining across the party | **Never miss it.** Two assigned kickers, in order |
| **Perfect Storm** | 32s | No | 3s channel, then massive damage to everyone **nearby** | Get clear. Lethal while Mancatchers are up |
| **Lightning Rod** *(Vayr's Legacy — Adept+)* | 38s | No | AoE on a random player dealing continuous damage **divided among all players** | **Stack in it deliberately.** Splitting is the mechanic; spreading is what kills you |
| **Raiders** | **70s** | No | Summons **2 Mancatchers** | Cleave them down before the next Perfect Storm |
| **Storm's Conduit** | passive | No | Constant periodic lightning damage, jolting nearby heroes | The healer plans around a permanent drain — this caps how long the fight can run |

### Why it gets ugly around the one-minute mark

Dread Arc is on 20s and Perfect Storm on 32s, so they collide every 160 seconds. Raiders lands every
70s. The dangerous window is **Perfect Storm arriving while Mancatchers are alive and Dread Arc is
due** — that is the wipe, and it is on a fixed schedule rather than a random one. Save a group
defensive for it rather than spending cooldowns early.

### The three things to get right
1. **Never miss Dread Arc, and never kick Charged Bolt.** Assign two people to Dread Arc so a missed
   interrupt has a backup.
2. **Kill Mancatchers fast** — they are what makes Perfect Storm lethal.
3. **Stack for Lightning Rod.** The damage is split between everyone standing in it.

> **Source gap:** earlier notes here listed a bridge-phase cast called *Forked Lightning*. It does
> not appear in current Icy Veins or Method ability listings for Brogg. Treat it as unverified.
