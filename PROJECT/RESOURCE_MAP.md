# RESOURCE MAP — "A Nascent Light" Remix Project

The repo root is the **Resource Bank** (61 texts). Rule: all chapter prose must be **lifted and edited** from these files. Only write original sentences when the bank lacks the needed beat.

## Primary templates (structure & spine)
| File | Role | Best zones (line refs) |
|---|---|---|
| `A_Gamers_Grand_Journey.txt` | **Spine.** White-room prologue, system UI style, tutorial quest beats. | Ch1 prologue 45–304; Ch2 first-awakening/system-boot 305–660; Ch3 shady deal (negotiation) 657+; training chapters 23071+ (Ch25 Summoning/Training) |
| `A_Nascent_Kaleidoscope.txt` | **Secondary spine.** "Foreign thoughts"/remembering a past life (Ch1–2: 35–495), magic self-study & runecraft/talisman research (Ch4 ~495–670), Skyrim barrow/portal prose (Ch6+: 982+). Repo namesake — "Kaleidoscope" motif. | 35–1000 |
| `I, Draugr.txt` | **Barrow/dungeon kit.** Crypt crawl, draugr fights, frost magic, spell-testing, snow travel, troll rooms. (QQ dump; body starts ~line 120; strip `​` zero-widths + CRLF.) | 170–800 (Bleak Falls analog → "Greyfell Mound"), 2900–2960 (snow camp), 774 (frost hand) |
| `Legends Never Die .txt` | **Combat realism & family.** Viking farm boy (12yo): first kill, shield wall, axe work, mother's hug, raid defense. | 328 (grown-up kid), 447–520 (house defense/first kills/grief), 802–810 (bridge shield wall) |
| `Tensura.txt` | **System voice.** "Acquisition Successful" boxes, skill tiering (Common/Extra/Unique), analyze-and-combine skill evolution. First-person SI "Felix White" childhood summary (school/orphanage) 82–200. | 82–430, 547–560 (skill fusion) |
| `konosuba.txt` | **Guild/quest/lightness.** Dungeon-in-modern-world opener (goblin/torch fight, Adventurer's Card, class picker joke, skill popups) 73–300; shopping/guild chapters later. Keep comedic beats sparse. | 73–430 |
| `Breaking_the_World_with.txt` | **System banter & body-awakening.** Kip-up/body realization 60–75; system Q&A voice; gacha-roll presentation (remix as one-off "Facet Draw"). | 55–170, plus early-town negotiation chapters |

## Scene/texture donors
| File | What it donates |
|---|---|
| `Borne_of_Caution.txt` | Animal-handling realism ("Harsh is the realization that any animal could turn on you" line 13200±), cub-therapy beats, grounded training arcs, PTSD-recovery pacing, breeder/market negotiation 13007–13190 |
| `The_Stowaway.txt` | **Romance template** (Maren↔Kale slow burn): foundling trust, wound-tending, shared-bed-for-warmth, pining beats. First-meeting wreckage 1940–2010; engine-warmth nodding-off 455–470; "found you" arc 2892–3005 |
| `The_Art_of_Burning.txt` | Captive→trust dynamics, grumpy caretaker beats, camp life, winter-tribal texture |
| `Hp odyssey.txt` / `enchanting melody.txt` | Magic research, ritual rigor, academy politics (Arc 3+ material), disciplined study prose |
| `Wandering prince.txt` | Breath/underwater training-obsession beats (Ch1: 3–40) |
| `Dost_Thou_Even_Steal.txt` | Stealth, heist planning, mask/identity discipline |
| `Ghost_in_the_City.txt` | Gamer UI in a city, reputation systems, vendor/market life |
| `Yakuza.txt` (`DxD: Like a Devil fem gamer`) | Scheming, business dealings, female gamer voice |
| `What_would_Madara_do.txt` | Clan politics, martial pride |
| `I just want to learn magic bro.txt` | **VOICE donor (user's own fic, Heliel43).** Anti-melodrama self-awareness, domestic competence as survival strategy, "flawed mc" candor, magic-as-craft pragmatism. Emulate when bridging. |
| `A_Lack_of_Wisdom.txt` | Disciplined POV introspection, slow-burn team-as-family |
| `The_Hobbit_A_Most.txt` | (Fairy-tale register only) folk-narration cadence for village legend/interlude bits |
| Others (Worm/DxD/Persona fics) | Reserve vault: dialogue sparring, mentor beats, bar-fights, moral-grey banter. Mine by grep per need. |

## Extraction workflow (repeat every chapter)
1. `grep -n` anchors in donor file → `sed -n 'A,Bp'` pull → skim.
2. Compose chapter in `STORY/chapters/NN_Title.md`: paste lifted prose, then edit — names, POV/tense, continuity, remove fandom nouns.
3. Log every donor zone used in `STATE.md` ledger (proves sourcing, speeds recalls).
4. Sanitize: strip CR (`\r`), zero-width spaces (U+200B), form feeds (`\f`), QQ forum cruft (headers/line numbers/"View content"), and any fandom IP nouns (Grimm, chakra, Devil Fruit, Pokémon, Persona, Peerage…). All proper nouns in the final serial must be ORIGINAL.
5. Never re-use the same donor zone twice (check ledger before mining).

## Grep anchors for common needs
- System box voice → `Tensura.txt` ("Acquisition Successful"), `A_Gamers_Grand_Journey.txt` ("[System]", "Quest"), `Breaking_the_World_with.txt`
- Melee combat → `Legends Never Die .txt`, `Ace_In_The_Hole.txt`, `Duelist.txt`
- Dungeon/crypt → `I, Draugr.txt` (170–3781), `A_Nascent_Kaleidoscope.txt` Skyrim arc, `Tensura.txt` Ch27 "The Dungeon!"
- Market/guild/town → `konosuba.txt`, `Breaking_the_World_with.txt`, `Ghost_in_the_City.txt`
- Romance beats → `The_Stowaway.txt`, `The_Art_of_Burning.txt`, `Window_Across_the_Galaxy.txt`, `A_Body_of_Water_and.txt`
- Training arcs → `Borne_of_Caution.txt`, `Wandering prince.txt`, `Hp odyssey.txt`, `enchanting melody.txt`
- Campfire/travel/winter → `I, Draugr.txt` (2900+), `Legends Never Die .txt`, `The_Art_of_Burning.txt`
