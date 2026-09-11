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
| 2 | [Computer System Architecture](units/unit-02-computer-system-architecture/index.html) — Digital Logic Circuits, Data Representation, Register Transfer & Microoperations, Basic Computer Organization, Programming the Basic Computer, Microprogrammed Control, CPU, Pipeline & Vector Processing, I/O Organization, Memory Hierarchy, Multiprocessors | ✅ Ready |
| 3 | [Programming Languages and Computer Graphics](units/unit-03-programming-languages-computer-graphics/index.html) — Language Design & Translation, Elementary Data Types, Programming in C, OOP, Programming in C++, Web Programming, Computer Graphics, 2D & 3D Transforms and Viewing | ✅ Ready |
| 4 | [Database Management Systems](units/unit-04-database-management-systems/index.html) — DB Concepts & Architecture, Data Modeling, SQL, Normalization, Enhanced Data Models, Data Warehousing & Mining, Big Data Systems, NOSQL | ✅ Ready |
| 5 | [System Software and Operating System](units/unit-05-system-software-operating-system/index.html) — System Software, OS Basics, Process Management, Threads, CPU Scheduling, Deadlocks, Memory Management, Storage Management, File & I/O Systems, Security, Virtual Machines, Linux, Windows, Distributed Systems | ✅ Ready |
| 6 | [Software Engineering](units/unit-06-software-engineering/index.html) — Process Models, Requirements, Design, Quality, Estimation & Scheduling, Testing, Configuration Management | ✅ Ready |
| 7 | [Data Structures and Algorithms](units/unit-07-data-structures-algorithms/index.html) — Data Structures, Performance Analysis & Recurrences, Design Techniques, Lower Bound Theory, Graph Algorithms, Complexity Theory, Selected Topics, Advanced Algorithms | ✅ Ready |
| 8 | [Theory of Computation and Compilers](units/unit-08-theory-of-computation-compilers/index.html) — Theory of Computation, Regular/Context-Free Languages, Turing Machines, Unsolvable Problems, Syntax Analysis, Semantic Analysis, Run Time System, Intermediate Code Generation, Code Generation & Optimization | ✅ Ready |
| 9 | [Data Communication and Computer Networks](units/unit-09-data-communication-computer-networks/index.html) — Data Communication, Computer Networks, Network Models, OSI/TCP-IP Layer Functions, WWW, Network Security, Mobile Technology, Cloud Computing & IoT | ✅ Ready |
| 10 | [Artificial Intelligence](units/unit-10-artificial-intelligence/index.html) — Approaches to AI, Knowledge Representation, Planning, NLP, Multi Agent Systems, Fuzzy Sets, Genetic Algorithms, Artificial Neural Networks | ✅ Ready |

All 10 units of the syllabus are now covered.

## 📄 Previous papers

Original scanned question booklets for past GSET "Computer Science and Applications" exams are available on the [Previous Papers page](papers.html):

| Session | Paper | Questions | Marks |
|---|---|---|---|
| Sept 2016 | II | 50 | 100 |
| Sept 2016 | III | 75 | 150 |
| Sept 2018 | II | 100 | 200 |
| Dec 2021 | II | 100 | 200 |

These are scanned (image-only) PDFs with no embedded text layer, so they're provided as-is for reading/download rather than transcribed into the site.

## Repository structure

```
GSET/
├── index.html                 # Landing page linking to all units
├── papers.html                 # Previous papers page
├── papers/                     # Original scanned exam PDFs
├── units/
│   ├── unit-01-.../index.html # Description + diagrams + MCQ quiz for each unit
│   ├── unit-02-.../index.html
│   ├── ...
│   └── unit-10-.../index.html
└── README.md
```
