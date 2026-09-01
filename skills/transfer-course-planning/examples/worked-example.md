# Worked example: Las Positas College to UC Berkeley Cognitive Science

This is an end-to-end run of the `transfer-course-planning` skill for one
anonymized student, from intake through the rendered planner. Read it to see
what a finished plan looks like and how each step feeds the next.

## The student

A Las Positas College student, Cognitive Science major, in their first semester
(Fall 2026). They are currently enrolled in PSYC 4, ENGL C1000, CS 1, and
MATH 1. In high school they passed the AP exams in Statistics, Psychology, and
Human Geography, and completed four years of Japanese. Their goal is UC
Berkeley, Cognitive Science B.A., transferring in Fall 2028. They are
comfortable carrying about 15 units per term, are open to summer terms, and
want a guaranteed backup admission.

## Step 2 — pulling the agreement

The assist.org articulation agreement used is Las Positas College to UC
Berkeley, Cognitive Science B.A. **Catalog year: 2025-2026.** This is a
fallback: the 2026-2027 agreement was not yet published when the plan was
built, so the most recent available year is used and this substitution must be
disclosed in the plan's caveats.

Lower-division preparation from that agreement:

| Berkeley requirement | Las Positas equivalent |
|---|---|
| Calculus | MATH 1 |
| Statistical Thinking | AP Statistics (score 3+) — no course needed |
| Computer Programming | ENGR 26 + CS 2 together, articulating to Berkeley ENGIN 7 (assist flags "this articulation will be revised") |
| Neuroscience (PSYCH C61) | PSYC 4 |
| Discrete Math (MATH 55) | CS 17 / MATH 10 |
| Intro to Cognitive Science (COG SCI 1) | **No Course Articulated** — take after transfer |
| One philosophy course (PHILOS 3 / 12A / 25A / 25B or AGRS 36) | **No Course Articulated** — take after transfer |

## Step 3 — reconciling

**AP to Cal-GETC mapping** (from the Las Positas AP chart):

- AP Statistics -> Area 2
- AP Psychology -> Area 4
- AP Human Geography -> Area 4

Psychology and Human Geography are two different Area 4 disciplines, so both
Area 4 course slots are satisfied by AP and no Area 4 course is needed.

**Already done or in progress:** MATH 1 (Calculus) and PSYC 4 (Neuroscience)
are in progress this term. AP Statistics clears Statistical Thinking outright.
AP covers Cal-GETC Area 2 and both Area 4 slots.

**After-transfer list** (no articulation exists, so they cannot be completed
before transferring and are deferred unless cross-enrollment is used — see
Step 6):

- Intro to Cognitive Science (COG SCI 1)
- One philosophy course (PHILOS 3 or an approved alternative)

## Step 4 — admission scaffolding

To be transfer-eligible the student needs **60 UC-transferable semester units**
and the **7-course pattern** (English composition 1A and 1B, a quantitative
reasoning course, and four courses across at least two of Cal-GETC Areas 3, 4,
and 5). The term grid below builds both.

The **UC language-other-than-English requirement** is satisfied by the four
years of high school Japanese; no college language course is required.

Berkeley Cognitive Science is a **direct-admit major in the College of Letters
& Science** — there is no secondary or capped-major screening at Berkeley for
this major, so meeting the L&S requirements and being competitive is the whole
task.

## Step 5 — the backup

The guaranteed backup is **UC Santa Cruz via TAG (Transfer Admission
Guarantee)**. Berkeley offers no TAG, so the backup must be a different campus.

UCSC's Cognitive Science B.S. is a screening major, but its screening courses
are already in this plan: calculus is MATH 1, statistics is AP Statistics, and
programming is CS 2. PSYC 4 also covers the major's recommended PSYC 20. Nothing
extra is needed for the backup.

**File the TAG September 1-30, 2027.**

## Step 6 — cross-enrollment

Las Positas participates in **UC Berkeley cross-enrollment**: about $46 per
unit, one lower-division course per term, up to two terms total, taken for a
letter grade. A student becomes ineligible once admitted anywhere.

Use both allowed terms for the two no-articulation courses:

- COG SCI 1 — Spring 2027
- PHILOS 3 — Fall 2027

**Timing rule:** both must finish before spring 2028 admission decisions, which
this schedule does, and both must be taken before any admission offer arrives
(which would end eligibility).

## Step 7 — the term grid

Units shown are Las Positas units; the Berkeley cross-enrollment course each
term is extra on top.

| Term | Load | Courses |
|---|---|---|
| Fall 2026 (in progress) | ~16 | PSYC 4, ENGL C1000, CS 1, MATH 1 |
| Spring 2027 | ~15 LPC + COG SCI 1 at Berkeley | CS 2, ENGL C1001 (Cal-GETC 1B), COMM C1000 (1C), an Ethnic Studies course (Area 6) |
| Summer 2027 | ~6 | ENGR 26, an Area 3A arts course |
| Fall 2027 | ~15 LPC + PHILOS 3 at Berkeley | CS 17 / MATH 10, a physical science + lab (Area 5A/5C), an Area 3B humanities course |
| Spring 2028 | ~15 | PSYC 25 (recommended for the major), a biological science course (Area 5B), transferable electives to clear 60+ units |

## Step 8 — the rendered planner

Filled into `templates/planner.html`, this plan becomes the student's one-page
planner artifact: the term grid, the after-transfer list, and the backup all
laid out on a single page, with the 2025-2026 catalog year disclosed in the
caveats section.
