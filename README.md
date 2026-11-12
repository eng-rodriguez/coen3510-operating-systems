# COEN 3510 — Operating Systems

Instructor workspace for COEN 3510 Operating Systems (4 credits; 45 lecture
hours and 30 laboratory hours over 15 weeks), Computer Engineering, Inter
American University of Puerto Rico, Bayamón Campus.

This repository is instructor-private. It holds instructor solutions and hidden
tests, so it must never be shared with students as-is.

## Repository layout

| Path | Contents |
|------|----------|
| `CLAUDE.md` | Working rules for Claude-assisted development |
| `README.md` | Approved decisions and current development status (this file) |
| `handbook.html` | Instructor Handbook v1.5, the governing course design |
| `lectures/` | Objectives, readings, slides, instructor notes, examples |
| `labs/` | Lab handouts, starter code, local tests, checkpoints, instructor keys |
| `assessments/` | Quizzes, midterm, rubrics, Blackboard instructions, ABET evidence |
| `projects/` | Final team project (Project C) materials |

No other top-level items are added. Empty folders hold a `.gitkeep`.
Inside each lab or project subdirectory, student-facing files are kept separate
from instructor solutions and hidden tests. Student releases are built only from
student-facing files and never include instructor-only material.

## Approved decisions

There is no separate decision log; this section is the record. The handbook
(Section 5) is the authoritative policy text.

### Assessment organization
- 15 weekly laboratory sessions.
- 10 graded laboratory units, provisionally equally weighted within the 40%
  laboratory component: Weeks 2–9, 12 and 14. Week 1 is formative.
- Projects A (Mini Shell) and B (Concurrent Work Queue) are integrated into the
  graded laboratory units.
- Project C (xv6 extension) is the final team project, 30% of the course grade.
  Its gates (Weeks 10, 11, 13, 15) are graded only within the final project and
  are not double-counted as laboratory units.
- Six graded quizzes, provisionally in Weeks 2, 4, 6, 10, 12 and 14, given in
  the 15-minute retrieval slot at the start of lecture, supervised, in
  Blackboard. Retrieval quizzes in other weeks are formative.
- Individual supervised midterm in Week 8: about 90 minutes of the lecture
  block, covering Weeks 1–7; the other ~90 minutes cover semaphores and
  deadlock. The Week 8 laboratory remains a graded unit.

### Grading (unchanged)
- Course: laboratories 40%, final team project 30%, supervised midterm 20%,
  quizzes 10%. No separate final exam.
- Each laboratory unit: individual supervised checkpoint 60%, team local tests
  30%, team Blackboard report 10%.
- Individual checkpoint: 6 points, three criteria scored 0–2 (2 = full,
  1 = partial, 0 = no demonstrated competency): (A) working artifact or
  observed result, (B) prediction and explanation, (C) independent unseen
  task. Descriptors are in handbook Section 3. The old 4-point rubric is removed.
- Final project: implementation 40%, technical report 25%, presentation 15%,
  individual defense 20%. Presentations are 10–12 minutes per team including
  Q&A; individual technical defenses are separate.

### Teams and teaching
- Plan for 12 students in four teams of three.
- Students decide their own responsibilities; no prescribed or rotating roles.
- Textbooks: *Operating Systems: Three Easy Pieces* (primary);
  *Operating System Concepts*, 10th ed. (secondary).
- C on Linux; xv6 on RISC-V under QEMU; GCC, Make, GDB, Git.
- AI may assist development; AI-use disclosure is required in team reports and
  projects. No AI in supervised individual checkpoints, quizzes, midterm, or
  project defense.
- Blackboard is the official system for submissions, grades, rubrics and records.
- GitHub is for private team repositories and basic version control only.
- Local instructor-provided tests (`make test`); no CI/CD requirements.

### Production and repository
- Four specialist workstreams: Lectures (`lectures/`), Laboratories (`labs/`),
  Assessments (`assessments/`), Projects (`projects/`). The main project
  conversation is the orchestrator.
- Approved decisions and progress are recorded in this README; there is no
  separate decision log.
- Minimal seven-item top-level structure, as listed above.
- Projects A and B live under `labs/`; Project C under `projects/`. Each lab or
  project unit uses `student/` and `instructor/` subfolders.

### Decision record
| Date | Decisions |
|------|-----------|
| 2026-11-12 | Handbook v1.5 approved, with D1–D7: 6-point checkpoint descriptors (D1); graded units Weeks 2–9, 12, 14 (D2); Week 8 midterm split (D3); quiz delivery (D4); four workstreams (D5); folder conventions (D6); 10–12 min presentations (D7). |

## Development status

| Item | Status |
|------|--------|
| Handbook v1.5 reconciliation | Complete; approved 2026-11-12 |
| Repository initialization | Complete; approved 2026-11-12 |
| Environment validation (Linux toolchain, QEMU, xv6) | Not started; next phase, awaiting authorization |
| Week 1 package | Not started; next phase, awaiting authorization |
| Weeks 2–15, Project C, assessments | Not started |

Unresolved technical dependencies (next phase): pinned Ubuntu version,
GCC/GDB/Make versions, RISC-V cross toolchain, QEMU version and pinned xv6
commit; course syllabus approval; departmental ABET outcomes and thresholds.

Nothing in this repository has been released to students or submitted to
Blackboard.
