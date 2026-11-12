# COEN 3510 — Operating Systems

## Purpose
Develop technically correct, reproducible instructional
materials for an undergraduate Computer Engineering OS course.

## Authority
Read `handbook.html` (Instructor Handbook v1.5; Section 5 is the
authoritative policy) and the approved decisions in `README.md`.
There is no separate decision-log file: record approved decisions
and development status in `README.md`.
Do not silently change course policies; treat changes as proposals
requiring instructor approval.

## Technical environment
- C for primary programming assignments.
- Linux for systems programming.
- xv6/RISC-V under QEMU for kernel laboratories.
- GCC, Make, GDB, and Git.
- Local automated tests using `make test`.
- No CI/CD requirements; do not require GitHub Actions.
- Blackboard is the official submission and grading system.
- Teams of three; no prescribed or rotating roles.
- AI-use disclosure is required in team reports and projects.

## Repository layout
Top-level items are limited to: `CLAUDE.md`, `README.md`,
`handbook.html`, `lectures/`, `labs/`, `assessments/`, `projects/`.
Use `.gitkeep` for empty directories.

## Specialist workstreams
Lectures (`lectures/`), Laboratories (`labs/`), Assessments
(`assessments/`), and Projects (`projects/`). The main project
conversation is the orchestrator. See handbook Section 4A.
Projects A and B live under `labs/`; Project C under `projects/`.
Each lab or project unit uses `student/` and `instructor/` subfolders.

## Assessment summary (details in handbook Section 5)
- Course: labs 40%, final team project (Project C) 30%,
  supervised midterm 20%, quizzes 10%.
- Each lab unit: individual checkpoint 60% (6 points, three
  criteria scored 0–2), team local tests 30%, team Blackboard
  report 10%.
- 15 lab sessions; 10 graded units (Weeks 2–9, 12, 14); Week 1
  formative; Project C gates are not double-counted as lab units.
- Six quizzes (Weeks 2, 4, 6, 10, 12, 14); midterm in Week 8.

## Repository rules
- Keep student and instructor materials separate, inside each
  lab or project subdirectory.
- Never include instructor-only material in student releases.
- Never distribute instructor solutions or hidden tests.
- Never commit student records or credentials.
- Never push changes without instructor approval.

## Validation
- Compile all C examples with appropriate warnings enabled.
- Execute available tests.
- Verify xv6 builds and boots when relevant.
- Document actual test commands and results.
- Clearly report untested or incomplete work.

## Course production
For each weekly package include:
1. Learning objectives and readings.
2. Lecture slides and instructor notes.
3. Worked examples and demonstrations.
4. Laboratory handout and starter code.
5. Local tests and expected outputs.
6. Individual competency checkpoints.
7. Blackboard instructions and rubrics.
8. ABET mapping and evidence plan.

## Completion criteria
No weekly package is complete until technical,
pedagogical, and student-facing reviews pass.