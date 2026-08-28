# HARU NATSUKI SAGA — PHASE 1: SOURCE AUDIT

**Corpus:** `nascent-kaleidoscope-source` — 45 works, ~12.4M words.
**Purpose of this document:** Establish what material we actually have, what it is good for, where it conflicts, and how it assembles into the Haru Natsuki Saga. No story is written here. This is the map.

**Method note:** Every claim below is anchored to a specific file (and line number where practical) so the human author can pull the original prose directly. Grep anchors are given in `backticks`.

---

## 0. EXECUTIVE SUMMARY

The corpus is not a random bookshelf. It is a reading library with three dense clusters that map almost perfectly onto the Saga's three pillars:

1. **A Persona 5 cluster** (≈3.5M words) — including the two best possible structural models: an *outsider joins the Phantom Thieves mid-story* blueprint (`Ace_In_The_Hole`), and a *full P5 Royal storyline* blueprint (`Rig_the_Game_Royal`, `Faith_for_the_second_run`).
2. **A Yakuza / Kamurocho cluster** (≈1M words) — including a **P5×Yakuza fusion fic** (`Phantom_Dragon_Rising`) that already solves our hardest design problem: how a protagonist from the criminal underworld enters the P5 plot without breaking it, with a pro-wrestling-obsessed orphanage kid attached.
3. **A Re:Zero cluster** (≈1.4M words) — including a **canon-walkthrough reaction fic** (`The_Exhibition_Of_A_Low`) that compresses Arcs 1–2 into voice-accurate scenes we can consult like a reference bible.

The single most important discovery: **the Ichiban Kasuga material in `Burn_Like_A_Dragon_Rise` is the best existing Don Quixote material in the corpus.** A middle-aged ex-yakuza who experiences reality through a heroic fantasy lens, who refuses to stop believing in heroes, is Haru's psychological baseline already written by a human author — and that fic even contains the *deconstruction* of the hero-fantasy coping mechanism, in dialogue, ready to be re-aimed at Haru.

Second most important discovery: `Sun's Valour` contains a passage naming Theseus's traditional epithets — **"the Club-Bearer, the Line-Bender, the Cliff-Kicker and the Wrestler"** — "legendary for defeating his enemies by turning their own tricks and traps against them." That one passage fuses the two identities the directive assigns Haru: the labyrinth-navigator Persona and the wrestler. This is exactly the kind of specific, non-generic seed the saga should be built on.

There is **no existing Don Quixote/Theseus Persona content, no Haru character, and no Re:Zero material beyond early-arc canon coverage** — those are synthesis zones, identified as such in §7.

**Update (v1.1):** The previous project's state has since been supplied in-chat as a transfer pack (now `planning/transfer_pack.md`) and reconciled against this audit and the master directive in `planning/01_TRANSFER_RECONCILIATION.md`. §6.8 is resolved; several §6 items are now locked in `planning/DECISIONS_LOG.md`. This audit proceeds on the repository alone.

---

## 1. CORPUS INVENTORY & TIERING

### Tier S — Load-bearing (the saga will be assembled from these)

| File | Words | What it is | Why it matters here |
|---|---|---|---|
| `Ace_In_The_Hole.txt` | 887k | P3's Ken Amada joins the Phantom Thieves (PT!Ken AU); full vanilla-P5 plot retold, complete through the Yaldabaoth battle and endings | The **outsider-integration blueprint**: how a traumatized newcomer with his own agenda enters the P5 storyline mid-Kaneshiro and changes it without derailing it |
| `Dost_Thou_Even_Steal.txt` | 855k | Joker banished by Yaldabaoth into MHA Japan; 100 chapters, complete | The **displaced-Trickster blueprint** (inverse of Haru in Lugunica), plus the corpus's most elaborate **Yaldabaoth material**, including the banishment mechanic we can reuse for Haru's transition |
| `Ghost_in_the_City.txt` | 883k | Cyberpunk SI; MC lives with her gangster older brother Jun | The best **lived-in sibling voice** in the corpus; overprotective-brother material that reads like real family, not like plot |
| `Burn_Like_A_Dragon_Rise.txt` | 435k | Post-Yakuza 7 drama, Haruka Sawamura POV, 139 chapters; Ichiban's found family, Kamurocho in decline, later crosses into Persona lore (Kirijo/Anti-Shadow weapons, Adachi as villain, Aigis) | The **Kamurocho bible** + the **Ichiban/Don Quixote psychology mine** + a working template for "the supernatural exists behind the Japanese underworld" |
| `Faith_for_the_second_run.txt` | 742k (ongoing) | P5R Royal Trio (Ren/Akechi/Sumire) time-loop around Maruki's third semester | The deepest **Akechi, Sumire and Maruki characterization** in the corpus; third-semester emotional mechanics |
| `Throw_Away_Your_Mask.txt` | 629k | Akechi thrown back into the P4 era; P3/P4 ensembles; complete posting | Akechi redemption/psychology mine; "working with teenagers who think he's a child" outsider-comedy-into-tragedy register |
| `The_Exhibition_Of_A_Low.txt` | 509k | Re:Zero cast watches Subaru's Arcs 1–2 (complete), SS ongoing | A **canon-walkthrough of Arcs 1–2 with voice-accurate reactions** — our Re:Zero reference bible for the reunion arc era |
| `Borne_of_Caution.txt` | 679k | Pokémon journey fic famous for grounding, PTSD and therapy | The corpus's best **mental-health realism**: therapy sessions, survivor's guilt, de-escalation of drama |
| `Steal_the_Truth_Reach.txt` | 427k | Nanako Dojima follows Joker to Tokyo and becomes entangled in P5; day-by-day calendar structure | The **"refuses to let go and follows" engine** in its purest form, plus a rigorous day/date chapter discipline for plotting the P5 year |
| `The_Art_of_Burning.txt` | 428k | Zuko held captive by Hakoda's crew; slow-burn adoption | Hurt/comfort and **captor→guardian relationship conversion** mechanics; excellent for Haru's darker underworld detours |
| `The_Trickster_and_the.txt` | 978k | Post-P5R Ren joins FGO as a veteran Master | **Post-P5R experienced-Trickster voice**; how a former PT carries the weight afterwards; Velvet Room continuity |

### Tier A — Strong secondary (specific scenes/traits to be extracted)

| File | Words | Extract |
|---|---|---|
| `Phantom_Dragon_Rising.txt` | 126k (ongoing, 9 ch) | **The single most structurally relevant fic in the corpus.** Akira Kurusu raised at Kiryu's Morning Glory Orphanage; wrestling-obsessed little brother figure Taichi; Kiryu's fighting style as legend; full P5 Kamoshida arc underway. See §3 |
| `Black_Star.txt` | 148k, complete | Post-P5 cognitive-world prose of unusually high literary quality (Dead Sea); "the city that was not the city" — atmosphere model for reality-erasure during the Yaldabaoth climax |
| `A_Lack_of_Wisdom.txt` | 320k | SI-as-Sasuke; the Itachi/Sasuke brother wound; unreliable-narrator interiority; "You are not worth killing" beat |
| `Ill-Gotten_Gains.txt` | 357k | Izuku/Shigaraki "siblings of a sort"; parental Aizawa; what it costs to love someone walking into darkness |
| `All_the_Young_Dudes.txt` | 538k | Marauders era; the Sirius/Regulus brother-wound; found-family texture over years |
| `What_would_Madara_do.txt` | 293k | Uchiha OC Ryoko separated from her brothers — *"I have to find my brother… he's probably already looking for me"* (l. 7770) — the mutual-search beat; ANBU-grade combat prose |
| `Sun's Valour (PJO SIMulticross - DXD Start).txt` | 321k | The **Theseus passage** (l. 41876); demigod outsider humor; mentor-student dynamics |
| `Higurashi_Ryu_Ga.txt` | 229k | Kiryu investigating a small town's tragedy; protective-of-children Kiryu; yakuza-investigation mechanics; "how a professional violent man earns a community's trust" |
| `Rig_the_Game_Royal.txt` | 170k (incomplete) | **The P5R storyline fic**: dual protagonist (P5 Ren + P5R female MC Rem), Maruki introduced, Yoshizawa present, cross-reality Velvet Room rules (l. 625–684) |
| `Advent_of_the_Jumper.txt` | 42k | Majima Goro vignettes; the Yakuza world as a place other stories visit |
| `New Game, New Life. (Ranma 12, Multicross, Gamer SI).txt` | 293k | Delinquent-school Japan texture (169 `delinquent` hits); martial-arts social world; e.g. brawl etiquette, gangs, school hierarchies |

### Tier B — Texture only (background radiation, not structure)

`Isekai_Theater.txt` (Subaru explains Return by Death to fellow isekai protagonists, l. 3094 — the **emotional register of an RbD confession**, and other protags' horrified reactions; useful later), `REInfinity_-_Starting.txt` (strong-Subaru AU; Lugunica texture, Emilia-cast banter, Royal Selection references — **voice-only** value, its premise contradicts our Subaru), `Abusing Tropes In A Generic Anime World For Maximum Bullshit.txt` (anime-Japan meta texture), `Burn the World Down (Gamer SI, Avatar The Last Airbender).txt` and `Wandering prince.txt` (training-arc structures), `A_Gamers_Grand_Journey.txt` (escalation/combat), `Breaking_the_World_with.txt`, `The Guild of Gamers The Supervillain.txt`, `Where the hell are the Worms (Chaos Gacha).txt`, `Just as Satan Intended (DxD, Chaos Gacha.txt`, `Hollow Hope(DXD Self-Insert).txt`, `I, Draugr.txt`, `A_Nascent_Kaleidoscope.txt` (**re-tiered in v1.1:** plot-irrelevant, but now the designated VOICE/style donor — it is the author's own prior fic and the saga's first-person tone anchor per the transfer pack; see `01_TRANSFER_RECONCILIATION.md` §4), `A_Body_of_Water_and.txt`, `Down_a_Rabbit_Hole_to.txt`, `The_Hobbit_A_Most.txt`, `It_Started_With_The.txt`.

### Tier C — Not usable for this saga (kept for completeness)

`All_the_Young_Dudes` romance core, `Like_the_Night_that.txt`, `The_Stowaway.txt`, `Their_Captive_Prize_-.txt`, `Window_Across_the_Galaxy.txt` — romance/ID-attachment engines that do not fit a brother-search structure. They remain available if a romance subplot for adult side characters is ever wanted, but nothing in the directive calls for them.

---

## 2. MAJOR SOURCE WORKS — DETAILED CATALOGUE (TIER S + PDR)

### 2.1 `Phantom_Dragon_Rising` — P5 × Yakuza (the bridge fic)

**Premise:** Akira Kurusu grew up at the Morning Glory Orphanage in Okinawa under Kiryu Kazuma's care, then goes to Tokyo on probation — canon P5, with a Yakuza childhood underneath.

**Crown jewels:**

- **Ch. 1 "The Fool of the Orphanage" (l. 52+):** Akira spars with **Taichi**, a bald orphan kid who is "a wrestling fanatic of the highest pedigree," rushing in with any wrestling move he can think of. Akira coaches him: *"Pro bowlers don't become pro bowlers by playing golf. The same goes for pro wrestlers. They don't grow by using styles that don't match their capabilities."* — a ready-made **mentor-voice scene** for Haru teaching (or being taught) wrestling-as-fighting, and for defining Haru's own stylistic identity as *power + durability, not speed*.
- **The Kiryu legend (l. 15440+):** A shopkeeper recognizes Akira's fighting stance as Kiryu's and recounts, with awe and three months of broken ribs, how Kiryu *"picked up a damn bicycle and fucking powerbombed it over his chest."* This is the corpus's existing template for **wrestling-vocabulary violence treated as real, legendary force** — exactly the directive's "WWE/NJPW movement vocabulary + genuine street violence." It also demonstrates the social mechanic: Haru's style gets *recognized* by underworld old-timers, which builds his reputation without exposition.
- **Ch. 4 "Metaverse 101":** the fic deliberately on-ramps a street-level protagonist into cognitive-world mechanics — useful scaffolding for Haru's first Metaverse exposure.
- **Structure:** orphanage found-family → lone transfer to Tokyo → P5 canon begins (Kamoshida palace at ch. 9). Haru's Earth arc can borrow this shape: **home/family unit → loss → arrival in a new city → canon event swallowing him**.

**Adaptation note:** PDR proves the *fusion* works without Altering P5's spine. We are not copying Akira (Haru is his own person with a different wound), but the fic's connective tissue — how Kiryu-lore, orphanage family, Iwai, and probation Tokyo interlock — is directly reusable.

### 2.2 `Burn_Like_A_Dragon_Rise` — the Kamurocho bible & the Ichiban mine

**Premise:** 2022–23. Kiryu is (publicly) gone; Haruka Sawamura fights to keep Morning Glory Orphanage alive; a loan from Akiyama leads her to Ichiban Kasuga's Ichiban Holdings in Ijincho; the story broadens into a multi-city yakuza epic whose back half collides with Persona-3-adjacent supernatural material (Kirijo "Shadow Research Facility" on Yakushima, Anti-Shadow Suppression Weapons, Aigis, Adachi as a major antagonist — 510 mentions).

**Crown jewels:**

- **Ichiban's hero psychology:** *"I'm just doing what a hero would do. It gives the other guy a chance to fight back, y'know? A fight isn't very fun if it's a one-hit KO."* (l. 11883) and Kiryu's flat reply, *"If I ever see the world the way you do, kill me."* — an existing **two-voice argument about idealism vs. realism** that can be re-cast as anyone-vs-Haru, or Subaru-vs-Haru.
- **The deconstruction:** Yagami and Akiyama discussing pandemic coping: *"What, like, people are pretending to be video game heroes so they don't have to think about how bad their lives suck?"* / *"Sheesh… That's depressing. You have to be a special kind of deluded to buy into something like that…"* (l. 16000) — and the story immediately cuts to an earnest cosplayer (Yukari Takeba cameo) being robbed. This scene is Haru's Don Quixote thesis **and** its counterargument, already in dialogue form. Do not explain the Persona symbolism in dialogue (directive §10) — but if the author ever wants the symbolism challenged out loud, this is the text to adapt.
- **Kamurocho in decline** (post-3K-plan crime wave, post-Aoki assassination politics, ch. 1's briefing through Akiyama): a grounded, specific criminal-underworld setting for Haru's investigation years — factions, ex-yakuza security companies, a burned trust ecology, *"stay away from Kamurocho. At least for now."*
- **Underground tournament arc** (ch. 53–58 region, "Mad Dog," "It's Going Down Now"): cage fights, Ichiban + Kiryu team fights, ring entrances — a ready-made **combat set-piece venue** where Haru's wrestling-as-real-violence identity can be forged and witnessed.
- **The unified-world mechanic** (ch. 64+): ordinary yakuza stumbling into Anti-Shadow weapons and asking *"Shadow what-now?"* (l. 19115) — the template for **how Earth civilians with zero metaphysical vocabulary experience first contact with the cognitive layer**. Haru's pre-Persona encounters with the strange can be staged exactly this way: underworld people, underworld logic, encountering something the underworld has no words for.
- **Idol/orphanage family material:** Haruka's guardianship, Haruto, Ayako; the Morning Glory money plot is a model for **the mundane stakes that keep an Earth arc grounded** (someone has to pay rent while the Metaverse burns).

**Contradiction vs. PDR (see §6):** In PDR Kiryu is alive; in BLAD Kiryu has "passed." Both cannot be true in one continuity without reconciliation.

### 2.3 `Ace_In_The_Hole` — the outsider-joins-P5 blueprint

**Premise:** Frame story: Sae's interrogation of Ren (l. 60+). Then the full P5 plot from Kaneshiro onward with Ken Amada — a former Metaverse combatant with dead-parent grief and a suppressed history — pulled in by Mitsuru, awakening a Persona, and joining the Thieves as an additional member alongside the full canon cast.

**Crown jewels:**

- **The full P5 event map** with an outsider threaded through: Mafia/Bank (Kaneshiro) → Awakening → Medjed → Pyramid → "To Be A Phantom Thief" → Okumura spaceport → Inaba trip (a delightful P4-detour chapter pattern) → school festival → casino of envy → "Whims of Fate" → Shido cruiser → "Into the Depths" (Yaldabaoth) → "With The Stars and Us." Chapter headings at `grep -n "Chapter [0-9]\+:" Ace_In_The_Hole.txt`.
- **The Yaldabaoth battle staging** (l. 70860+): Grail transformation, the god's *why-do-you-defy-me* exchange with each Thief answering in voice (Haru Okumura's line, *"If this is all for the sake of humanity, wouldn't being beaten by humans satisfy you?"* is worth preserving verbatim), city-wide Shadow chaos below with named civilians being caged, Sae's ground-level POV, Akechi's ambiguous non-participation: *"They've made their choice. And I've made mine."* This is the **climax template**: god-scale fight intercut with ground-level consequence.
- **How a sixth-wheel Thief earns his spot:** Ken gets a persona awakening scene (ch. 5 "Awakening"), an acceptance arc ("To Be A Phantom Thief"), and continuous "the veteran among children" friction — the exact social position Haru would occupy, but Haru's version is inverted: *he's* the one searching, not being recruited.

### 2.4 `Dost_Thou_Even_Steal` — displaced Trickster + Yaldabaoth lore

**Crown jewels:**

- **The opening (l. 92+):** Yaldabaoth's banishment — *"The sin of rebelling against a god is severe. As punishment, I banish you to other worlds unknown!"* — with **four doors to other realities** tearing open. This is a ready-made, corpus-native **mechanism for Haru's transition to Lugunica** (option A in §5.7).
- **Interrogation-room cold open (l. 113+):** a world-class liar choosing what to reveal, testing Tsukauchi — a masterclass in **protagonist-keeps-secrets dialogue**; directly reusable register for *Subaru* managing what he tells Haru in Lugunica, and for Haru lying to police about his search.
- **A missing-brother echo:** a bystander asks Joker for help — *"My brother went missing about two weeks ago… I've been trying to look for him."* (l. 10772) — small scene, but proof the corpus already writes strangers-with-missing-siblings warmly.

### 2.5 `Rig_the_Game_Royal` + `Faith_for_the_second_run` — the P5R storyline kit

- **Rig** runs the P5R calendar with a twist premise (a Ren who *lost* to Yaldabaoth gets a second chance in the P5R reality where a female MC "Rem" exists). Extract: the **P5R event calendar** with Maruki's introduction (l. 10203+), Yoshizawa dynamics, and the **cross-reality Velvet Room rule** (l. 625–684): Igor/Lavenza can grant a game in a different reality but *"shall have no knowledge of your actions"* once it begins — a precedent if we ever need Velvet Room mechanics that don't break our story's stakes.
- **Faith** is the emotional third-semester mine: Sumire discovering months were stolen (*"Wasn't their deadline February third? And -oh no- It's April"*, summary), a Royal Trio digging "their graves and lying in them" (its tag: *Miscommunication, in the sense that the Royal Trio have decided to dig their graves and lie in them*). Extract: **Maruki's offer as temptation-of-the-grief-stricken** — the exact emotional mechanism Haru will face, because Maruki's actualization can, for Haru, literally mean *"a world where Subaru never disappeared."*

### 2.6 `The_Exhibition_Of_A_Low` + `Isekai_Theater` + `REInfinity` — the Re:Zero reference shelf

- **Exhibition** = Arcs 1–2 walked scene-by-scene with the Lugunica cast reacting in-voice (Roswaal's drawl, Beatrice's "in fact/suppose," Ram's "Barusu," Otto's flustered loyalty, Garfiel's bravado). It contains the corpus's densest **Subaru-suffering-and-love material** (Arc 2 loop chapters: "That Boy Loves You," "To Be An Oni," "To Be A Sister," "Can't You Make The Crying Stop?"). Coverage is honest: **Arcs 1–2 complete; Arc 3–4 not yet in file** — for later arcs we write from canon knowledge, using Exhibition as the tone reference.
- **Isekai Theater** gives the **register of a Return-by-Death confession** (l. 3094): *"I can… Return by Death! Time rewinds when I die! It felt so… painful... I was so scared!"* — note: in that fic the penalty is gone. In OUR story the penalty stands; this scene is a register reference for what a RbD reveal costs the confessor, not a template to copy.
- **REInfinity** is a strong-Subaru AU (Gojo-bloodline Subaru, confident and overpowered). **Its premise contradicts directive §18's Subaru** (terrified, exhausted, secretly strategic). Voice-only value: Emilia/Ram/Emilia-cast banter, Royal Selection texture.

### 2.7 `Steal_the_Truth_Reach` — "she can't let go of the injustice. And follows him."

The premise sentence is Haru's engine in miniature. Nanako (a child with her own unprocessed trauma from a past case) attaches herself to the P5 plot out of refusal to accept an unfair loss. Extract: the **calendar discipline** (every chapter is a date: "2/14 - Morning," "4/12 - Castle of Lust") — the cleanest plotting tool in the corpus for mapping Haru's year against the P5 calendar; and the **child-of-a-tragedy joining a bigger tragedy** emotional arc.

### 2.8 `Black_Star` — the prose benchmark

Complete, 19 chapters, post-P5: Paranoia Syndrome, the Dead Sea (the rotted cognitive world where *"all things go to be forgotten — including someone the Thieves had"*). The opening (l. after "Chapter 1") is the corpus's best cognitive-world prose: *"In the city that was not the city the streets had no signs, only slates of blank metal hanging askew on their poles as if confused how they came to be there… And everywhere he went, there was water, ice-cold and dark as ink."* Extract: **atmosphere for the Yaldabaoth climax** (a Tokyo being unwritten), and the precedent that post-victory cognitive damage lingers.

### 2.9 `Throw_Away_Your_Mask` + `Faith` — the Akechi problem/asset

The corpus contains ~13,000 mentions of Akechi across four fics — this library is *obsessed* with him, and the saga should take that seriously rather than trimming him to a canon walk-on. Relevant assets: Akechi as the celebrity detective whose casework intersects missing persons; Akechi's mother's suicide and bastard origin (a boy erased by power); TAYM's full redemption-engine; Faith's "royal trio lying in their graves together" register. (See §5.6 for the recommended integration.)

### 2.10 `Borne_of_Caution` — grounding the aftermath

Best-in-corpus therapy material: *"please answer this honestly. Have you seen a professional about your PTSD yet?"* (l. 15145); *"She said I've got PTSD and survivor's guilt."* (l. 17257). The saga needs this register: Haru's grief must be allowed to be a *condition he lives with*, not a personality trait; and post-Metaverse damage needs consequences that therapy, sleep, and honesty address.

---

## 3. EARTH-BASED MATERIAL — WHAT THE CORPUS GIVES THE EARTH ARC

The Earth arc needs, per directive §8: family, loss, investigation, underworld, personality change, combat identity, relationships, supernatural escalation, P5R, climax.

| Earth-arc need | Corpus source |
|---|---|
| A home worth losing | PDR's Morning Glory scene (l. 52–200); BLAD's orphanage finance plot (ch. 1–2); Ghost in the City's Jun-sibling domesticity (l. 1511+) |
| The disappearance wound | A_Lack_of_Wisdom's Itachi-wound interiority (l. 226–390); WWMD's separated-siblings mutual search (l. 7770); ATYD's Sirius/Regulus estrangement |
| An investigation that develops naturally | BLAD/Yagami's detective agency (ch. 1, l. ~330); Higurashi's Kiryu-investigates-a-mystery structure (59 chapters of it); DTES interrogation/lying craft (l. 113+) |
| Underworld depth | BLAD entire (Kamurocho decline, ex-yakuza economy, tournaments); Higurashi (clan politics); PDR (Iwai, underground reputation mechanics) |
| Wrestling combat identity | PDR ch.1 (Taichi) + Kiryu bicycle-powerbomb legend (l. 15486); BLAD tournament arc; Sun's Valour's **Theseus "the Wrestler"** (l. 41878); Ichiban's fairness psychology (l. 11883) |
| Delinquent/school Japan texture | New Game New Life (delinquent etiquette); Abusing Tropes (anime-Japan social texture) |
| First contact with the impossible, told from a mundane POV | BLAD's "Shadow what-now?" scenes (l. 19115+); PDR "Metaverse 101" |
| The P5 year, day by day | Steal_the_Truth's calendar structure; Ace's event map; Rig's P5R calendar |
| Emotional aftermath mechanics | Borne_of_Caution (therapy, survivor's guilt); The_Art_of_Burning (injury/recovery/hurt-comfort pacing) |
| A world where the supernatural stays hidden | BLAD's Kirijo back-half (supernatural contained inside corporate/agency secrecy) |

**Kamurocho note:** the directive's example adaptation names Kamurocho. The corpus supports a Japan where **Kamurocho (Yakuza) and Tokyo/Yongen-Jaya (P5) coexist** — BLAD itself has Kamurocho, Sotenbori and Ijincho in one geography, and PDR has Kiryu-lore people inside P5's Tokyo. The saga's Earth can simply be that Japan.

---

## 4. PERSONA-RELATED MATERIAL — WHAT THE CORPUS GIVES THE PERSONA STORYLINE

- **Plot spine:** vanilla-P5 event map (Ace, complete) + P5R event map (Rig, through Maruki's tenure; Faith, third-semester interiority). Between them, the full Royal storyline exists in the corpus at scene level.
- **Awakening scenes:** Ace ch. 5 "Awakening" (an outsider's awakening mid-crisis); DTES/Rig/TAYM for Velvet Room framings. **Gap:** none of these feature a Don Quixote-style awakening — the *flavor* of Haru's awakening is a synthesis zone (§7).
- **Team integration mechanics:** Ace is the manual — how the Thieves test, tease, distrust, and finally adopt an outsider; "To Be A Phantom Thief" (ch. 11) is the acceptance chapter template.
- **Akechi:** the corpus's deepest character obsession; three distinct Akechi models (TAYM's time-displaced Redeemer, Faith's co-conspirator-in-grief, Ace's ambiguous survivor who saves Sae and walks away — l. 70960+). For Haru, the ambiguity model is the most usable.
- **Maruki/third semester:** Rig (structure) + Faith (interiority) + TAYM's reality-warp fallout register. The third semester is where the saga's deepest Haru material lives (see §5.5).
- **Yaldabaoth:** three staggers to combine — Ace's battle+ground-chaos staging, DTES's banishment-doors mythology, Black Star's erased-Tokyo atmosphere.
- **Post-P5 voice:** The_Trickster_and_the (a Ren who carries it afterwards; useful for the arc's final chapters and for any scene where Haru realizes the fight didn't fix everything).

---

## 5. POTENTIAL HARU MATERIAL / SUBARU-HARU DYNAMICS

### 5.1 The engine (extracted, not invented)
Steal_the_Truth's premise — *"she can't let go of the injustice. And follows him."* — is Haru's engine in existing words. WWMD's Ryoko — *"I have to find my brother… he's probably already looking for me."* — is the saga's long-game payoff: **Subaru, in Lugunica, being unable to say whether anyone is looking for him, and Haru crossing a world because the answer is yes.**

### 5.2 The lived-in sibling register (existing models to blend)
- **Everyday domesticity:** Ghost_in_the_City's Jun beats — *"It is what I am here for."* (l. 1525); big-brother humor ("The big brother taking pleasure in siblings torture look," l. 10254). Haru and Subaru's *past* should read like this: mundane, unsentimental, constant.
- **Teasing + devotion:** PDR's Akira/Taichi coaching banter; BLAD's Haruka/Kiryu deference-and-defiance.
- **The wound:** A_Lack_of_Wisdom — a brother who kills his whole world and still says *"my big brother, the one I loved more than anything"* (l. 226–236): the register for Haru's worst nights; and ATYD's Regulus material for the *abandoned*-feeling variant (Sirius leaving = Subaru vanishing without explanation).
- **Directive §17's list** (tease/fight/protect/misread/joke/break down) is fully serviceable from these four sources without inventing a new register.

### 5.3 The mask problem (Subaru in Lugunica)
Subaru's external persona vs. internal terror is already characterized in the corpus at three depths: Exhibition (the boy who performs confidence so his friends won't see the loops), Isekai Theater's confession scene (what it costs to say it out loud), and REInfinity (the confident register Haru will *remember* — which is the trap: Subaru can sound exactly like his old self while dying inside). Haru knowing him well (directive §18) means Haru's POV chapters should be the ones where Subaru's façade visibly costs him — the corpus's Akechi-POV chapters (TAYM, Faith) are the best existing studies of a narrator maintaining a mask around people who can almost see through it.

### 5.4 Mind and fist (directive §19)
Subaru = the mind, Haru = the fist is pre-figured twice: Ichiban/Kiryu in BLAD (the dreamer who plans by hero-logic, the professional who executes) and PDR's Akira coaching Taichi (the one who sees the whole style, the one built for power). The directive's caution — Haru is not stupid, Subaru is not helpless — is served by the Ichiban/Kiryu material, where "the muscle" routinely makes the *moral* call the strategist misses (e.g., Ichiban's fairness speech, l. 11883).

### 5.5 The Don Quixote → Theseus track (existing seeds only)
- **Don Quixote seed:** Ichiban — the man who *chose* to see heroes in a world that told him he was trash, and whose fantasy lens is shown both as strength (he saves people because he believes) and as coping (the Yagami/Akiyama deconstruction, l. 16000). Haru's awakening flavor should be built from Ichiban's psychology minus the delusion: Haru doesn't see monsters; he *refuses to see a corpse* where his brother should be.
- **The windmill line exists in-corpus** but only as background texture (`Down_a_Rabbit_Hole_to`, 2 hits) — do not lean on it; the symbolism should be demonstrated (directive §10).
- **Theseus seed:** Sun's Valour l. 41876–41880 — *"between the Club-Bearer, the Line-Bender, the Cliff-Kicker and the Wrestler, that guy was legendary for defeating his enemies by turning their own tricks and traps against them."* This gives the evolution its concrete meaning: Don Quixote charges; **Theseus reads the labyrinth and turns its own mechanisms against it** — which is also the wrestling identity (counters, leverage, using the opponent's weight = using the labyrinth's own walls). Mementos is literally a labyrinth; the evolution can be earned there, then pay off forever in Lugunica (politics, cults, Witch factors = a bigger labyrinth).
- **Evolution trigger, per directive §11:** early Haru "I need to find my brother" → later "I found him; now I keep him alive." The corpus's closest existing conversion arc is Ace's Ken (recruited to search for justice → stays to protect people he loves).

### 5.6 The Akechi intersection (recommended synthesis, clearly marked as new structure)
The corpus's Akechi density suggests the saga can *earn* a real Akechi subplot: Akechi as celebrity detective whose career is built on closed cases — including, plausibly, the 2016 case file of a missing boy named Natsuki Subaru (a "solved as runaway" file Haru keeps hitting a wall against). This uses only canon-Akechi mechanics (Shido's errand boy curating cases) plus the corpus's characterization. No existing scene to adapt — flagged as new connective structure (§7) — but every *character* ingredient is in-corpus.

### 5.7 The transition mechanisms (existing, corpus-native)
1. **Yaldabaoth's doors** (DTES l. 92+): the dying god's curse banishes Haru "to worlds unknown" — ironic, cruel, thematically perfect (the god of control's last act is to remove the one person who controls nothing).
2. **The Velvet Room deal** (Rig l. 625–684): a cross-reality arrangement whose rules we can define — e.g., Lavenza cannot tell Haru where Subaru is, only open the door the "fool's journey" demands.
3. **The Dead Sea drift** (Black Star): post-Yaldabaoth, the rotted cognitive world is unsettled; Haru pursuing *one impossible door that smells like his brother's room* into the place where forgotten things go — and falling through. Most atmospheric; least mechanical.

All three can be combined (Velvet Room frames it; Yaldabaoth's death-wound makes the hole; the Dead Sea is the corridor). Decision deferred to Phase 7.

### 5.8 Lugunica-side material (post-transition)
- Canon-walkthrough + voices for Arcs 1–2: Exhibition. Emilia-cast banter: REInfinity, Isekai_Theater.
- **What Haru arrives INTO matters:** directive §15 (canon momentum) + §8's Subaru = the strategist. The corpus's reaction-fic format is a gift here: Exhibition demonstrates each canon beat's emotional temperature (what Rem's loops feel like to people who love Subaru) — exactly what a *brother* walking into mid-Arc-2-era events would collide with.
- **Optimal entry point (deferred to Phase 8):** before Arc 2 (max impact on loops Haru can't understand), or before Arc 3 (White Whale/Royal Selection — the directive's politics-and-cults labyrinth). Not decided in this audit.

---

## 6. CONTRADICTIONS (surface, don't hide — directive §24)

1. **Kiryu alive (PDR) vs. Kiryu dead (BLAD).** Both fics are load-bearing. *Reconcilable:* choose one continuity for the saga's Earth (Phase 2 decision); the unused fic's non-Kiryu material remains valid. Note the two fics' eras don't overlap anyway (PDR: 2016 Tokyo; BLAD: 2022–23 multi-city).
2. **Protagonist naming across the P5 fics:** Ren Amamiya (Dost, Steal, Ace, BLAD cameo, Trickster) vs. Kurusu Akira (Black Star, Rig, PDR). One must be standardized. Recommendation: **Ren Amamiya** (corpus majority + official), with PDR's *orphanage-grown* backstory transplanted rather than its name.
3. **P5's calendar (April 2016–March 2017) vs. Subaru's disappearance.** Canon Subaru is 17 at summoning; the directive wants Haru searching for *years* before P5 events. Working proposal (flagged, not fixed): Subaru vanishes spring 2013 (age 17); Haru, b. ~2001, is 12 at the loss, 15 entering Shujin's neighborhood orbit in 2016 — his whole adolescence shaped by the search, arriving at the P5 events already hardened. Poignant bonus: in Lugunica Subaru is still ~17; Haru arrives ~16–17. **The older brother stopped aging; the younger brother grew up to almost catch him.** This near-convergence is available *because* of the corpus's two timelines and should be a deliberate choice in Phase 2.
4. **Okumura Haru name collision.** The protagonist is named Haru Natsuki (fixed). P5 has Okumura Haru as a core Thief. This will collide in-text and must be handled *deliberately* (comedy beat, nickname differentiation, or a first-meeting scene that weaponizes it). Options open; must not be silently ignored.
5. **REInfinity's overpowered confident Subaru vs. directive §18's terrified strategic Subaru.** Resolution: REInfinity is voice-texture only; its premise is rejected.
6. **Isekai Theater's penalty-free RbD vs. canon penalty (heart-crush/punishment).** Resolution: our story keeps the penalty; the confession register alone is borrowed.
7. **Exhibition covers Arcs 1–2 only.** For Arc 3+ the saga writes from canon knowledge with Exhibition as tone reference. Not a contradiction — a coverage limit, stated so nobody expects file support later.
8. **Previous project history unavailable.** ~~Directive §5 asks me to inspect prior-project planning...~~ **RESOLVED in v1.1:** supplied as `planning/transfer_pack.md` and reconciled in `planning/01_TRANSFER_RECONCILIATION.md`. Key ruling: the transfer pack governs where compatible with the master directive; the Ajin element is removed per directive §14; the pack's locked timeline supersedes this audit's §6.3 proposal.

---

## 7. GAPS — WHERE NEW CONNECTIVE WRITING WILL BE REQUIRED

Per directive §23, each gap is stated as *what the scene must accomplish*, not pre-written:

1. **Haru himself.** No corpus character is Haru. The assembly path: Ichiban's belief (BLAD) + Kiryu-style restraint and physicality (BLAD/PDR/Higurashi) + Nanako's refusal-to-let-go (Steal) + Ken's outsider-among-Thieves position (Ace) + Jun's brotherhood register (Ghost) — combined into one boy with one wound. Phase 2's first task.
2. **The Persona (Don Quixote) and its awakening.** No corpus scene has a Quixotic awakening. Needs: an awakening whose *imagery* is windmills/lance/heroic-folly without dialogue-explaining it. The *mechanics* of awakening are in-corpus (Ace ch. 5); the *flavor* is new.
3. **The Theseus evolution.** Trigger, location (likely Mementos), and the new imagery — anchored to the Sun's Valour epithets (§5.5). New scene; existing thematic anchors.
4. **The reunion scene (Lugunica).** The saga's centerpiece. No corpus scene reunites brothers across worlds. Needs: recognition beat, mask-vs-intimacy beat (§5.3), and the *delayed* understanding of RbD (directive §18). Available models for register only.
5. **Haru's investigation years (the connective tissue of the early Earth arc).** The corpus gives setting and mechanics (BLAD/Higurashi) but no existing missing-person arc. Note DTES l. 10772 as a kindness-template for strangers who help.
6. **Akechi/Natsuki-case intersection** (§5.6): new structure, existing characterization.
7. **Maruki's temptation of Haru.** The third-semester mechanism exists (Rig/Faith), but Haru's *specific* offer — a reality where Subaru never left — is the saga's darkest and most personal synthesis, to be planned in Phase 4. It is also, structurally, the missing-person trap made literal: the one temptation Haru cannot refuse cheaply.
8. **Post-Yaldabaoth transition chapter(s)** (§5.7): mechanism exists; staging is new.

---

## 8. STRONGEST PROSE TO PRESERVE OR ADAPT (human writing worth protecting)

- **Black Star** — Dead Sea opening & ch. 10 paranoia-Tokyo (atmosphere for Yaldabaoth's Tokyo).
- **BLAD** — Haruka/Akiyama ch. 1 (grief carried in logistics: *"Dead… almost two years ago, now"*); Kiryu/Ichiban hero-argument (l. 11883–11905); Yagami/Akiyama hero-deconstruction (l. 15990–16000); the Kiryu entrance at the tournament ("The Dragon of Dojima… KAZUMA KIRYU!!!!").
- **PDR** — the beach sparring scene (ch. 1); the Iwai revelation scene (l. 15440–15540) — how reputation is felt, not stated.
- **Ace** — the Yaldabaoth confrontation exchange (l. 70868–70935), esp. Okumura Haru's line and Morgana's *"We'll take it back… our future… And this world!"*; Akechi/Sae street scene (l. 70960+).
- **DTES** — the banishment proclamation (l. 92+); the interrogation-room mask-work (l. 113+).
- **Exhibition** — the Arc 2 loop chapters' reaction texture ("That Boy Loves You"; "Can't You Make The Crying Stop?") for Lugunica-cast voices under emotional fire.
- **Ghost in the City** — the Jun shooting-range scene (l. 1511+) as the model of sibling care without sentiment.
- **Borne_of_Caution** — the therapy scenes (l. 15145, 17257) as the model for honest aftermath.
- **Sun's Valour** — the Theseus epithet passage (l. 41876–41880), verbatim-quality.
- **A_Lack_of_Wisdom** — the "You are not worth killing" wound (l. 226) as the register of brotherhood at its most broken.

---

## 9. ASSEMBLY ASSESSMENT — HOW THE SAGA COMES OUT OF THIS MATERIAL

The test in directive §27: could this story only have emerged from this corpus? Run the pillars:

- **Earth arc, underworld layer** — from BLAD + PDR + Higurashi (Kamurocho decline, orphanage stakes, reputation mechanics, tournament violence).
- **Persona 5 Royal pillar** — from Ace (outsider integration), Steal (calendar + refusal-to-follow engine), Rig (P5R structure), Faith + TAYM (Akechi/Maruki/Sumire interiority), Black Star (aftermath atmosphere), Trickster (post-P5 voice).
- **Don Quixote** — from Ichiban, with the corpus's own deconstruction as counterweight.
- **Theseus** — from Sun's Valour's epithets + Mementos-as-labyrinth + the wrestling identity already seeded in PDR/BLAD.
- **Yaldabaoth climax → transition** — from Ace's staging + DTES's doors + Black Star's erasure + Rig's cross-reality rules.
- **Lugunica arc** — from Exhibition's canon-walkthrough + Isekai Theater's confession register + REInfinity's cast voices, with Subaru characterized per Exhibition (not per REInfinity).
- **Brotherhood** — from Ghost (domestic), A_Lack_of_Wisdom (wound), WWMD (mutual search), ATYD (abandonment), Art_of_Burning (guardianship).

The result is a story whose every load-bearing wall comes from the library: a wrestling-styled boy from a Kiryu-shaped underworld, driven by a Nanako-shaped refusal, armored in an Ichiban-shaped delusion that slowly becomes a Theseus-shaped competence, who fights through an Ace-shaped P5R year, watches a Black Star-shaped sky tear open over Tokyo, and falls through a Dost-shaped door into an Exhibition-shaped world where his brother is holding a mask together with both hands.

That story could not have been generated from the phrase "Re OC fanfiction." It can only be assembled from this shelf. **Assessment: the corpus is sufficient.** The gaps in §7 are connective, not structural.

---

## 10. OPEN QUESTIONS FOR THE AUTHOR (blocking Phase 2–3, not blocking this audit)

1. **Previous project files:** can they be supplied (or key decisions restated)? §14 tells me Ajin is removed; everything else about prior Haru decisions is unknown.
2. **Kiryu generation vs. Ichiban generation:** is the saga's Kamurocho the Kiryu-era underworld (PDR flavor; Kiryu alive, 2016 Tokyo-adjacent) or post-3K decline (BLAD flavor; Kiryu gone, Ichiban Holdings present)? This decides which fic is the primary setting-donor.
3. **P5 protagonist name:** standardize on Ren Amamiya (recommended) or Akira Kurusu?
4. **Okumura Haru collision:** play it for comedy, play it for awkwardness, or sidestep via "Natsuki" as his primary name in-team?
5. **Subaru's Earth timeline:** does the spring-2013 disappearance proposal (§6.3) work, including the age-convergence poignancy?

*End of Phase 1. Next: Phase 2 — Character Synthesis (building Haru, the brothers' history, and the Earth cast from §5's components), then Phase 3 — Earth Arc Architecture.*
