# Builder Guide Module 04: Module Builder

**Time:** Part 1; Day 2, 1:30–3:00 PM (Lecture Outline + Slide Deck) · Part 2; Day 3, 10:30–11:30 AM (Quiz + Assignment Supplementary Material) · Part 3; Day 4, 2:30–3:00 PM (Finish Building Your Module)
**Feeds:** `course-site/modules/module-XX.md` (public outline) + `course-toolkit/lecture-prep-notes/module-XX-notes.md` (private, full notes) + `course-toolkit/quizzes/` (private, with answer key) + `course-site/resources.md` (public)

---

## Facilitator Notes *(remove or move to course-toolkit before publishing)*

- **Labeling flag:** the Day 2 session is currently titled "Module Builder, **Part 2**: Lecture Outline + Slide Deck" in the agenda, but it's the first Module Builder session chronologically, and Day 3's session is *also* labeled "Part 2" (Quiz + Assignment Supplementary Material). This is almost certainly a copy-paste labeling slip; recommend relabeling the Day 2 session "Part 1" before this goes out. I've numbered the parts below by chronological order, not by the agenda's current (inconsistent) labels.
- Day 3, 11:30 AM–12:30 PM ("Walkthrough Example: Moving Data onto HPC; using Claude for API data extraction") isn't assigned a Builder Guide module number, but it sits right in the middle of this Module Builder arc and is where the HPC-specific piece of the assignment actually gets built. Point participants there as the natural bridge between Part 1 and Part 2 below.
- This is the session where the coder/non-coder split matters most; see the callout in each part.

---

## Before You Start

Pick **one module** from your curriculum map (`course-site/schedule.md`) to build fully, end to end, as a repeatable template. You'll reuse this same process for every other module later; the point of building one *fully* this week is to have a pattern to copy.

---

## Part 1: Lecture Outline + Slide Deck (Day 2, 1:30–3:00 PM)

### Step 1: Outline the module

Ask Claude to draft a lecture outline from your learning outcome for this module:

> *"Draft a lecture outline for [module topic], covering [outcome]. Include a short intro, 2-3 core concepts, and a wrap-up tying to the HPC assignment."*

Already have lecture notes or slides for this module? Bring them, and ask Claude to restructure them into this format rather than starting over.

### Step 2: Build the slide deck

Source lives in Canva or Slides (per your institution's setup); export a PDF and archive it in the repo once done.

- **If you code:** you can also have Claude generate a deck directly (e.g., via `pptxgenjs`) if you'd rather work from a script than a GUI.
- **If you don't code:** stick with Canva/Slides; Claude can still help you write the outline and speaker notes that go into it.

### Step 3: Split public vs. private

- `course-site/modules/module-XX.md` → student-facing outline, slides link, assignment link
- `course-toolkit/lecture-prep-notes/module-XX-notes.md` → your full prep notes (talking points, timing, anything not meant for students)

---

## Part 2: Quiz + Assignment Supplementary Material (Day 3, 10:30–11:30 AM)

*(Bridge in: Day 3, 11:30 AM–12:30 PM covers moving data onto HPC and using Claude for API data extraction; that's the technical backbone for the assignment you're building supplementary material for here.)*

### Step 4: Build the quiz

In `course-toolkit/quizzes/module-XX-quiz.md`, with a full answer key. This stays private.

### Step 5: Build the assignment's supplementary material

In `course-site/resources.md`; datasets, reference links, setup instructions specific to this assignment.

If you already have an assignment written for this module, upload or paste it and have Claude adapt it rather than drafting from nothing.

- **If you code:** ask Claude to scaffold the actual assignment notebook/script now, so the quiz and supplementary material reference something concrete.
- **If you don't code:** describe the assignment goal and dataset to Claude and have it draft the starter notebook/script *and* a plain-language explanation you can hand to students (and use yourself to write the quiz).

---

## Part 3: Finish Building Your Module (Day 4, 2:30–3:00 PM)

### Step 6: Close any gaps

Cross-check: does `course-site/modules/module-XX.md` link to everything (slides, assignment, quiz link; not the quiz *content*, that stays private)?

### Step 7: Public/private leak check

Before moving on, re-read `course-site/modules/module-XX.md` and confirm no answer keys, grading notes, or private prep content made it into the public file.

---

## Checkpoint

- [ ] Lecture outline + slide deck built and linked in `course-site/modules/module-XX.md`
- [ ] Full prep notes in `course-toolkit/lecture-prep-notes/module-XX-notes.md`
- [ ] Quiz with answer key in `course-toolkit/quizzes/`
- [ ] Assignment supplementary material in `course-site/resources.md`
- [ ] Public file re-checked for accidental private content
