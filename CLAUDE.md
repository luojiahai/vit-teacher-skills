# VIT Teacher Skills

This repository contains skills for VIT-registered teachers in Victoria, Australia. The skills help with the full spectrum of teacher work — from daily lesson planning to career-critical registration processes.

## When to Use These Skills

These skills should be used whenever a user is a Victorian teacher (or works in Victorian schools) and needs help with teaching-related tasks. The skills are designed to be automatically triggered by relevant keywords, but you should also proactively suggest them when a conversation clearly relates to Victorian teaching practice.

Look for signals like:
- References to the Victorian Curriculum, VCE, VIT, APST, DET, VCAA
- Mentions of specific Victorian schools, year levels (F–10, VCE Units 1–4), or learning areas
- Teacher-specific tasks (lesson planning, report writing, assessment design)
- Registration or professional learning questions
- Behaviour or incident documentation in a school context
- Parent communication in a school context

## Skill Overview

All skills live in `skills/teaching/`. Each skill has a `SKILL.md` with its name, description, and instructions, plus a `references/` directory with supplementary materials.

| Skill | For |
|---|---|
| `lesson-planning` | Single lesson plans — Victorian Curriculum F–10 / VCE |
| `unit-planning` | Whole-unit and term plans, scope & sequence |
| `assessment-design` | Assessment tasks, rubrics, feedback frameworks |
| `report-card-writing` | Student report comments — 5-point scale, plain English |
| `iep-writing` | IEPs, ILPs, NCCD documentation, EAL/high-ability plans |
| `incident-documentation` | Incident reports, mandatory reporting, child safety |
| `behaviour-support-planning` | Proactive BSPs, functional behaviour assessments, SWPBS |
| `parent-communication` | Parent emails, newsletters, interviews, complaints |
| `vit-inquiry` | PRT → Full registration: 5-stage Inquiry, 37 APST descriptors |
| `professional-learning-reflection` | Annual 20-hour PL documentation, VIT audit-ready |

## Shared References

The `shared-references/` directory contains curriculum and policy information used across multiple skills:

- `apst-standards.md` — The 7 APST standards, 37 descriptors, 3 domains
- `victorian-curriculum-f10.md` — Victorian Curriculum F–10 structure and achievement standards
- `vce-study-designs.md` — VCE subject structure, outcomes, and assessment
- `vit-policies.md` — Registration, PL, audit, and codes of conduct

When a skill instructs you to read a shared reference, read it. The references contain the domain knowledge the skills depend on — curriculum structures, policy details, and legal frameworks.

## How Skills Connect

The skills form natural chains:

```
unit-planning → lesson-planning → assessment-design → report-card-writing
                                                                                    → parent-communication

iep-writing ←→ behaviour-support-planning ←→ incident-documentation

vit-inquiry ← nearly all other skills (as evidence sources)

professional-learning-reflection ← ongoing from all practice
```

When using one skill, suggest related skills if the teacher's need extends beyond the current scope. For example, if a teacher asks for a lesson plan but doesn't have a unit plan, suggest `unit-planning`. If a teacher is documenting incidents and the behaviour is recurring, suggest `behaviour-support-planning`.

## Important Context

### The teacher's regulatory environment

Victorian teachers are regulated by VIT and must:
- Demonstrate the APST (Australian Professional Standards for Teachers)
- Complete 20 hours of PL annually covering all 3 APST domains
- Maintain recency of practice (20 days/year)
- Comply with mandatory reporting obligations (CYFA s.184, Crimes Act s.327)
- Follow DET policies (reporting, behaviour, child safety)

### The curriculum landscape (2025–2026)

- Victorian Curriculum F–10 Version 2.0 is the current version
- Mathematics Version 2.0 is mandatory for reporting from Term 1 2026
- English Version 2.0 was fully implemented in 2025
- VCE Study Designs are revised on rolling schedules — always check current accreditation periods

### School diversity

Victoria has three school sectors: Government (DET), Catholic, and Independent. Government schools follow DET policies most strictly. Catholic and Independent schools have their own reporting and policy frameworks, but all use the Victorian Curriculum and APST. When a skill references DET-specific policy (like the 5-point scale or ISOC reporting), note that it may vary in non-government schools.
