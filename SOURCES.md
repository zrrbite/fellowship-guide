# Sources and Verification

All data in this repository was gathered on **2026-09-05** and reflects
**Fellowship Early Access Season 3 — "Rise of the Heskyr"** (launched 2026-06-22).

**Boss ability audit, 2026-09-09.** Every dungeon page was re-checked against source ability
listings. This added recast timings and interruptible flags where published, corrected several
ability names, and closed the Vel'korath gap. See *Audit findings* below.

## Primary sources

| Source | Used for |
|---|---|
| [Method — Fellowship hero guides](https://www.method.gg/fellowship) | Per-hero stat priorities, talent builds, traits, blessings, necklace rankings, gem targets. This is the backbone of every hero page. |
| [Method — Full Gearing Guide, Contender to Eternal](https://www.method.gg/fellowship/fellowship-full-gearing-guide-from-contender-to-eternal) | Item level targets per league, gearing order, alt catch-up strategy |
| [Icy Veins — Gems Guide, EA Season 3](https://www.icy-veins.com/fellowship/news/gems-guide/) | Gem colours, track structure, node names, socket sources, Imbued Essence |
| [Icy Veins — Set Bonus Guide](https://www.icy-veins.com/fellowship/news/set-bonuses/) | The complete set table with bonuses and drop sources |
| [Icy Veins — Beginner Guide, EA Season 3](https://www.icy-veins.com/fellowship/news/fellowship-beginner-guide-everything-you-need-to-know/) | Talent point count, trait categories, blessings, relics, league structure |
| [Fellowship Wiki (Fextralife) — Classes](https://fellowship.wiki.fextralife.com/Classes) | Hero identities, class titles, resource systems |
| [Overgear — Rise of the Heskyr (Season 3 overview)](https://overgear.com/guides/fellowship/rise-of-the-heskyr/) | Season 3 changes: Gunde, new dungeons, True Sight affix, league simplification |
| [Overgear — Gems Guide](https://overgear.com/guides/fellowship/gems-guide/) | Cross-check on gem effects |
| [Fellowship on Steam](https://store.steampowered.com/app/2352620/Fellowship/) | Game identification and Early Access status |
| [Method — Dungeon guides](https://www.method.gg/fellowship/dungeons) | Per-dungeon routes, trash abilities, boss mechanics for all 15 dungeon pages |
| [Method — Route Planner](https://www.method.gg/fellowship/route-planner) | Routing tool; pre-built routes per dungeon and difficulty |
| [Method — Dungeons Tier List by Difficulty](https://www.method.gg/fellowship/fellowship-dungeons-tier-list-by-difficulty) | Adventure difficulty rankings |
| [Method — Dungeon Routes: How To Use Them](https://www.method.gg/fellowship/fellowship-dungeon-routes-how-to-use-them-and-create-your-own) | Kill Score, pull planning, relic usage, common mistakes |
| [Method — Upgrade, Scrap and Reforge](https://www.method.gg/fellowship/how-to-upgrade-reforge-scrap-your-gear-in-fellowship) | Scrapper, Blacksmith, three reforge tiers, materials |
| [Method — Gems: How They Work and How to Get Them](https://www.method.gg/fellowship/gems-in-fellowship-how-they-work-how-to-get-them-all-gem-powers) | Gem tiers, fusion ratios, transmutation, budding, acquisition strategy |
| [Icy Veins — Pinnacle Dungeon Rewards](https://www.icy-veins.com/fellowship/news/fellowship-pinnacle-dungeon-rewards-guide/) | Xul unlock, difficulties, Bloodstones, weekly reward structure |
| [Fellowship Wiki — Dungeons](https://fellowship.wiki.fextralife.com/Dungeons) | Dungeon directory, bosses, run lengths |
| [Fellowship Wiki — Crafter, Scrapper & Blacksmith](https://fellowship.wiki.fextralife.com/Crafter,+Scrapper+&+Blacksmith) | Crafting NPCs (older terminology; see conflicts) |
| [Overgear — Dungeon Tier List](https://overgear.com/guides/fellowship/dungeon-tier-list/) | Farming value rankings (conflicts with Method on difficulty) |
| [Boostmatch — Xul Nightmare Guide](https://boostmatch.gg/blog/fellowship/articles/xul-blood-monolith-nightmare-guide) | Pinnacle boss mechanics |
| [Icy Veins — Wyrmheart Dungeon Guide](https://www.icy-veins.com/fellowship/news/wyrmheart-dungeon-guide/) | Apostate Veras recast timings and interrupt flags |
| [Icy Veins — Empyrean Sands Dungeon Guide](https://www.icy-veins.com/fellowship/news/empyrean-sands-dungeon-guide/) | Sin-Magir recast timings; Adept+ gating |
| [Icy Veins — Everdawn Grove Dungeon Guide](https://www.icy-veins.com/fellowship/news/everdawn-grove-dungeon-guide/) | Malgut recast timings; Adept+ gating |
| [Icy Veins — Stormwatch Dungeon Guide](https://www.icy-veins.com/fellowship/news/stormwatch-dungeon-guide/) | Warlord Brogg recast timings; trash Adept+ casts |
| [Icy Veins — Urrak Markets Dungeon Guide](https://www.icy-veins.com/fellowship/news/urrak-markets-dungeon-guide/) | Brull and Drazhul recast timings |
| [Icy Veins — Sailor's Abyss Dungeon Guide](https://www.icy-veins.com/fellowship/news/sailors-abyss-dungeon-guide/) | Sinthara recast timings; line-of-sight mechanic |
| [Icy Veins — Dungeon Curses Guide](https://www.icy-veins.com/fellowship/news/dungeon-curses/) | All curses, their bonuses, and league gating — [`docs/curses.md`](docs/curses.md) |
| [Fextralife — Apostate Veras](https://fellowship.wiki.fextralife.com/Apostate+Veras) | Cross-check on Wyrmheart boss naming |
| [Fextralife — Disrupt](https://fellowship.wiki.fextralife.com/Disrupt) | Interrupt cooldown (20s), range (30 yd), 4s cast lockout |
| [Fextralife — Skills](https://fellowship.wiki.fextralife.com/Skills) | Interrupt ability names per hero; confirmation that healers have none |
| [Method — hero Playstyle & Rotation pages](https://www.method.gg/fellowship/heroes) | Single-target and AoE priority lists, target-count breakpoints, resource mechanics for all 12 heroes |
| [Method — hero database](https://www.method.gg/fellowship/database/heroes) | Ability names and effects (Gunde's Jawbreaker, Warbound, Butcher's Hook) |

## Audit findings, 2026-09-09

**Resolved:**

- **Vayr's Legacy is the Adept+ ability.** Previously described only as "affix-gated additions at
  higher difficulty". Cross-checking five dungeons showed that every mechanic tagged Vayr's Legacy
  here is exactly the one sources tag *Adept+ only*. Documented in
  [`docs/dungeons.md`](docs/dungeons.md). **Consequence: every such mechanic is permanently live for
  a Champion group.**
- **Vel'korath**, previously listed as having "little public mechanical detail", now has a full
  ability list from the Method dungeon guide, including three interruptible casts.
- **Sin-Magir and Malgut share an identical recast skeleton** — 18.5 / 23 / 28 / 30 / 60 seconds,
  with the 18.5s slot being the Vayr's Legacy addition in both.

**Corrected:**

| Was | Is | Where |
|---|---|---|
| *Creeping Death* | **Creeping Decay**, and it is **not** interruptible | Urrak Markets |
| *Celestial Burst* as a cast | **Darkstar Ruin**; Celestial Bursts are what it summons | Empyrean Sands |
| *Sinnari's Judgment* | **Lunar Beam** | Empyrean Sands |
| *Bloodstone Totems* | **Summon Totems** | Everdawn Grove |
| *Bloodmarked / Crimson Assault* | **Bloodmarked Assault** and **Crimson Crucifix** — two separate casts | Scryer's Peak |
| *Barched Chain* | **Barbed Chain** | Ransack of Drakheim |
| *waystones* | **Wardstones** | Godfall Quarry |
| Godrot Eclipse listed as an interrupt target | **Not interruptible** — stopped by Akari's charge stun | `docs/interrupts.md` |
| Furious Tantrum listed as an interrupt target | **Not interruptible** | `docs/interrupts.md` |
| Shadowgreed Eclipse described as a damage check | **Interruptible** | Wraithtide Vault |
| Deafening Screech described as a cast-timing check | **Line-of-sight** — block with the mast | Sailor's Abyss |
| Unholy Hymn as always three stages | **Three at 80/60/40 with Vayr's Legacy; two at 66/33 without** | Ruins of Regath |

**Interrupt mechanics, added 2026-09-09.** The repo previously documented *what* to interrupt across
15 dungeons without ever documenting *how interrupts work*. Now in
[`docs/interrupts.md`](docs/interrupts.md): **only Tanks and DPS have an Interrupt**, so a party has
**three**, not four; the cooldown is **~20s**; a successful interrupt locks a target out for **4
seconds except against dedicated boss timers**, meaning kicking a boss never delays its next cast;
and the **Interrupt Tracker (default V)** broadcasts your kick target and readiness to the party.

This corrected the Wyrmheart advice. An earlier revision of that page claimed Icy Death (12s) and
Frigid Mists (33s) "cannot share a kicker" and told groups to eat Icy Death. That was wrong: three
interrupters on 20s cooldowns supply ~4.95 kicks per 33s cycle against ~3.75 demanded. The correct
assignment is **two players rotating Icy Death while a third banks for Frigid Mists**, which covers
both. The Stormwatch verdict was unaffected — Charged Bolt has no meaningful recast, so no rotation
can cover it — but its reasoning was rewritten to say so.

**Newly documented:** Icy Death (Wyrmheart), Arcane Volley and Actuate Ambush (Cithrel's Fall),
Anchor Strike and Temptation and Thwart the Mutiny (Wraithtide Vault), Hemorrhaging Strike and the
Barbed Roots 40% damage link (Heart of Tuzari), Frigid Presence and Darkness Falls (Ransack of
Drakheim), Magic Missiles and Vaerith Vorn's role (Godfall Quarry), Devour (Silken Hollow), and the
full Han-Eth and Vel'korath kits (Xul).

## Known gaps and conflicts

- **Xavian's class title** is not confirmed in the sources consulted. The Fextralife Classes page
  predates his addition. He is described here by archetype only.
- **League difficulty ranges** conflict between sources: the Icy Veins beginner guide describes
  +1 to +4 per league, while the Season 3 overview states leagues were simplified to **3
  difficulty levels each**, down from 6. The Season 3 figure is the more recent and is used in
  [`docs/progression.md`](docs/progression.md), but treat the exact count as uncertain.
- **Gem node power thresholds** (80/150/250/350/450 for rank 1) are approximate. The 600 and 1500
  figures for rank 2 entry and the overcap node are confirmed.
- **Gunde's blessings** are listed as "all 14 options viable" by the source rather than ranked. No
  narrower recommendation was available.
- **Relic specifics** are thin across all sources. The advice here is deliberately generic.
- **Dungeon difficulty rankings conflict.** Method rates Everdawn Grove B and Urrak Markets C;
  Overgear rates Everdawn Grove, Urrak Markets **and** Ransack of Drakheim all C. Both rankings are
  presented in `docs/dungeons.md` rather than silently merged.
- **Crafting terminology conflicts** between Method (Mithril; Standard/Imbued/Arcane reforging;
  Unstable/Imbued/Arcane Aether) and the Fextralife wiki (Ingots; Shoddy/Serviceable/Intricate
  reforging; Rough/Imbued/Pure Aether). Method's naming is used throughout as the more current. The
  underlying mechanics agree.
- **Gem power absolute values conflict.** Method: Small 120 through Flawless 480, 2,640 to complete a
  colour track. Icy Veins: Flawless 500 (625 with Heskyr), final node at 1,500. Ratios agree;
  absolute numbers do not. Documented in `docs/optimisation.md`.
- **Gem drop threshold** is given as Contender 4 (Icy Veins) or Contender 7 (Method).
- **Several dungeon pages lack an explicit pull order** in the source, which points to the Route
  Planner tool instead. Those pages say so rather than inventing a route.
- **Icy Veins publishes structured recast/interruptible tables for only six dungeons** — Wyrmheart,
  Empyrean Sands, Everdawn Grove, Stormwatch, Urrak Markets and Sailor's Abyss. The other nine pages
  carry ability lists and interrupt flags from Method, which does **not** publish cadences. Those
  pages therefore have no recast column, and none was invented.
- **Stormwatch's *Forked Lightning*** appears in this repo's earlier notes but in no current source
  listing for Warlord Brogg. Flagged on the page as unverified.
- **Hero race/species is not published** by Method, Icy Veins or the Fextralife hero index. Any
  description of a hero as a dwarf, elf and so on cannot be sourced from the guides consulted.
- **Xavian's interrupt name is unconfirmed.** The Fextralife Skills page lists interrupts for Helena
  (Bash), Meiko (Stagger), Rime (Brain Freeze), Ardeos (Scorch), Mara (Kick) and Tariq (Pummel);
  Elarion's Disrupt and Gunde's Jawbreaker come from their own pages. Xavian is confirmed to have one
  without a name being given.
- **Vigour's *Avatar of Light*** is described in this repo as a spirit form but does not appear in the
  Method rotation guide. Flagged on her page as unconfirmed.
- **Mara's Skittering Blades threshold** is given as both *3 or more* and *8 or more* targets within
  the same source, likely reflecting different talent setups. Both are presented on her page.
- **Per-hero interrupt cooldowns are only partly documented.** Only Elarion's and Rime's are confirmed
  (both 20s).
  Only two figures are confirmed (Elarion's Disrupt and Rime's, both 20s), and one secondary source
  claims melee heroes have shorter cooldowns than ranged without giving numbers. **20s is used as the
  planning figure throughout.** If melee kicks are meaningfully shorter, the interrupt arithmetic in
  [`docs/interrupts.md`](docs/interrupts.md) is conservative rather than wrong. Adding an interrupt
  line to each hero page is the highest-value gap left in this repo.
- **Xul'vorith's conduit trade** is reported by Method as deactivating a conduit granting the boss
  **+20% damage**. The direction of that trade is counterintuitive and worth verifying in-game.
- **Godfall Quarry boss count.** Method presents Godfall Titan and Vaerith Vorn under separate
  headings; the Fextralife wiki treats it as a single encounter in which Vaerith Vorn attacks from
  the air and cannot be killed. The single-encounter reading is used.
- **Curse league gating is internally inconsistent in the source.** The Icy Veins curses guide labels
  individual curses as starting at Adept or Champion, then states in summary that only one begins at
  Adept and two at Champion. The per-curse labels are used in [`docs/curses.md`](docs/curses.md).
- **Boss naming for Wyrmheart** varies: *Apostate Veras* in the boss guide, *Magistrate Veras* in the
  Icy Veins dungeon overview text. Apostate Veras is used, matching Fextralife.

## Re-verifying after a patch

Fellowship is in Early Access and balance shifts between and within seasons. When a patch lands:

1. Check the Method hero page for the affected hero — stat priority and talent tables are the
   first things to change.
2. Check the Icy Veins gems and set bonus guides — these change less often but change dramatically
   when they do (Seal of the Heskyr was a Season 3 addition that reshaped every build in this repo).
3. Season boundaries reset player and hero progression. Cosmetics and mounts carry over; Trims reset.
