# Builder Guide Module 02: Learning Outcomes → Curriculum Map

**Time:** Day 1, 2:15–3:00 PM (Learning Outcomes) + Day 2, 10:15–11:00 AM (Curriculum Map & Schedule)
**Feeds:** `course-toolkit/learning-outcomes-map.md` (private) + `course-site/schedule.md` (public)

---

## Facilitator Notes *(remove or move to course-toolkit before publishing)*

- This module now spans an overnight gap — outcomes on Day 1 afternoon, curriculum map the next morning. Open the Day 2 session with 5 minutes for people to re-read their own outcomes doc before building the schedule on top of it; don't assume it's fresh in their heads.
- This is the session where "Why HPC?" (Day 1, 2:00–2:15, right before this block) turns into something concrete. Push participants to flag *which* outcomes will be assessed via an HPC-based assignment now — even a rough guess — since Module 04 (Module Builder) picks up directly from this flag.

---

## Part 1: Learning Outcomes (Day 1, 2:15–3:00 PM)

### Step 1: Draft 3–5 outcomes

Use Claude to turn a rough sense of "what I want students to be able to do" into properly scoped outcomes. A useful prompt:

> *"Help me write 3-5 learning outcomes for a [course topic] course. Students range from [describe prior experience]. I want at least one outcome that involves using HPC resources."*

### Step 2: Map each outcome to an assessment type

For each outcome, note in `course-toolkit/learning-outcomes-map.md`:
- How it will be assessed (assignment, quiz, exam)
- Whether it's HPC-based

**You don't need to know the technical details of the HPC assignment yet** — just flag it. Module 04 is where Claude helps you design the actual assignment, whether you code or not.

### Step 3: Fill in the table

```
| Module | Learning Outcome | Assessment | HPC-Based? |
|---|---|---|---|
```

---

## Part 2: Curriculum Map (Day 2, 10:15–11:00 AM)

### Step 4: Sequence your modules

Working from the outcomes table, sketch a week-by-week (or module-by-module) map. Ask Claude to help sequence — e.g.:

> *"Given these learning outcomes [paste table], suggest a logical order across N weeks, noting where the HPC-based assignment should land."*

### Step 5: Build `course-site/schedule.md`

This is the public-facing version — topic and assignment-due-date only, no grading detail.

---

## Checkpoint

- [ ] `course-toolkit/learning-outcomes-map.md` has 3–5 outcomes, each mapped to an assessment
- [ ] At least one outcome flagged as HPC-based
- [ ] `course-site/schedule.md` has a full module sequence with assignment due dates
