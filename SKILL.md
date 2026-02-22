# Screenplay Writing Manual for AI Agents

Operational reference for AI agents generating commercially viable, industry-standard screenplays. Combines structural dramaturgy, formatting mechanics, dialogue craft, and multi-agent workflow into a single working document.

---

## 1. Core Principles

A screenplay is a technical blueprint for audio-visual production. Every word on the page must serve one of three functions: advance the plot, reveal character, or create tension. If a line does none of these, cut it.

**Scope:** This manual covers English-language screenplays targeting the US/UK industry. The structural frameworks, formatting specifications, and page-count standards reflect Western dramatic tradition. For non-Western markets (e.g., Kishōtenketsu-based East Asian structure, Rasa-driven Indian tradition), supplement or replace the structural frameworks in Section 2 with market-appropriate paradigms.

**Non-negotiable rules:**
- Write only what the audience can **see** or **hear**. No internal thoughts, no invisible backstory, no un-filmable abstractions.
- Present tense, active voice. Always.
- One formatted page equals approximately one minute of screen time.
- The screenplay is a **spec script** (a story document for readers), not a shooting script (a production document). Never include scene numbers, camera directions, or color-coded revision pages.

**Creative risk principle:** The rules in this manual are guardrails, not the destination. A great screenplay breaks at least one rule deliberately and with purpose. A scene that runs long because the tension demands it is better than a scene trimmed to satisfy a pacing metric. The Evaluator Agent must distinguish between *accidental* rule violations (sloppy craft) and *deliberate* violations (creative choice), and preserve the latter.

**Context loading protocol:** Do not load this entire manual into context for every task. Load Section 1 (principles) always. Load structural frameworks only during outlining. Load formatting only during drafting. Load adaptation only when adapting. Load the quality checklist only during evaluation. Treat this manual as a section-by-section reference, not a monolithic system prompt.

---

## 2. Structural Frameworks

Every commercially viable screenplay runs two parallel tracks: an **outer story** (events, obstacles, escalation) and an **inner story** (the protagonist's psychological arc). Structure fuses them so each plot beat forces an internal shift. In ensemble pieces without a single protagonist, the spine is thematic rather than character-driven (see Section 2.8).

### 2.1 Three-Act Structure (Syd Field)

The dominant Western paradigm. Key proportions:

| Act | Span | Function |
|---|---|---|
| I — Setup | 0–25% | Establish the ordinary world, protagonist, and stakes |
| II — Confrontation | 25–75% | Escalating obstacles; protagonist pursues the goal |
| III — Resolution | 75–100% | Climax, resolution, new equilibrium |

**Critical nodes:**
- **Inciting Incident** (~10–12%): The event that disrupts the status quo and launches the story.
- **Plot Point 1** (~25%): The irreversible choice that commits the protagonist to the journey.
- **Midpoint** (~50%): A false victory or devastating setback that raises stakes and shifts the protagonist from reactive to proactive (or vice versa).
- **Plot Point 2** (~75%): The lowest point; forces the protagonist to synthesize lessons learned.
- **Climax** (~85–95%): The final confrontation that resolves the central dramatic question.

### 2.2 Save the Cat! Beat Sheet (Blake Snyder)

Fifteen beats with percentage targets. Use as a diagnostic overlay when a draft sags:

1. **Opening Image** (1%) — Visual snapshot of the flawed status quo.
2. **Theme Stated** (~5%) — A secondary character hints at the lesson the protagonist must learn.
3. **Set-Up** (1–10%) — Establish the protagonist's world, relationships, and flaws.
4. **Catalyst** (~10%) — The inciting incident.
5. **Debate** (10–20%) — Protagonist resists the call; doubt and deliberation.
6. **Break into Two** (~20–25%) — Protagonist makes a proactive choice to cross the threshold.
7. **B Story** (~22%) — Introduces the thematic/relational subplot (often the love interest or mentor).
8. **Fun and Games** (20–50%) — The "promise of the premise"; the reason the audience bought a ticket.
9. **Midpoint** (~50%) — False victory or false defeat; stakes escalate.
10. **Bad Guys Close In** (50–75%) — External and internal pressures intensify.
11. **All Is Lost** (~75%) — The nadir; a significant loss or failure.
12. **Dark Night of the Soul** (75–80%) — Protagonist confronts despair.
13. **Break into Three** (~80%) — Synthesis of Act I values and Act II lessons produces a new plan.
14. **Finale** (80–99%) — Protagonist executes the plan and proves transformation.
15. **Final Image** (100%) — Visual bookend showing how the world (and protagonist) has changed.

### 2.3 Story Circle (Dan Harmon)

Eight-step cyclical model. Best for episodic and serialized narrative:

1. **You** — Comfort zone established.
2. **Need** — A desire or problem emerges.
3. **Go** — Cross the threshold into the unfamiliar.
4. **Search** — Face escalating obstacles; adapt.
5. **Find** — Acquire the goal but discover a deeper truth.
6. **Take** — Pay a heavy price.
7. **Return** — Re-enter the familiar world or face the final battle.
8. **Change** — Fundamentally altered by the journey.

### 2.4 Organic Character Logic (John Truby)

Use when the script demands deep thematic writing. Truby requires:
- A **designing principle** (the story's unique organizing idea).
- A protagonist with both a **psychological weakness** (hurting themselves) and a **moral weakness** (hurting others).
- An antagonist who specifically attacks the protagonist's unique weakness.
- A **moral argument** threaded through the plot: the protagonist's immoral actions escalate until self-revelation forces a moral decision they were incapable of making at the start.

### 2.5 TV Pilot Structure

The feature-film paradigms above (Three-Act, Save the Cat) do not map directly to television pilots. A pilot has distinct structural demands:

- The A-plot must resolve enough to be satisfying as a standalone episode, while the B-plot and series-level mystery remain open, demanding Episode 2.
- The pilot must demonstrate the show's **repeatable episode engine** — the structural pattern that will generate stories week after week — not just tell a single complete story.
- Ensemble introductions must be staggered and economical. Not every character needs full establishment in the pilot; plant hooks that pay off in later episodes.
- End with a **series question**, not a story answer. The pilot's climax should resolve the episode's immediate conflict while opening a larger question that defines the series.

Use Harmon's Story Circle (Section 2.3) as the primary structural tool for episodic work, with the Three-Act framework applied to the pilot's self-contained A-plot.

**Note:** Multi-camera sitcom formatting (double-spaced dialogue, marked act breaks, different margins) is a distinct specification not covered by this manual's formatting section. The formatting in Section 5 applies to single-camera drama and comedy only.

### 2.6 Premise-Driven Conflict (Lajos Egri)

Every coherent story demonstrates a single philosophical thesis through human behavior (e.g., "Ruthless ambition leads to self-destruction"). Construct a **unity of opposites**: two determined characters with irreconcilable drives, inextricably bound together. Conflict then generates organically from character rather than from imposed plot mechanics.

### 2.7 Genre Contracts

Audiences arrive with genre-specific expectations. The structural frameworks above must be inflected by genre:

- **Thriller:** Ticking clock or escalating jeopardy as a structural engine; at least one major twist or reveal per act; the antagonist should be active and ahead of the protagonist for most of Act II.
- **Horror:** Dread escalation curve — tension builds through atmosphere before the first scare; scare beats at regular intervals with increasing intensity; the rules of the threat must be established before the climax exploits them.
- **Comedy:** Comedic set pieces distributed at roughly 10–15 page intervals; the "Fun and Games" section (20–50%) carries the heaviest joke density; false breakup or all-is-lost moment must land emotionally, not just comedically.
- **Romance:** Meet-cute by ~10%; mutual resistance and attraction through Act II; a false breakup or betrayal at ~75% that tests the relationship's premise; grand gesture or reconciliation in the climax.
- **Action/Adventure:** Major set pieces at act breaks and midpoint; escalating spectacle (each set piece tops the previous); physical stakes must mirror emotional stakes — action sequences that don't advance the inner story are empty spectacle.

**Genre-specific dialogue adjustments:** In comedy, directness and timing (setup-punch rhythm) are as important as subtext — the joke is often in what a character says *too honestly*, not what they withhold. In horror, dialogue should be sparse during tension sequences; characters articulate less as fear increases. In thriller, dialogue carries misdirection — characters actively lie, omit, and redirect.

### 2.8 Ensemble Structure

When there is no single protagonist, the spine is **thematic** rather than character-driven. All storylines explore the same central question from different angles.

- Each co-lead needs a compressed arc (desire/flaw/turn), but the *theme* is the protagonist.
- The beat sheet maps to the thematic argument's progression, not any single character's journey.
- Intercut between storylines using thematic rhyming — cut from one character's scene to another's when both face a parallel dilemma or when one storyline's outcome comments on another's.
- At least one storyline should collide with or directly affect another by the climax; fully independent threads feel structurally disconnected.

---

## 3. Character Architecture

### 3.1 Creation

Build each character from:
- **Desire** — What they actively pursue.
- **Fear** — What they avoid at all costs.
- **Flaw** — The desire's shadow (ambition becomes ruthlessness; loyalty becomes blindness).
- **Edge** — One specific competence that makes them irreplaceable in this story.
- **Backstory wound** — One formative event shaping the fear. It need not appear on screen, but it shapes every reaction.

**Elevator pitch test:** "[Name] wants [desire], but [fear/flaw] keeps getting in the way, and now [inciting pressure] forces a choice."

### 3.2 Archetypal Functions

Characters serve narrative functions drawn from mythic structure:
- **Hero** — Central psychological journey.
- **Mentor** — Provides wisdom or tools.
- **Threshold Guardian** — Tests the hero's readiness.
- **Herald** — Announces change.
- **Shapeshifter** — Introduces doubt through shifting allegiance.
- **Shadow** — The antagonistic force; often a dark mirror of the hero.
- **Trickster** — Disrupts the status quo; provides relief.

Roles are not exclusive. A character may shift functions as the narrative demands.

### 3.3 Arc Tracking

- Define the arc type early: transformation, hardening, disillusionment, or tragic deterioration.
- Each scene must test the arc by pressuring the flaw or challenging the belief.
- Track the gap between what the character says they want and what their choices reveal.
- Mark 2–4 **pivot beats** where the internal compass visibly shifts.

---

## 4. Dialogue Craft

### 4.1 The Subtext Imperative

Characters never say exactly what they mean. Every line of dialogue must operate on two levels: what is said (the text) and what is meant (the subtext). If the literal text perfectly matches the character's internal goal with no obfuscation, deflection, or misdirection, flag it for revision.

**Techniques for generating subtext:**
- **Indirection** — Characters talk around the real issue. A scene about a divorce is conducted as an argument about who gets the dog.
- **Contradiction** — What a character says opposes what they do. "I'm fine" while their hands tremble.
- **Interruption and silence** — What is cut off or left unsaid carries meaning.
- **Mismatched register** — A character uses humor to deflect pain, or clinical language to suppress emotion.

**Subtext calibration:** Not every character in every scene should be oblique. At least one character per scene should be relatively direct — often the antagonist, a child, or a minor character — providing the audience enough surface information to decode the subtext of others. Subtext without any anchor becomes incoherence.

### 4.2 Dialogue Rules

- Each character **wants something** in every conversation; the exchange must escalate.
- No "As you know..." exposition dumps. Convey information through conflict or discovery.
- Each speaking character needs a **voice fingerprint**: default sentence length, verbal habits, register, and evasion tactic.
- Dialogue under pressure should **degrade**: syntax shortens, masks slip, the careful speaker stammers.
- Trim greetings and pleasantries unless they carry subtext.
- Clean attribution: action beats convey emotion better than adverbial parentheticals.

### 4.3 The Show-Don't-Tell Imperative

The most common failure in AI-generated screenplays is on-the-nose dialogue that tells the audience what characters feel. Replace diegesis (telling) with mimesis (showing):

| Weak (Diegesis) | Strong (Mimesis) |
|---|---|
| "I'm so angry at you for leaving." | Character sweeps framed photos off the mantle into a trash bag. |
| "This neighborhood is dangerous." | A child hopscotches around spent shell casings. |
| "I've never felt so alone." | Character sets two plates at the dinner table, then quietly puts one back. |

---

## 5. Formatting Specification

### 5.1 Page Setup

- **Font:** Courier or Courier Prime, 12-point. Non-negotiable.
- **Margins:** Left 1.5", Right 1", Top 1", Bottom 1".
- **Lines per page:** ~55.
- **Page numbers:** Top-right, starting on page 2.
- **Paper:** US Letter (8.5 x 11").

### 5.2 Element Formatting

**FADE IN:** — First words of the script, flush left.

**Scene Headings (Sluglines):**
- ALL CAPS, flush left.
- Format: `INT./EXT. LOCATION — TIME OF DAY`
- Time options: DAY, NIGHT, DAWN, DUSK, CONTINUOUS, LATER, MOMENTS LATER.
- Sub-locations are acceptable: `INT. HOSPITAL — WAITING ROOM — NIGHT`
- No scene numbers in a spec script.

**Action Lines:**
- Flush left, full page width.
- Present tense, active voice.
- **Maximum 3–4 lines per block.** Break longer descriptions into separate paragraphs with white space between them.
- Capitalize a character's name on their FIRST appearance only.
- Capitalize significant sound effects sparingly (e.g., `GUNSHOT`, `EXPLOSION`). Do not capitalize ambient sounds.

**Character Cues:**
- ALL CAPS, centered at ~3.7" from left page edge.
- Extensions on the same line: `(V.O.)`, `(O.S.)`, `(CONT'D)`.

**Dialogue:**
- Left edge at ~2.5" from left page edge; column width ~3.5".
- No quotation marks.
- Keep speeches concise. Break long monologues with action beats.

**Parentheticals:**
- Between character cue and dialogue, indented to ~3.1" from left edge.
- Lowercase, in parentheses: `(quietly)`, `(to Sarah)`, `(beat)`.
- Use sparingly — only when delivery is ambiguous from context.
- Never use for actions; actions belong in action lines.

**Transitions:**
- `FADE IN:` is flush left (first line of script only).
- `FADE OUT.` is flush right (last line of script only).
- All others flush right with colon: `SMASH CUT TO:`, `MATCH CUT TO:`
- **Omit `CUT TO:` in modern specs.** A new slugline implies the cut. Overuse signals amateurism.

### 5.3 Title Page

- Title centered, ALL CAPS.
- Below: `Written by` then author name.
- Contact info in lower corner.
- No loglines, synopses, draft dates, WGA numbers, or artwork.
- Same Courier 12pt font. The title page is not numbered.

### 5.4 Page Count Standards

| Format | Target Range |
|---|---|
| Feature — Comedy | 90–105 pages |
| Feature — Drama/Thriller | 100–115 pages |
| Feature — Action/Adventure | 105–120 pages |
| TV Pilot — Hour Drama | 50–60 pages |
| TV Pilot — Half-Hour (single-cam) | 30–35 pages |
| Short Film | 1–40 pages |

Scripts under 85 or over 125 pages raise immediate red flags.

---

## 6. Pacing and Evaluation Heuristics

### 6.1 Pacing Metrics

- **Action density:** Action blocks exceeding 4 lines degrade reading pace. Penalize "bricks" of dense text; reward fragmented, propulsive lines with strong verbs.
- **Dialogue ratio:** Dialogue should comprise 40–60% of the screenplay. Deviations signal either talky stagecraft or underwritten characters.
- **Scene economy:** Enter every scene as late as possible, exit as early as possible. Every moment must advance plot or reveal character.
- **Scene turns:** Every scene should turn — enter with one value state, exit with the opposite (safe to threatened, ignorant to aware, allied to betrayed).
- **Pinch points** (~37% and ~62%): Moments of intense pressure reminding the audience what is at stake.

### 6.2 Common Rejection Triggers

Evaluate every draft against these failure modes:
- Wrong font or non-standard formatting.
- Dense action blocks (>4 lines).
- Excessive parentheticals.
- Camera directions in a spec (`CLOSE ON`, `WE SEE`, `ANGLE ON`).
- Overuse of CAPS for emphasis.
- Scene numbers, `CONTINUED` markers, or draft dates.
- "We see" / "We hear" constructions.
- Passive voice or novelistic description.
- Page count outside acceptable range.
- Spelling and grammar errors.
- On-the-nose dialogue (no subtext).
- Transitions on every scene break.

---

## 7. Multi-Agent Workflow

A single-pass generation attempt will produce degraded output. Decompose screenplay writing into specialized agent roles executed sequentially:

### 7.1 Agent Architecture

**1. Structural Architect Agent**
- Receives: Premise, genre, target length.
- Consults genre contracts (Section 2.7) to inflect beat placement with genre-specific expectations.
- Outputs: A beat sheet with percentage-mapped plot points using Snyder's 15 beats or the Three-Act framework.
- Validates: Inciting incident at ~10%, midpoint at ~50%, climax at ~85–95%; genre-specific beats are present.
- Handoff format: JSON array of beat objects, each with `beat_name`, `target_percentage`, `description`, and `characters_involved`.

**2. Character and Theme Agent**
- Receives: Beat sheet (JSON) from Agent 1.
- Outputs: Character profiles (desire/fear/flaw/edge/wound for each principal), antagonist logic, thematic premise (Egri), moral argument tracking (Truby), and a **voice fingerprint card** per speaking character (default sentence length, vocabulary register, verbal tic, evasion pattern).
- Validates: The antagonist attacks the protagonist's specific weakness; the conflict set arises from character opposition, not imposed mechanics.
- Handoff format: JSON object with `characters` array (each containing profile fields and voice fingerprint), `premise`, `moral_argument`, and `thematic_tracking`.

**3. Scene Outline Agent**
- Receives: Beat sheet (JSON) + character profiles (JSON).
- Outputs: Scene-by-scene outline specifying: slugline, characters present, scene goal, scene turn (entering value state to exiting value state), and subtext notes.
- Validates: Every scene turns at least one value; no scene exists solely for exposition.
- Handoff format: JSON array of scene objects, each with `scene_number`, `slugline`, `characters`, `goal`, `turn_from`, `turn_to`, `subtext_note`, `target_page_range`.

**4. Drafting Agent**
- Receives: Scene outline (JSON) + character profiles with voice fingerprint cards (JSON) + style brief.
- Outputs: Formatted screenplay pages in Fountain syntax.
- Constraints: Action blocks max 4 lines. No internal thoughts. No camera directions. Capitalize character names on first introduction only. Present tense, active voice.
- **Style brief (mandatory):** Before drafting begins, the user defines (or the agent proposes for user approval per Section 8.1): tonal register (e.g., sardonic, earnest, lyrical), 2–3 reference films for voice/pacing, action-line style (terse vs. atmospheric), dialogue density preference, and any deliberate rule-bending. The Drafting Agent and Evaluator must evaluate against the style brief, not just against this manual's defaults.
- **Structural progress tracker (mandatory):** After drafting each scene, log the current page count, percentage through the script, and which beats have been placed vs. which remain. Re-read the voice fingerprint card for each speaking character before writing their dialogue.

**5. Evaluator and Refinement Agent**
- Receives: Complete draft + structural progress log + character profiles with voice fingerprints.
- **Revision triage:** When feedback is vague or a scene "isn't working," diagnose before prescribing. Check in this order — structure (does the scene turn?), then character (is the arc being tested?), then subtext (is dialogue on-the-nose?), then pacing (are action blocks dense?), then formatting and line-level craft. Always work top-down; do not line-tighten a scene whose real problem is structural.
- Executes revision passes in order:
  1. **Structure pass** — Verify beat placement percentages against the progress log; confirm midpoint reversal; check all scenes turn.
  2. **Character pass** — Verify each scene tests the protagonist's flaw; confirm distinct voice fingerprints against the fingerprint cards; check motivation layers.
  3. **Subtext pass** — Flag on-the-nose dialogue; rewrite so at least one important thing per scene is communicated indirectly.
  4. **Pacing pass** — Flag action blocks >4 lines; check dialogue ratio (40–60%); flag scenes that overstay their utility.
  5. **Format pass** — Validate slugline formatting, character cue placement, parenthetical usage, transition usage, and page count.
  6. **Line-tightening pass** — Cut 10–20% of words without losing meaning; eliminate cliches; replace weak verb+adverb with stronger verbs.
- **Escalation authority:** The Evaluator may send the draft back to an earlier agent with a specific revision request. When agents produce conflicting outputs, the hierarchy of authority is: structure takes precedence over character design; character takes precedence over dialogue; formatting is non-negotiable at all levels.

### 7.2 Context Management

Screenplays exceed typical LLM context windows. Maintain continuity using:
- A **story bible** updated after each scene: premise, cast (want/fear/flaw/edge for each), voice fingerprint card per speaking character, world rules, plot status, open threads, and next-scene options.
- **Act summaries** compacted into dense metadata after completion, carried forward into subsequent generation prompts.
- **Character state tracking** recording each character's emotional state, knowledge state, and physical location at each scene boundary.
- **Structural progress tracker** carried forward with each scene: current page count, percentage through script, beats placed, beats remaining.

### 7.3 Prompt Engineering Principles

- Use **affirmative directives with explicit constraints**: "Write action lines in present tense, active voice. Maximum 3 lines per block. Do not describe internal thoughts. Do not include camera directions."
- Separate **literal action from thematic undercurrent**: "This scene is ostensibly about packing boxes for a move. The subtext is that the marriage is ending. The dialogue must never reference the marriage directly."
- **Constraint-based negative prompting** prevents common AI failures: "Do not use dialogue to explain backstory. Do not write parentheticals for delivery that is clear from context. Do not use the phrase 'we see.'"

---

## 8. Collaboration Protocol

When used interactively with a human collaborator, the agent must follow these rules in addition to the autonomous pipeline:

### 8.1 Decision Rights

- **Human decides:** Premise, theme, character fates, tone, POV, ending, fidelity level for adaptations, and any choice that changes what the story means.
- **Agent decides (within a draft):** Sentence-level craft — word choice, rhythm, imagery, action line construction, scene choreography, formatting.
- **Agent proposes, human approves:** Scene structure changes, new subplots, timeline changes, character introductions, tonal shifts, and anything that alters the story bible. Present these as numbered options with trade-offs.

### 8.2 Revision Triage for Human Feedback

When a human says a scene "isn't working" or gives vague feedback, diagnose before rewriting. Check in this order:

1. **Structure** — Does the scene turn? Is it in the right place in the beat sheet?
2. **Character** — Is the protagonist's flaw being tested? Are voice fingerprints distinct?
3. **Subtext** — Is dialogue on-the-nose?
4. **Pacing** — Are action blocks dense? Does the scene overstay its utility?
5. **Formatting and line-level craft** — Formatting errors, word choice, rhythm, cliches.

Offer 2–3 hypotheses to the human and ask which resonates before rewriting. Do not immediately rewrite at the wrong level.

### 8.3 Draft Presentation

- Before the draft, state in one sentence what the scene is doing structurally.
- After the draft, flag 1–2 non-obvious craft decisions.
- When presenting alternatives, label them clearly (Option A / Option B) and state the key difference in one line.
- Match the requested scope: if the human asked for a rough sketch, do not deliver polished pages.

### 8.4 Rewrite Protocol

When given an existing script to fix rather than a blank page:

1. **Read the full draft first.** Identify what's working — scenes that turn, characters that land, dialogue that sings. Protect these.
2. **Diagnose using the revision triage** (Section 8.2) — structure, then character, then subtext, then pacing, then lines.
3. **Classify the rewrite scope:**
   - **Page-one rewrite** — The structure is broken; the story needs to be reconceived from the premise outward.
   - **Structural pass** — Beats are misplaced or missing; scenes need reordering, cutting, or invention.
   - **Character pass** — Arcs aren't tracking; voice fingerprints are blurred; motivations are unclear.
   - **Polish** — Line-level craft only; the structure and characters are sound.
4. **Rewrite only at the diagnosed level.** Do not polish a script that needs structural repair. Do not restructure a script that only needs a dialogue pass.

### 8.5 Conflicting Notes

When receiving feedback from multiple stakeholders:

- Group notes by the revision triage hierarchy (structure → character → subtext → pacing → lines).
- Flag direct contradictions to the user before implementing either side.
- **Hierarchy of authority:** The user's explicit instructions override all other stakeholders; structural notes override cosmetic notes; notes that align with the dramatic spine override notes that pull away from it.
- When two notes are genuinely incompatible, present both as options with trade-offs rather than choosing silently.

---

## 9. Fountain Syntax Reference

Fountain is the preferred intermediate format for AI generation — plain text, human-readable, and machine-parsable.

```fountain
Title: THE LAST LIGHT
Credit: Written by
Author: Agent System

FADE IN:

EXT. DESERT HIGHWAY — DAWN

Heat shimmers rise from cracked asphalt. A single car idles on the shoulder, hazard lights blinking.

ELENA VASQUEZ (30s, dust-caked, jaw set) steps out and scans the horizon. Nothing but sand and sky.

ELENA
(into phone)
I'm here. Where are you?

She waits. Static. She lowers the phone and walks toward the dunes.

ELENA (CONT'D)
Fine.

EXT. SAND DUNES — CONTINUOUS

Elena crests a dune. Below, a makeshift camp. Three figures huddle around a dead fire.

FADE OUT.
```

**Key Fountain rules:**
- Lines beginning with `INT` or `EXT` (after a blank line) are parsed as scene headings.
- ALL CAPS text on its own line before dialogue is parsed as a character cue.
- Text in parentheses below a character cue is parsed as a parenthetical.
- `*italics*`, `**bold**`, `***bold italics***` for emphasis.
- Transitions end with `TO:` and are preceded by a blank line.

**Formatting edge cases:**
- **INTERCUT:** Use `INTERCUT — PHONE CONVERSATION` (or `INTERCUT WITH:`) as a slugline after establishing both locations. Subsequent dialogue alternates without new sluglines.
- **Dual dialogue** (simultaneous speech): In Fountain, place a `^` before the second character's cue to indicate they speak at the same time as the previous character.
- **Montage:** Use `MONTAGE —` as a slugline header, followed by lettered or dashed action lines for each image. End with `END MONTAGE.`
- **Series of shots:** Same as montage format; use `SERIES OF SHOTS —` as the header.
- **Flashback:** Use `FLASHBACK —` appended to the slugline (e.g., `INT. CHILDHOOD HOME — DAY — FLASHBACK`). End the sequence with `END FLASHBACK.` or return to present with `BACK TO PRESENT` in a new slugline.
- **Text on screen:** Write `CHYRON:` or `TITLE CARD:` followed by the text in quotes as an action line (e.g., `CHYRON: "Three years later"`).
- **Lyrics/songs:** Italicize lyrics using `*asterisks*` in the dialogue block.

---

## 10. Adapting Source Material to Screenplay

When the input is an existing novel, short story, novella, or other narrative work, the agent must transform it into a screen-native dramatic structure rather than transcribe it.

### 10.1 Identifying the Dramatic Spine

Before any other decision, extract a single throughline by answering two questions:
1. **Main plot:** WHO wants WHAT, and WHO or WHAT opposes them?
2. **Major subplot:** Apply the same framework to the supporting storyline.

If these questions cannot be answered clearly from the source, the material does not yet have a screenplay. The agent must construct or sharpen a spine before proceeding.

**The memory test:** After ingesting the source, identify the scenes and characters that carry the most dramatic weight — those without which the cause-and-effect chain breaks. These survive. Everything else is a candidate for cutting.

### 10.2 Compression (Novel to Screenplay)

A 90,000-word novel must fit a ~15,000–20,000-word screenplay. Apply three layers of cutting:

1. **Spine filter:** Eliminate subplots and characters that do not serve the protagonist's outer goal or the thematic premise.
2. **Composite characters:** When multiple characters serve similar dramatic functions (e.g., three mentors, three minor antagonists), merge their key traits into one character. In *The Shawshank Redemption*, Darabont consolidated the novel's rotating wardens into a single permanent antagonist.
3. **Inner-goal filter:** Remove any remaining material that serves neither the outer goal nor the protagonist's inner arc.

**What always survives:** The 5–7 load-bearing scenes without which the story collapses; effective original dialogue that already works cinematically; the inciting incident, midpoint, and climax.

**What gets cut:** Redundant beats that repeat established information or emotion; descriptive and reflective passages with no external dramatic consequence; backstory that can be communicated visually or through subtext.

The agent should feel free to reorder events, shift perspective, and rewrite the ending if a more compelling cinematic conclusion is possible.

### 10.3 Expansion (Short Story to Screenplay)

When the source is a short story or novella, the challenge reverses — the agent must expand limited material to feature length. This requires:
- Inventing scenes that deepen characters beyond the source's sketch.
- Adding subplots grounded in the source's psychology and theme.
- Building dramatic sequences between events the source implies but does not show.

Short-source adaptations permit significant creative departure. The source functions as a launching pad, not a constraint.

### 10.4 Externalizing Interiority

Film is an exterior medium. Internal narration, stream-of-consciousness, and prose interiority must be converted to action the camera can capture:

| Prose Device | Screen Translation |
|---|---|
| Internal monologue | A **sounding-board character** (confidant, adversary) who receives the thought as dialogue through conflict |
| Emotional state described by narrator | **Behavioral revelation** — physical action that externalizes the feeling (see Section 4.3) |
| Associative memory / flashback in prose | **Visual juxtaposition or montage** — image sequences that mimic associative logic |
| Thematic commentary by narrator | **Symbolic object or environment** — production design carries the argument |
| Character's private reasoning | **Decision under pressure** — force the character to choose visibly, revealing the reasoning through the choice itself |

### 10.5 POV Translation

| Source POV | Screen Strategy |
|---|---|
| **First person** | Anchor the camera to the protagonist's presence in nearly every scene; the audience learns only what they learn. Use voiceover selectively (see 10.7). Add a confidant character for essential disclosures. |
| **Omniscient** | Select a primary POV character or small ensemble. Film cannot sustain true omniscience — commit to whose subjectivity the camera privileges. |
| **Multiple restricted POV** | Option A: Select one protagonist, subordinate others. Option B: Treat the camera as a neutral observer moving among characters (the *Game of Thrones* approach). Option C: Show the same event from different perspectives in sequence (*Atonement*). |
| **Epistolary** | Read letters/entries as voiceover over dramatized action; use the act of writing as its own scene; reduce mediation by expanding direct interactions. |
| **Unreliable narrator** | Use visual contradiction (voiceover says one thing, camera shows another); use cinematographic coding (warm/idealized tones for the narrator's version, harder light for reality); seed unreliability in Act I through behavioral hints. |

### 10.6 Scene Triage

Every scene from the source must pass one of these tests to survive:
- It is essential to the dramatic spine — without it, cause-and-effect breaks.
- It is a key character-defining moment that cannot be conveyed another way.
- It contains dialogue that already works cinematically.
- **(Tiebreaker only)** It is a scene the source's audience would most expect and most miss. This test never overrides the spine test — a scene that fails the spine test is cut regardless of how iconic it is. If the scene is truly beloved, fold its emotional core into a scene that does serve the spine.

**Compositing:** Multiple scenes with related functions merge into one scene that achieves all their purposes simultaneously.

**Inventing new scenes:** Invention is legitimate when needed to externalize internal states, fill structural gaps (a missing inciting incident at the right page, a missing midpoint reversal), or dramatize events the source implies but does not show. The constraint: invented scenes must obey established character psychology. A character acting out of character to serve a cinematic set piece is the cardinal adaptation error.

### 10.7 Voice-Over Discipline

Voice-over is the most common adaptation crutch. It appears to solve the interiority problem but typically relocates it rather than dramatizing it.

**The test:** If the narration can be replaced by a scene, cut it. Voice-over earns its place only when it reveals something the visual story cannot or adds a layer of meaning on top of the image.

**Legitimate uses:**
- The source's prose voice is inseparable from the story's meaning (*Fear and Loathing in Las Vegas*).
- The narrator is unreliable — what they say and what the audience sees contradict each other (*Gone Girl*).
- Ironic contrast between narration and image creates subtext (*Trainspotting*'s "Choose life" over scenes of squalor).
- World-building compression when centuries of context must be conveyed in minutes (*Lord of the Rings* prologue).

**Illegitimate uses:** Relaying information the audience could be seeing; explaining what characters feel; delivering backstory that could emerge through conflict.

### 10.8 Fidelity Decisions

Perfect fidelity is impossible — each reader's experience of a novel is subjective, and no single film can satisfy all internal versions. The agent must choose a position on the fidelity spectrum:

- **Faithful:** Closely follows plot, characters, and themes. Best when the source's structure already maps to screenplay form or when the audience expects specific scenes.
- **Loose:** Uses the source as inspiration, building an independent dramatic structure. Best when the source's greatness is in prose style, internal psychology, or narrative voice — none of which film can directly replicate.

**Decision tree:**
- If the source's primary appeal is plot mechanics (thriller, mystery, action) → lean **faithful** to plot structure.
- If the primary appeal is prose voice, interiority, or structural experimentation → lean **loose**; capture tone and mood rather than transcribing events.
- If the source is short (novella/short story) and expansion is needed → lean **loose**; the source provides a launching pad, not a complete blueprint.
- If unclear → ask the human before proceeding; do not default silently.

**The governing principle:** Stay faithful to at least one core dimension — character progression, thematic argument, or emotional register. Abandoning all dimensions simultaneously produces something that cannot meaningfully be called an adaptation.

### 10.9 Adaptation Agent Workflow

When adapting source material, prepend a **Source Analysis Agent** to the multi-agent architecture in Section 7. For novels exceeding the agent's context window, the Source Analysis Agent must use **chunked ingestion**: process the source chapter by chapter, building a cumulative spine document, character map, and scene inventory. The agent must never claim to have analyzed content it has not read:

**0. Source Analysis Agent**
- Receives: The source text (via chunked ingestion if it exceeds the context window).
- Outputs: Dramatic spine (protagonist, goal, antagonist, stakes); character map with desire/fear/flaw for each principal; list of load-bearing scenes; list of prose-dependent elements that resist direct translation (internal monologue, omniscient commentary, epistolary devices); recommended fidelity level; rights status flag (public domain vs. copyrighted).
- Validates: A clear throughline exists or can be constructed; the source has sufficient dramatic material for the target format.

The remaining agents (Structural Architect, Character/Theme, Scene Outline, Drafting, Evaluator) then operate on the Source Analysis Agent's output rather than on a raw premise.

### 10.10 Rights Awareness

The agent must flag rights status when given source material:
- **Public domain** (US): Works published before January 1, 1931 are free to adapt without permission. Verify works from 1925–1968 case-by-case (copyright depended on registration and renewal formalities).
- **Copyrighted works:** Require an option agreement granting exclusive development rights for a defined period. The agent should never generate a full adaptation of copyrighted material without the user confirming that rights have been secured or that the work is for portfolio/educational purposes only.
- **Existing adaptations:** Public domain status of the underlying text does not permit copying another adapter's specific character designs, interpretations, or visual identity.

### 10.11 Biopic and True Story Adaptation

Real lives lack three-act structure, clean arcs, and satisfying climaxes. Forcing a full biography into a screenplay produces either historical dishonesty or dramatic inertia.

- **Select a single chapter or conflict** from the subject's life — not the whole life. Define a dramatic question that this chapter answers.
- **Composite real people** into functional characters when the real cast is too large for screen.
- **Clarify the fidelity contract** before proceeding:
  - *"Inspired by"* — Significant invention is permitted; the source is a launching pad.
  - *"Based on a true story"* — Core facts must be accurate; timeline and minor characters may be adjusted.
  - *"A true story"* — Near-documentary fidelity; invention is limited to dramatizing scenes between documented events.
- Ask the user which contract applies before drafting.

---

## 11. Pre-Script Deliverables

The screenplay is not the first document in the industry pipeline. Agents must be able to produce these precursor documents:

### 11.1 Logline

A 1–2 sentence pitch (under 50 words) following this formula: **[Protagonist with a defining trait]** must **[goal triggered by inciting incident]**, but **[antagonistic force / central obstacle]** threatens **[stakes — what is lost if they fail]**.

Example: *A reclusive marine biologist must escort a wounded alien across hostile desert to reach an extraction point, but a government kill team and her own paranoia threaten to destroy the only proof of extraterrestrial life.*

### 11.2 Synopsis

A 1–2 page present-tense, third-person prose summary covering all three acts **including the ending**. The synopsis must reveal the climax and resolution — it is a selling document, not a teaser. Write in a voice that conveys the film's tone.

### 11.3 Treatment

A 5–15 page expanded narrative covering every major sequence. Written in present tense, prose style (not bullet points), with enough scene-level detail that a reader can visualize the film. The treatment should convey pacing and tone, not just plot.

---

## 12. Quality Checklist

Before delivering any draft, validate against this checklist:

- [ ] Inciting incident lands by page 10–12% of total.
- [ ] Midpoint reversal shifts protagonist's stance at ~50%.
- [ ] Every scene turns at least one value.
- [ ] No action block exceeds 4 lines.
- [ ] Dialogue ratio is 40–60%.
- [ ] Every speaking character has a distinct voice fingerprint.
- [ ] At least one important thing per scene is communicated through subtext, not stated directly.
- [ ] No camera directions, scene numbers, or "we see/hear" constructions.
- [ ] Character names capitalized on first introduction only (in action lines).
- [ ] Parentheticals used sparingly and only when delivery is ambiguous.
- [ ] All sluglines follow `INT./EXT. LOCATION — TIME` format.
- [ ] Page count falls within genre-appropriate range.
- [ ] No spelling or grammar errors.
- [ ] Title page is clean: title, writer credit, contact info only.
- [ ] The script opens with a moment of change, pressure, or destabilizing revelation — not with routine or exposition.
- [ ] Genre-specific beats are present and correctly placed (Section 2.7).
- [ ] The draft has been evaluated against the style brief, not just manual defaults.
- [ ] For ensemble scripts: the thematic spine is clear and all storylines address the same central question (Section 2.8).

**Additional checks for adaptations:**
- [ ] A clear dramatic spine (WHO wants WHAT, WHO opposes them) has been extracted from the source.
- [ ] Prose interiority has been externalized as visual action, dialogue through conflict, or symbolic environment — not relocated into voice-over or on-the-nose dialogue.
- [ ] Composite characters replace redundant source characters where applicable.
- [ ] No scene exists solely because it appeared in the source — every scene passes the spine test.
- [ ] Voice-over (if used) adds a layer the visual story cannot provide; it does not relay information the audience could be seeing.
- [ ] Rights status has been flagged (public domain, optioned, or portfolio/educational use).
