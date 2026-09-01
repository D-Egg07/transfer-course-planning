# transfer-course-planning

A Claude skill that builds a term-by-term course plan for California community college students transferring to a UC or CSU.

## What it does

This skill takes a community college student's transfer goal and generates a complete course-by-course plan and a one-page planner per target school. It runs an intake questionnaire to learn about the student's progress, existing credits, AP exams, and constraints. It then pulls authoritative data from assist.org articulation agreements, the college's Cal-GETC and AP charts, and UC/CSU admission requirements. The skill reconciles what the student has already completed against what each target requires, identifies remaining coursework, and offers guaranteed-admission backup tracks (UC TAG or CSU ADT) with optional cross-enrollment at the target campus. Finally, it builds a balanced term grid and renders a one-page HTML planner for each target.

## Install — as a plugin

```
/plugin marketplace add D-Egg07/transfer-course-planning
/plugin install transfer-course-planning@transfer-course-planning
```

## Install — as a plain skill

Copy `skills/transfer-course-planning/` into `~/.claude/skills/`.

## How it works

1. **Intake** — questionnaire on community college, target universities, major, current coursework, AP/IB exams, transfer term, unit load, guaranteed-admission preference, cross-enrollment interest, language background, and constraints
2. **Pull the data** — assist.org major articulation agreement, college Cal-GETC or IGETC list, AP/IB credit chart, CSU Transfer Model Curriculum (if applicable), and UC/CSU campus admission requirements
3. **Reconcile** — mark completed courses against major prep and GE areas; apply AP/IB credit per the college's own chart; flag after-transfer courses and remaining requirements
4. **Admission scaffolding** — minimum transferable units, junior standing, GPA floors and competitive ranges, UC 7-course pattern or CSU Golden Four requirements, impacted-major status, and CSU Constitution & American Ideals requirement
5. **Guaranteed backup** — recommend and fully map a TAG-eligible UC (Davis, Irvine, Merced, Riverside, Santa Barbara, Santa Cruz) or CSU ADT if the primary target has no guarantee
6. **Cross-enrollment** — if available through the community college, reserve one or two lower-division courses per term to take at the target after admission but before transfer
7. **Build the term grid** — distribute courses across terms to the transfer date, respecting prerequisites and unit caps, with running totals including AP and cross-enrollment credits
8. **Render the planner** — one HTML artifact per primary target, with a caveats block, catalog year attribution, and admit-term guidance

## Scope & disclaimer

This skill is **for California community college → UC or CSU transfer only**. It is planning guidance, not a substitute for a community college counselor or an official transcript evaluation. Every articulation, AP-credit, and admission-requirement detail must be verified against assist.org and the target campus.

## License

MIT
