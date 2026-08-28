# HANDOFF — READ THIS FILE FIRST

**You (the agent reading this in a fresh chat) are continuing THE HARU NATSUKI SAGA — a long-form Re:Zero × Persona 5 Royal × Yakuza fanfiction.** This file is the complete transfer package. Read it, then the files it lists, then work. Do not rely on chat history — there is none. Everything lives in these files.

---

## 1. THE PROJECT IN ONE PARAGRAPH

Haru Natsuki, 15, is the younger brother of Natsuki Subaru (Re:Zero), who vanished from Earth on Dec 23, 2015 (canon Satella summoning; nobody on Earth knows). Haru carries a "death anchor" — he feels pain-echoes of his brother's Return-by-Death loops (feeling only, never information) — and has built a self-convinced delusion that the yakuza took Subaru. By day he's an unremarkable Shujin first-year; by night he's "Winter," a Kamurocho street fighter working an invented case with pro-wrestling as his real combat style. **Book One = the full Persona 5 Royal year (Apr 2016–Feb 2017), 23 chapters × 10k words, ending with Haru crossing into Lugunica during Maruki's reality reversion.** The saga's heart is the brothers: Book II is their reunion, with Subaru as the terrified strategist and Haru as the fist.

## 2. READ ORDER (all paths relative to repo root)

1. `planning/MASTER_DIRECTIVE.md` — the author's founding brief, **verbatim, supreme law**.
2. `planning/DECISIONS_LOG.md` — every locked ruling from every working session (Ajin removed, no Velvet Room, awakening moved to ch. 7's Bank, word law, all of it). **If any doc contradicts this log, the log wins** (unless MASTER_DIRECTIVE overrides both).
3. `planning/STATUS.md` — pipeline state + the 23-chapter tracker (what's drafted/humanized/posted) + production rules.
4. `planning/03_EARTH_ARC_ARCHITECTURE.md` (v2) — the chapter-by-chapter map with canon-verified dates, A/B/C plots, corpus donors, and the foreshadow/payoff ledger (§6).
5. `planning/04_PERSONA_INTEGRATION.md` — Don Quixote kit, the ch. 7 awakening beat-map, Nav rules, Theseus triggers.
6. `planning/05_CHARACTER_DEV_TRACKER.md` — continuity bible: injury ledger, anchor-log trend, per-chapter deltas, ration maps (comedy %, raw lines).
7. `planning/02_CHARACTER_SYNTHESIS.md` — who everyone is and why (voice donors, knowledge tables).
8. `planning/06_YALDABAOTH_CLIMAX_DESIGN.md`, `planning/07_TRANSITION_TO_LUGUNICA.md` — ch. 18 and ch. 23 beat-level designs + post-crossing policy.
9. `planning/00_SOURCE_AUDIT.md` — the corpus map (45 works, ~12.4M words, tiered, with line anchors) and `planning/transfer_pack.md` — the previous project's state.

**When drafting chapter N:** read STATUS row N, `03` §4 chapter N brief, `05` rows N and N−1, the ledger (`03` §6), and any design doc owning that chapter (`06` for ch. 18, `07` for ch. 23, `04` §1.2 for ch. 7).

## 3. NON-NEGOTIABLE RULES (the short list — full versions in MASTER_DIRECTIVE + DECISIONS_LOG)

- **NO AJIN.** Haru is mortal. No regeneration, no reset, no IBM. Wounds heal at normal speed (see the injury ledger in `05`).
- **NO VELVET ROOM.** Haru is not a wild card, never a guest, no contract, no Igor/Lavenza scenes. His Persona (DON QUIXOTE → THESEUS in Book II) awakens by **shadow-acceptance** inside Kaneshiro's Bank on the Thieves' calling-card invasion day (~Jul 6, ch. 7).
- **Pre-awakening quarantine (ch. 2–6):** nothing supernatural touches Haru. Chapters 2–6 are a pure yakuza story. Only exceptions (established in ch. 1): anchor pains + the Nav's "No results found."
- **Haru has zero meta knowledge.** No Re, no canon, no future. He reacts on available information. The audience knows; he never does; never explain in narration.
- **Canon is default.** Book One changes ZERO canon outcomes; the one divergence is the crossing itself.
- **Anchor grants no powers, no information. Ever.**
- **Voice law:** first-person Haru, dry snark, blunt, restrained emotion — **one raw line per chapter max** (map in `05` §7), comedy 25–35% of scenes (map in `05` §7, front-loaded), grief in small bursts ("Maybe someday" register). Rating T; Futaba romance PG/blush-level, confession before endgame.
- **Word law:** 10k target per chapter (up/down allowed). **Show-don't-tell is house method** — it expands scenes; mark expansion points for the author's pass; no mindless bloat.
- **Named yakuza rations:** Kiryu = ch. 4 myth + ch. 9 on-page lesson (≤2 total); Majima = ch. 5 (slot 1 of 2); Iwai = recurring supporting (not rationed); Ichiban = absent (in prison, canon); no spam — they appear to SAVE or TEACH when the situation is beyond Haru.
- **Workflow:** agent produces ROUGH drafts + **Humanization Notes**; the AUTHOR rewrites with human touch and approves before anything posts. Final prose is the author's. After finalization: update `STATUS.md` tracker and `DECISIONS_LOG.md` if new rulings, then **git commit** to branch `arena/01a0473b-nascent-kaleidoscope-source` (push only to that branch).

## 4. CURRENT STATE (at handoff)

- **Planning: COMPLETE for Book One** (Phases 1–7 done). Phases 8–9 (Lugunica/Book II architecture) not started — required before Book II drafting, not before Book One production.
- **Prose: none in repo yet.** Chapter 1 v4 exists in the author's OLD workspace (never transferred). The v4.1 revision treatment is `03` §7.
- **Next actions (in order):** (1) ch. 1 v4.1 — from the author's pasted v4 text (line-level pass: remove Ajin content, add the live May 2 confession-day opening) or fresh from the treatment; (2) ch. 2 "The Name" draft (brief: `03` §8) — 10k + Humanization Notes.
- Chapter drafts live in `planning/chapters/chNN_title.md`.

## 5. CANON ANCHORS (verified; sources in `03` §11)

Kamoshida confession **May 2, 2016** (ch. 1 opens live in the gymnasium) · Mementos opens **May 7** · Kaneshiro window **Jun 19–Jul 9**, calling card/invasion **~Jul 6** (Haru's awakening) · confession **Jul 9** · Medjed **Aug 21–22** · Futaba confession **~Aug 31** · Okumura collapse **Oct 11** · Akechi→Sae **Oct 28** · Ren's arrest **Nov 20** · election **Dec 18** · Yaldabaoth **Dec 24** · false reality **~Jan 2, 2017** · reversion/"Day of Fates" **Feb 3** (the crossing). Subaru vanished **Dec 23, 2015**; Haru b. ~Dec 21, 2000. 2016 = Kiryu-era Kamurocho (Tojo era intact; Millennium Tower standing).

## 6. THE AUTHOR'S PREFERENCES (learned across sessions — honor them)

Fun-first, not miserable: dry snark, cool action, banter, wholesome romance. Corpus-first: adapt from the source material (donors cited per chapter in `03` §4 with file + line anchors; full corpus is at repo root as .txt files) — never generic AI prose. The author applies heavy show-don't-tell rewrites; drafts should invite that. The author approves each chapter. Dates: school-side beats pin to canon; yakuza/civilian-side dates flex within windows. The two-Harus collision is a running comedy bit that becomes genuine bond. Iwai is the P5/Yakuza border-crossing adult. Boss the cat outranks everyone.

## 7. BOOT PROMPT (the author pastes this into a fresh chat)

> Read planning/HANDOFF.md, planning/MASTER_DIRECTIVE.md, planning/DECISIONS_LOG.md, planning/STATUS.md first. This is the Haru Natsuki Saga; all state is in the repo. Then do: **[draft Chapter 1 v4.1 / draft Chapter 2 / review my attached Chapter N rewrite and update STATUS + commit / continue]**.

If the repo is NOT attached in the fresh chat: re-attach it (or `planning/` + `planning/chapters/` at minimum, plus the corpus .txt files if available — though production can proceed on the planning docs alone, since all donor material is quoted with anchors in `00_SOURCE_AUDIT.md`). A portable archive exists at `planning/HANDOFF_PACKAGE.zip`.

## 8. WHAT IS NOT IN THE REPO (known gaps)

- The author's Chapter 1 v4 text (old workspace). The treatment (`03` §7) replaces it if unavailable.
- The previous project's deep files (old `story-blueprint/` workspace) — its *conclusions* live in `transfer_pack.md`; the files themselves were never transferred.
- Nothing else. This file + the repo = the complete project state.
