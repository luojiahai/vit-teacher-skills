# VIT Teacher Skills

This repository contains skills for VIT-registered teachers in Victoria, Australia. The skills help with the full spectrum of a teacher's professional life — from daily classroom practice to career-critical registration processes with the Victorian Institute of Teaching.

## When to Use These Skills

These skills should be used whenever a user is a VIT-registered teacher (or works in Victorian schools) and needs help with teaching-related tasks. The skills are designed to be automatically triggered by relevant keywords, but you should also proactively suggest them when a conversation clearly relates to Victorian teaching practice.

Look for signals like:
- References to VIT, APST, registration, renewal, audit, professional learning
- References to the Victorian Curriculum, VCE, VCAA, DET
- Mentions of specific Victorian schools, year levels (F–10, VCE Units 1–4), or learning areas
- Teacher-specific tasks (lesson planning, report writing, assessment design)
- Registration status questions — PRT (provisional), full registration, moving to full
- Professional conduct or ethical questions
- Behaviour or incident documentation in a school context
- Parent communication in a school context

## Skill Overview

All skills live in `skills/teaching/` (runtime: `.agents/skills/` via `.claude/skills` symlink). Each skill has a `SKILL.md` with its name, description, and instructions, plus a `references/` directory with supplementary materials.

### Registration & Career Skills (VIT-specific)

| Skill | For |
|---|---|
| `vit-inquiry` | PRT → Full registration: 5-stage Inquiry, all 37 APST descriptors at Proficient level |
| `vit-registration-renewal` | Annual registration renewal: PL hours, recency of practice, MyVIT process |
| `vit-professional-conduct` | VIT Codes of Conduct and Ethics, mandatory notifications, professional boundaries |
| `professional-learning-reflection` | Annual 20-hour PL documentation, APST domain coverage, VIT audit-ready records |

### Teaching Practice Skills

| Skill | For |
|---|---|
| `unit-planning` | Whole-unit and term plans, scope & sequence — Victorian Curriculum F–10 / VCE |
| `lesson-planning` | Single lesson plans — explicit instruction, differentiation, APST-aligned |
| `assessment-design` | Assessment tasks, rubrics, feedback frameworks — Victorian Curriculum / VCE |
| `report-card-writing` | Student report comments — 5-point scale, plain English, curriculum-aligned |
| `iep-writing` | IEPs, ILPs, NCCD documentation, personalised learning plans |
| `incident-documentation` | Incident reports, mandatory reporting (CYFA s.184), child safety |
| `behaviour-support-planning` | Proactive BSPs, functional behaviour assessments, SWPBS |
| `parent-communication` | Parent emails, newsletters, interviews, complaints — APST 7.3 aligned |

## Shared References

The `shared-references/` directory contains curriculum and policy information used across multiple skills:

- `apst-standards.md` — All 37 APST descriptors at Proficient level, the 3 domains, and evidence principles
- `victorian-curriculum-f10.md` — Victorian Curriculum F–10 Version 2.0 structure, achievement standards, and reporting requirements
- `vce-study-designs.md` — VCE subject structure, Units 1–4, Outcomes, assessment types, and accreditation periods
- `vit-policies.md` — VIT registration categories, Inquiry requirements, renewal, PL, audit, Codes, and conduct

When a skill instructs you to read a shared reference, read it. The references contain the domain knowledge the skills depend on — APST descriptors, curriculum structures, policy details, and regulatory frameworks.

## How Skills Connect

The skills form natural chains centered on a teacher's career lifecycle:

```
Registration Pathway:
  vit-inquiry → vit-registration-renewal ↔ professional-learning-reflection
                    ↕
  vit-professional-conduct (underpins all practice)

Teaching Practice Chain:
  unit-planning → lesson-planning → assessment-design → report-card-writing
                                                              ↕
                                                      parent-communication

Student Support Chain:
  iep-writing ←→ behaviour-support-planning ←→ incident-documentation

Cross-cutting:
  Nearly all skills feed evidence into vit-inquiry (for PRTs) and
  professional-learning-reflection (for all teachers)
```

When using one skill, suggest related skills if the teacher's need extends beyond the current scope. For example, if a teacher asks for a lesson plan but doesn't have a unit plan, suggest `unit-planning`. If a teacher is documenting incidents and the behaviour is recurring, suggest `behaviour-support-planning`. If a PRT is building any teaching artifact, suggest annotating it for the `vit-inquiry`.

## Important Context

### VIT Registration Categories

Teachers hold one of: Provisional, Full, Non-practising, or Permission to Teach (PTT). PRTs complete the VIT Inquiry to achieve full registration. Fully registered teachers renew annually via MyVIT.

### The Professional Standards (APST)

All VIT-registered teachers are assessed against the 7 Australian Professional Standards for Teachers (37 descriptors across 3 domains). PRTs must demonstrate all 37 at the Proficient level. All teachers must link professional learning to the standards.

### Annual Requirements (Full Registration)

- **20 hours** of professional learning across all 3 APST domains
- **20 days** of professional practice (recency of practice)
- Annual renewal declaration via MyVIT
- Retain PL evidence for at least 2 years (audit-ready)

### VIT Codes and Conduct

All registered teachers are bound by the Victorian Teaching Profession's Code of Conduct and Code of Ethics. Breaches may result in VIT investigation, conditions, suspension, or cancellation.

### The Curriculum Landscape (2025–2026)

- Victorian Curriculum F–10 Version 2.0 is the current version
- Mathematics Version 2.0 is mandatory for reporting from Term 1 2026
- English Version 2.0 was fully implemented in 2025
- VCE Study Designs are revised on rolling schedules — always check current accreditation periods

### School Diversity

Victoria has three school sectors: Government (DET), Catholic, and Independent. Government schools follow DET policies most strictly. Catholic and Independent schools have their own reporting and policy frameworks, but all use the Victorian Curriculum and VIT's regulatory framework.

### Key Legislation Affecting Victorian Teachers

- *Education and Training Reform Act 2006* — VIT's establishing legislation
- *Children, Youth and Families Act 2005* s.184 — mandatory reporting
- *Crimes Act 1958* ss.327, 49O — failure to disclose/failure to protect
- *Disability Standards for Education 2005* — adjustments and NCCD
- Ministerial Order No. 870 — Child Safe Standards
