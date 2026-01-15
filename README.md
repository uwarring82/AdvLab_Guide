# Advanced Physics Laboratory — Document Guide

**Ulrich Warring, Physikalisches Institut, Universität Freiburg**

This repository contains the documents that govern how the Advanced Physics Laboratory works.

---

## What Is This?

Three documents work together to run the laboratory fairly and transparently:

| Document | What It Does | Can It Be Enforced? |
|----------|--------------|---------------------|
| **Invariant Framework** | Sets boundaries that cannot be crossed | Yes — always applies |
| **Unified Essay** | Describes what each role commits to | No — intentions only |
| **Unified Handbook** | Gives procedures and deadlines | Yes — can be enforced |

These documents form a hierarchy. Documents lower in the list cannot contradict documents higher in the list.

```
Invariant Framework (boundaries)
         ↓
Unified Essay (commitments)
         ↓
Unified Handbook (procedures)
         ↓
Experiment Guides (specific instructions)
```

---

## The Three Documents

### Invariant Framework

This document defines six principles that always apply. They cannot be changed by other documents.

The six principles are:

1. **Known Criteria** — You can only be assessed on criteria you knew about beforehand.
2. **Proportional Authority** — You can only be held responsible for things you had control over.
3. **Traceable Decisions** — Every decision that affects you must have a named person and a stated reason.
4. **Separation of Layers** — Why we do things, how we do things, and who decides are kept separate.
5. **Symmetric Visibility** — If a rule applies to you, you can see it. Everyone can see everyone's obligations.
6. **Correctable Error** — One mistake does not end your participation if you acknowledge it and correct it.

This document changes rarely. It is meant to last for many years.

### Unified Essay

This document describes what each group commits to:

- **Organisers** commit to fairness, clear expectations, and supporting tutors.
- **Tutors** commit to being present, giving honest feedback, and using authority carefully.
- **Students** commit to preparing, taking responsibility, and engaging with feedback.

The essay cannot be enforced. You cannot use it in a dispute. It exists so everyone can see what others have promised.

### Unified Handbook

This document contains the practical rules:

- Safety training requirements (valid for 12 months)
- The 15-minute presentation you give before starting an experiment
- How long tutors have to give feedback (14 days for reports)
- What to do if something goes wrong (escalation paths)
- How to estimate and report uncertainties
- Templates for notebooks and reports

These rules can be enforced. If the handbook says tutors must respond within 14 days, you can hold them to that.

---

## Core Values

Three values guide everything in these documents:

- **Respect** — For people, for the work, and for limits.
- **Trust** — Built through transparency, not assumed because of a title.
- **Responsibility** — Matched to what you can actually control.

---

## Key Design Choices

### Everyone Can See Everything

All sections are visible to all roles.

Students can read what tutors are expected to do. Tutors can read what organisers commit to. This is not surveillance. It lets everyone verify that expectations are fair.

Seeing something does not mean it applies to you. Each section only binds the role it addresses.

### Separate Layers

The documents are split by purpose:

- **Why we do things** → Unified Essay
- **How to do things** → Unified Handbook
- **What cannot be violated** → Invariant Framework

This stops procedures from being treated as principles. It also stops inspirational language from being used as a weapon.

### Private Information Stays Private

Personal details like schedules, grades, and contact information are not in these documents. They live on ILIAS, behind a login. Public documents contain no private data.

---

## Files in This Repository

```
AdvLab_Guide/
├── main.tex           # The main file that combines everything
├── framework.tex      # Invariant Framework
├── essay.tex          # Unified Essay
├── handbook.tex       # Unified Handbook
└── README.md          # This file
```

Future additions may include:

- Experiment-specific guides
- Standalone templates
- Diagrams

---

## How to Compile

### What You Need

A LaTeX installation. TeX Live 2023 or later is recommended.

### On Your Computer

Run these commands in the repository folder:

```bash
pdflatex main.tex
pdflatex main.tex
```

Run it twice so that cross-references work correctly.

### On Overleaf

1. Import this repository from GitHub.
2. Set `main.tex` as the main document.
3. Compile.

---

## Current Versions

| Document | Version | Status |
|----------|---------|--------|
| Invariant Framework | 0.1 | Approved |
| Unified Essay | 0.3 | Approved |
| Unified Handbook | 0.2.2 | Under review |

---

## Who Can Change What

| Document | Who Can Propose Changes | What Review Is Needed |
|----------|-------------------------|----------------------|
| Invariant Framework | Anyone | Two organisers must review. Changes must not break the principles. |
| Unified Essay | Organisers | Must check that changes do not contradict the Framework. |
| Unified Handbook (most sections) | Organisers | Must check that changes do not contradict the Framework. |
| Unified Handbook (common procedures and escalation) | Requires broader review | More people must agree before changes take effect. |

All changes must preserve the separation between the three documents. Procedures stay in the Handbook. Commitments stay in the Essay. Principles stay in the Framework.

---

## How to Contribute

You are welcome to suggest changes.

Before making big changes, open an issue to discuss your idea.

When proposing changes, keep in mind:

- The Framework should stay minimal and stable.
- The Essay should stay aspirational. It should not contain enforceable rules.
- The Handbook should stay practical. It should not contain philosophy.

---

## Licence

- Text and templates: MIT Licence (you can reuse and modify with attribution)
- Tables and figures: Creative Commons Attribution 4.0 (you can share and adapt with attribution)

---

## Contact

Physikalisches Institut  
Universität Freiburg

For questions about specific courses, check ILIAS.

---

*"It does not inspire, instruct, or persuade. It defines what must hold."*  
— Invariant Framework
