# Sources and Verification

All data in this repository was gathered on **2026-09-05** and reflects
**Fellowship Early Access Season 3 — "Rise of the Heskyr"** (launched 2026-06-22).

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
- **Vel'korath**, the third Xul boss, has little public mechanical detail. The page says so.

## Re-verifying after a patch

Fellowship is in Early Access and balance shifts between and within seasons. When a patch lands:

1. Check the Method hero page for the affected hero — stat priority and talent tables are the
   first things to change.
2. Check the Icy Veins gems and set bonus guides — these change less often but change dramatically
   when they do (Seal of the Heskyr was a Season 3 addition that reshaped every build in this repo).
3. Season boundaries reset player and hero progression. Cosmetics and mounts carry over; Trims reset.
