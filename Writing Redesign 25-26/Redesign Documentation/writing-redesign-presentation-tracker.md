# PROJECT: Writing Redesign Presentation Prep
**Type:** curriculum | **Phase:** planning | **Updated:** 2025-01-29T14:30:00Z

---
**⚠️ MANDATORY CLAUDE PROTOCOL - NO EXCEPTIONS ⚠️**

**EVERY RESPONSE - START:**
1. Increment response counter in Layer 4.5
2. If response count ≥ 4 since last skill re-read: READ `/mnt/skills/user/project-markdown-tracker/SKILL.md` first
3. READ this entire tracker file from top to bottom
4. If first time reading this file in current chat: read skill project-markdown-tracker
5. NEVER skip reading - project state is here

**EVERY RESPONSE - END:**
1. UPDATE this file with all changes (Layer 0-4.5)
2. UPDATE `/mnt/project/writing-redesign-presentation-tracker.md` with str_replace tool
3. PRESENT link only: [View project tracker](computer:///mnt/project/writing-redesign-presentation-tracker.md)

**CRITICAL:**
- Layer 0 = Mutable with versioning. Version all changes to preferences/constraints/decisions with timestamp + reason
- Layer 4.5 = Track response count. Trigger skill re-read every 4th response to prevent context drift
- If tracker not read → you're working blind → ALWAYS READ FIRST
- If tracker not updated → context lost forever → ALWAYS UPDATE LAST
---

## 🔴 LAYER 0 [LOCKED CHANGELOG - MUTABLE WITH VERSIONING]

### Project DNA
**Goal:** Prepare 30-minute presentation on Writing course redesign for team leaders (Jan 30, 2025)
**Done When:** Presentation structure finalized, key arguments clear, Q&A format drafted, decision points identified
**Scope:** In:[W1, W2, W3 assessment redesign, Lane 1/2 framework, Presentation+Q&A format, logistics] | Out:[Detailed rubric wording, lesson planning, Canvas setup]

### User Preferences [MUTABLE - VERSION ON CHANGE]
**Changelog:** 
- 2025-01-29T14:30: Initial preferences set from conversation

**PREF_001:** key="framing" | val="validity focus, NOT cheating detection" | v:1 | set:2025-01-29 | affects:[all messaging]
**PREF_002:** key="presentation_tone" | val="input-seeking, not approval-seeking" | v:1 | set:2025-01-29 | affects:[presentation framing]
**PREF_003:** key="rubric_style" | val="at level / above level / not yet at level (no numeric grades)" | v:1 | set:2025-01-29 | affects:[assessment design]

### User Constraints [MUTABLE - VERSION ON CHANGE]
**CONST_001:** must_use="30 minutes max presentation time" | reason:"meeting format" | affects:[content depth] | set:2025-01-29
**CONST_002:** must_avoid="framing as anti-cheating measure" | reason:"authorship validity is the point" | affects:[all messaging] | set:2025-01-29
**CONST_003:** must_use="cross-grading between FT/PT teachers" | reason:"solves DT logistics" | affects:[logistics section] | set:2025-01-29

### Foundation Decisions [MUTABLE - VERSION ON CHANGE]

**DEC_001** [v1 | ACTIVE] - Course Structure
- **What:** W1 = timed test + take-home + P+Q&A | W2 = take-home + P+Q&A (no timed) | W3 = timed test + take-home + P+Q&A
- **Why:** W1 validates propedeutic level (B1/B2), W3 validates CPE readiness (C1/C2), W2 is bridge focusing on strategy awareness
- **Rejected:** All three with timed tests (unnecessary for W2), W2 keeping current format (validity concerns with creative mimicry)
- **Impacts:** All course toetsplannen, teacher training, scheduling
- **Set:** 2025-01-29

**DEC_002** [v1 | ACTIVE] - Timed Test Format
- **What:** W1 = 60 min, 2 sources, ~2 paragraphs | W3 = 90 min, 3 sources, ~3 paragraphs
- **Why:** Quality over quantity; increased sources/time at W3 shows progression while keeping word count manageable
- **Rejected:** Longer word counts (grading burden), identical formats across courses (no progression)
- **Impacts:** Test design, rubric criteria, time allocation
- **Set:** 2025-01-29

**DEC_003** [v1 | ACTIVE] - W3 Take-Home Genre
- **What:** Student choice: Proposal OR Creative piece (Mystery vs Personal Essay)
- **Why:** Formal style covered in timed test + other programme parts; creative valued in current course; choice increases engagement
- **Rejected:** Proposal only (loses valued creative element), Creative only (less professional skill practice)
- **Impacts:** W3 assignment description, P+Q&A criteria need genre-specific elements
- **Set:** 2025-01-29

**DEC_004** [v1 | ACTIVE] - Presentation + Q&A is Lane 1
- **What:** P+Q&A component is the secured assessment; take-home writing is Lane 2 (not directly assessed for validity)
- **Why:** Live oral defense validates authorship; take-home is vehicle for demonstrating strategy application
- **Rejected:** Treating take-home as Lane 1 (cannot validate), treating P+Q&A as separate from Lane 1 (misunderstands framework)
- **Impacts:** How we explain the model, rubric weighting
- **Set:** 2025-01-29

**DEC_005** [v1 | ACTIVE] - Source Selection Removed from Assessment
- **What:** Source selection not assessed in summative test; students receive sources (W1/W3 timed) or use self-found for take-home but this isn't the validity focus
- **Why:** Source selection is research skill (covered elsewhere); cannot validate anyway in unsecured context; W3 learning outcomes are being revised
- **Rejected:** Keep assessing source selection (validity issues, not a writing skill per se)
- **Impacts:** Learning outcomes revision, timed test design
- **Set:** 2025-01-29

**DEC_006** [v1 | ACTIVE] - Learning Outcome Structure
- **What:** 4 outcomes per course (not 5); APA folded into source integration; audience folded into genre; "author" as verb
- **Why:** Simpler, more aligned with Kennisbasis structure (2.2.1 + 2.2.2); "author" captures validity point elegantly
- **Rejected:** 5 outcomes (too many), separate APA outcome (unnecessary granularity), separate audience outcome (part of genre)
- **Impacts:** All toetsplannen, outcome wording
- **Set:** 2025-01-29

**DEC_007** [v1 | ACTIVE] - Writing 2 Radical Simplification
- **What:** W2 = creative mimicry ONLY; no APA, no argumentative essay, no timed test
- **Why:** Language validated in W1 (propedeutic) and W3 (CPE); W2 focuses on genre awareness, diction, creative strategies
- **Rejected:** Keeping argumentative + APA (unnecessary, creates overlap with W1/W3)
- **Impacts:** W2 toetsplan, W2 P+Q&A criteria (higher bar for articulation)
- **Set:** 2025-01-29

**DEC_008** [v1 | ACTIVE] - Writing 1 Take-Home Genre
- **What:** Article for informal teacher journal — personal, argumentative, professional audience, more structural freedom
- **Why:** Expository essay is "not audience-aware"; article format gives clear audience/purpose; students can share opinions about teaching; more accessible than nuanced expository distinction
- **Rejected:** Expository essay (too abstract), formal academic essay (overlaps with timed test)
- **Impacts:** W1 assignment description, take-home instructions
- **Set:** 2025-01-29

**DEC_010** [v1 | ACTIVE] - Outcome 1 Tiering
- **What:** W1 "reflect awareness" → W2 "demonstrate deliberate application" → W3 "strategically leverage"
- **Why:** Creates coherent progression; mirrors strategy outcome tiering; same Kennisbasis element, increasing sophistication
- **Impacts:** All three course outcomes
- **Set:** 2025-01-29

**DEC_011** [v1 | ACTIVE] - Familiar/Unfamiliar Topics in Outcome 1
- **What:** "on familiar and unfamiliar topics" added to Outcome 1 for all courses
- **Why:** Directly from Kennisbasis 2.2.2 ("vertrouwde en niet-vertrouwde onderwerpen"); captured in timed test design (two prompts)
- **Impacts:** Outcome wording, timed test prompt design
- **Set:** 2025-01-29

**DEC_009** [v1 | ACTIVE] - Strategy Outcome Progression
- **What:** W1 "apply and justify" → W2 "consciously apply and justify" → W3 "strategically apply and justify"
- **Why:** Same core verb, increasingly intense adverb shows progression
- **Impacts:** Outcome wording across all three courses
- **Set:** 2025-01-29

---

## 🟡 LAYER 1 [ACTIVE CONTEXT]

### Execution Queue
**Focus:** ACTION_002 | **Progress:** 40%

**ACTION_001** [COMPLETE @2025-01-29T14:15]
- **Task:** Think-aloud session to clarify redesign proposal
- **Artifact:** conversation notes
- **Context:** DEC_001-005
- **Enables:** ACTION_002, ACTION_003
- **Prune:** "after presentation delivered"

**ACTION_002** [IN_PROGRESS] ← CURRENT
- **Task:** Draft Presentation + Q&A format structure
- **Progress:** 80%
- **Steps:**
  - ✓ Clarify what P+Q&A assesses (strategy awareness via terminology + practical examples)
  - ✓ Confirm duration (12.5 min presentation + 12.5 min Q&A + 5 min buffer = 30 min)
  - ✓ Draft P+Q&A presentation elements by genre (Proposal, Creative, Mimicry, Expository)
  - ✓ Draft Q&A prompt banks by genre
  - ✓ Create rubric framework (4 criteria: Authorship, Strategy Awareness, Decision-Making, Genre Awareness)
  - ✓ Draft strategy terminology bank
  - ▶ Review and refine with Freek ← NOW
  - ☐ Map to specific learning outcomes per course
- **Target:** /home/claude/presentation-qa-format-draft.md
- **Context:** DEC_001, DEC_003, DEC_004
- **Blockers:** None
- **Prune:** "when format finalized"

**ACTION_003** [PENDING]
- **Task:** Finalize presentation slide structure
- **Depends:** ACTION_002 (need P+Q&A format clarity)
- **Status:** Presentation structure outlined, needs refinement
- **Steps:** 6 sections @ ~5 min each
- **Context:** CONST_001 (30 min)

**ACTION_004** [PENDING]
- **Task:** Create one-pager handout for team leaders
- **Depends:** ACTION_003
- **Status:** Draft exists in conversation
- **Context:** PREF_002 (input-seeking)

### Active Artifacts
**presentation-qa-format-draft.md:**
- v:0.1 | status:draft | action:ACTION_002 | loc:"/home/claude/presentation-qa-format-draft.md"
- **Purpose:** Define structure, question types, criteria for oral defense component
- **State:** Draft complete; rubric section ON HOLD pending learning outcomes discussion
- **Next:** Finalize rubric after LO mapping
- **Context:** DEC_001, DEC_003, DEC_004
- **Done:** When approved for team leader presentation

**learning-outcomes-analysis.md:**
- v:0.1 | status:in_discussion | action:ACTION_002 | loc:"/home/claude/learning-outcomes-analysis.md"
- **Purpose:** Map Kennisbasis → current outcomes → new outcomes → test components
- **State:** Analysis complete; awaiting Freek's input on key questions
- **Next:** Decide on outcome structure (add 5th vs. rewrite existing)
- **Context:** Kennisbasis 2.2, current toetsplannen
- **Done:** When learning outcomes finalized

### Phase State
**Phase:** planning | **Goal:** Presentation ready for Jan 30 | **Progress:** 70% | **Blockers:** None currently

---

## 🟢 LAYER 2 [CONTEXT]

### External Precedents Found (Web Search 2025-01-29)
**University of Saskatchewan (2025):** 10 types of AI-resistant oral assessment tasks including:
- One-on-one role plays
- Synchronous oral exams with Zoom whiteboard
- Professional situation simulations
- Key quote: "having students engage in oral tasks in real time decreases the likelihood that AI will generate a significant part of their response"

**UNSW Teaching Gateway:** Oral assessment described as "authentic, secure, and versatile means of measuring students' competence" - term used: "evaluative conversation" (Aricò, 2021)

**UNESCO (Oct 2025):** "When students must articulate their understanding in real-time conversations, explain their reasoning, respond to unanticipated questions, or defend their conclusions against challenges, they demonstrate intellectual ownership that is difficult to fake."

**Frontiers in Education (Nov 2024):** Reflective writing + oral defense cited as AI-resistant; key is requiring students to explain process, not just submit product

**Academia.edu (Nov 2025):** "Oral Exams for a Generative AI World: Managing Concerns and Logistics for Undergraduate Humanities Instruction" - directly relevant paper

**Multiple sources confirm:** Oral assessment/viva voce growing in popularity as AI-resistant, authentic assessment method

### Grading Load Estimate
| Component | Current | Proposed |
|-----------|---------|----------|
| Initial marking | 30-45 min (essay read + feedback) | 15-20 min (shorter timed test) |
| Follow-up | 15-30+ min (clarification sessions) | Built into 30 min P+Q&A |
| Edge cases | Unlimited extra time | Capped |
| Admin after P+Q&A | — | +5 min per student |
| **Total** | 45-75+ min (variable) | 50-55 min (fixed, predictable) |
| **Hidden benefit** | — | P+Q&A doubles as feedback; mental load reduced (scheduled, verbal) |

---

## ⚪ LAYER 3 [REFERENCE]

### Key Arguments for Presentation
1. **Three broken assumptions:** Product = learning, Product = ability, Student = author → all invalid with AI/tools
2. **Spaghetti on the wall effect:** Students throw content hoping it sticks; no accountability mechanism
3. **Authorship as professional competence:** Teachers discuss their writing all the time; this is a real skill
4. **Validity, not cheating:** "This isn't about catching cheating. It's about what our test actually measures."
5. **External precedent:** Growing trend across HE (UNSW, USask, UNESCO guidance)

### Decision Points for Team Leaders
1. W3 take-home genre: Proposal vs Creative vs Choice? (Freek leans: choice)
2. P+Q&A criteria: How explicit should rubric be?
3. Timed test format confirmation: word count, sources, duration
4. P+Q&A duration: 30 min standard, flexibility for edge cases?

---

## 🔵 LAYER 4 [EPHEMERAL]

**Intent:** Finalized learning outcomes with tiering, familiar/unfamiliar topics, W1 genre; summarizing what's left
**Triggered:** User confirmed tiering approach, familiar/unfamiliar, W1 article genre; asked what's still open
**Affects:** Learning outcomes document (v2), presentation prep, rubric design
**Updates:** L0 (DEC_008 updated, DEC_010-011 added), analysis document v2

## 🟣 LAYER 4.5 [CHECKPOINT]

**Response Counter:** 5 | **Last Skill Re-read:** 2025-01-29T16:30 | **Next Re-read At:** 9

**Audit Trail:**
- Re-read #2 @2025-01-29T16:30: Layer 0 integrity ✓ (11 decisions) | L1 queue current ✓ | Pruning rules followed ✓
- Response #5 @2025-01-29T16:30: Outcome tiering finalized ✓ | Familiar/unfamiliar added ✓ | W1 genre decided ✓ | What's left summary provided
- Response #4 @2025-01-29T16:00: Learning outcomes revised ✓ | 4 key decisions captured (DEC_006-009) ✓
- Response #3 @2025-01-29T15:30: Kennisbasis analysis complete ✓ | Gap identified ✓
- Skill read #1 @2025-01-29T14:30: Layer 0 established ✓
