---
name: unit-planning
description: Plan whole units of work and scope-and-sequence documents aligned to the Victorian Curriculum F–10 Version 2.0 or VCE Study Designs. Use this skill whenever a teacher mentions unit planning, term planning, scope and sequence, curriculum mapping, designing a sequence of lessons, creating a unit of work, or needs to map curriculum content across weeks or a term. Also trigger when someone asks to "map out" a topic, plan "a series of lessons", "a term of [subject]", or mentions VCAA unit templates. When a teacher has been using the lesson-planning skill and seems to be planning multiple related lessons, suggest this skill.
---

# Unit Planning (Victorian Curriculum / VCE)

This skill helps VIT-registered teachers design whole units of work (typically 4–8 weeks) aligned to the Victorian Curriculum F–10 or VCE Study Designs. It produces scope-and-sequence documents, curriculum area maps, and detailed unit plans following the VCAA Teaching and Learning Unit (TLU) template structure.

## Before You Begin

Establish the planning scope. Ask only what isn't clear:

1. **Learning area / subject** — Which curriculum area? (e.g., Science, History, VCE Psychology)
2. **Year level or band** — e.g., Levels 5–6, Year 9, VCE Unit 3
3. **Topic or theme** — What is the unit about?
4. **Duration** — How many weeks? How many lessons per week?
5. **School context** — Government, Catholic, or independent? (affects reporting requirements)

If the teacher provides a topic without specifying the year level, ask. The achievement standards that anchor the unit depend on the level.

## Workflow

### Step 1: Reference the Curriculum Framework

For **F–10**: Read `shared-references/victorian-curriculum-f10.md`.
For **VCE**: Read `shared-references/vce-study-designs.md`.
For **APST alignment**: Read `shared-references/apst-standards.md`.

### Step 2: Map to Achievement Standards

This is the most important step. Start with the end in mind:

1. **Identify the achievement standard(s)** for the learning area and level/band
2. **Unpack** what students must understand and do
3. **Select content descriptions** that support the achievement standard
4. **Identify capabilities** that can be integrated (Critical and Creative Thinking, Ethical, Intercultural, Personal and Social)

For VCE: work from the **Outcomes** — these are the assessable statements of what students must demonstrate.

### Step 3: Design the Learning Sequence

A well-structured unit moves students from where they are to where the achievement standard says they should be. Consider:

- **Prior knowledge**: What do students already know? What pre-assessment will you use?
- **Progression**: How does each lesson build on the previous one?
- **Spacing and retrieval**: Where are opportunities to revisit earlier content?
- **Assessment points**: Where are formative checks? Where is the summative task?

### Step 4: Build the Unit Plan

Use this structure, which aligns with the VCAA TLU template and VTLM 2.0:

```markdown
# [Unit Title]

**Learning Area:** [Subject]
**Year Level/Band:** [Year or band]
**Duration:** [X weeks, Y lessons per week]
**APST Focus:** Standards 2.2, 2.3, 3.1, 3.2, 3.6 primarily

## Unit Overview
2–3 sentences describing what this unit is about and why it matters for students.

## Victorian Curriculum Alignment
### Achievement Standard(s)
[Quote or summarise the relevant achievement standard for this level/band]

### Content Descriptions
- [Content description 1]
- [Content description 2]
- [...]
- [Cross-curriculum capabilities integrated]

### [For VCE] Study Design References
- Unit: [X]
- Area(s) of Study: [X]
- Outcome(s): [Quote relevant outcomes]
- Key knowledge: [List]
- Key skills: [List]

## Essential Questions
2–3 big questions that frame the unit. These should be thought-provoking and not Google-able.
- e.g., "How do scientists build knowledge that changes over time?"
- e.g., "What makes an argument persuasive rather than just loud?"

## Learning Sequence

| Week | Lesson | Topic | Key Activities | Assessment Checkpoint |
|---|---|---|---|---|
| 1 | 1 | [Topic] | [Activity] | [Formative check] |
| 1 | 2 | [Topic] | [Activity] | — |
| ... | ... | ... | ... | ... |
| [Final] | [Final] | [Topic] | [Summative task] | Summative assessment |

## Assessment
### Pre-assessment
[How will you establish what students already know?]

### Formative Assessment
- [Ongoing check 1]
- [Ongoing check 2]

### Summative Assessment
[Describe the culminating task. For full assessment design, use the `assessment-design` skill.]

## Key Vocabulary
- [Term 1]: [Student-friendly definition]
- [Term 2]: [Student-friendly definition]
- [...]

## Resources
- [Resource 1 — e.g., textbook chapter, website, equipment]
- [Resource 2]
- [...]

## Differentiation Overview
| Consideration | Approach |
|---|---|
| Extension | [How will students working above level be extended?] |
| Support | [How will students working below level be supported?] |
| EAL | [Language supports] |
| Additional needs | [Adjustments based on IEPs/ILPs — use `iep-writing` skill for specific plans] |

## Reflection and Evaluation
### After the unit, consider:
- What worked well?
- What would you change next time?
- Did students meet the achievement standard?
- What evidence do you have? (APST 3.6)

## Curriculum Area Map Connection
[Note how this unit fits into the broader scope and sequence across year levels]
```

### Step 5: Connect to VCAA Planning Documents

The VCAA provides templates available at https://f10.vcaa.vic.edu.au/:
- **Curriculum Area Map** — scope and sequence across multiple year levels
- **Curriculum Area Plan** — term-by-term overview for a single learning area
- **Teaching and Learning Unit (TLU)** — the detailed unit plan (the structure above covers this)

If the teacher is developing a full-year scope and sequence, start with the Curriculum Area Map level. The unit plan is the zoom-in.

## Important Principles

### Why backwards design?
Start with the achievement standard (what should students be able to do at the end?), then plan the assessment (how will they show it?), then plan the lessons (what learning will get them there?). This ensures every lesson has a purpose and nothing is filler.

### Why a sequence, not just a list?
Individual lessons make sense to the teacher, but students experience learning as a sequence. They need to see how concepts connect. A unit plan ensures coherence — Lesson 3 builds on Lesson 2, which built on Lesson 1.

### Why integrate capabilities?
The Victorian Curriculum mandates explicit teaching of the 4 capabilities in and through the learning areas. A unit on persuasive writing naturally connects to Critical and Creative Thinking and Ethical Capability. Name these connections explicitly.

### Mathematics Version 2.0 note
From 2025, Mathematics uses Version 2.0. The strands are Number, Algebra, Measurement, Space, Statistics, Probability. Achievement standards are organised into paragraphs for each strand. Ensure units reference the v2.0 curriculum, not v1.0.

## Cross-Skill Connections

- Use `lesson-planning` to expand any individual lesson in the sequence
- Use `assessment-design` to build the summative assessment in detail
- Use `iep-writing` for students who need individual plans referenced in the differentiation section
- If this unit will be used as **VIT Inquiry evidence**, use the `vit-inquiry` skill to annotate it appropriately
