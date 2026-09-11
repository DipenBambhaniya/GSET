# GSET Exam Prep

Revision material for the GSET exam, organized unit by unit. Each unit gets:

- A **plain-language description** of every topic in the syllabus
- **Diagrams** (Venn diagrams, Hasse diagrams, graphs/trees, Karnaugh maps, LP feasible regions, PERT networks, etc.)
- A set of **practice MCQs** with instant scoring and explanations

Everything is published as a static website — no build step, no dependencies.

## 🌐 Website access

**Live site:** https://dipenbambhaniya.github.io/GSET/

> If the link above 404s, GitHub Pages hasn't been turned on for this repo yet.
> Enable it once: **Settings → Pages → Build and deployment → Source: "Deploy from a branch" → Branch: `main` / `(root)` → Save.**
> The site goes live a minute or two after that (and auto-updates on every future push to `main`).

## Units

| Unit | Topic | Status |
|---|---|---|
| 1 | [Discrete Structures and Optimization](units/unit-01-discrete-structures-optimization/index.html) — Mathematical Logic, Sets & Relations, Counting/Induction/Probability, Group Theory, Graph Theory, Boolean Algebra, Optimization (LP, Simplex, Integer Programming, Transportation/Assignment, PERT-CPM) | ✅ Ready |
| 2–10 | To be added | ⏳ Pending syllabus topics |

## Repository structure

```
GSET/
├── index.html                 # Landing page linking to all units
├── units/
│   └── unit-01-.../index.html # Description + diagrams + MCQ quiz for Unit 1
└── README.md
```

New units follow the same `units/unit-XX-<slug>/index.html` pattern and get linked from the root `index.html` and the table above as they're added.
