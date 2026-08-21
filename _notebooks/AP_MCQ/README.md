# AP_MCQ — What This Folder Is & What To Do

This explains the `AP_MCQ/ap_mcq_lessons` folder: what's in it, how the notebooks work, and what you need to do in each one.

## Folder layout

```
ap_mcq_lessons/
  Teacher/        reference notebooks (primitives, stack/heap, data types) — read-only examples
  unit_01/        Primitive Types & Objects        (lessons 1.1–1.15 + quiz)
  unit_02/        Selection & Iteration             (lessons 2.1–2.12 + quiz)
  unit_03/        Classes                           (lessons 3.1–3.9 + quiz)
  unit_04/        Arrays & ArrayList                (lessons 4.1–4.12 + quiz)
```

Each unit is a set of numbered lessons (`X.Y-topic-name.ipynb`) followed by one quiz notebook (`uXquiz.ipynb`). Each file is a Jupyter notebook running a **Java kernel** (a few cells use Python).

## What's actually finished vs. still empty

- **Unit 1** — fully written. Every lesson has content and homework, and the quiz has real questions with answers.
- **Units 2–4** — a mix. Some lessons are fully written like unit 1; others are empty stubs (title only, no content yet — nothing to do there). **All three quizzes (units 2, 3, 4) are empty stubs** — no questions written yet.

Empty lessons aren't something you're missing — the content just hasn't been written for those yet.

## Cell types (the basic mechanics)

A notebook is a sequence of **cells**. Only two kinds matter here:

- **Markdown cell** — rendered text: explanations, questions, instructions. You never write your answer *as code* here — but for questions that ask for a written answer, you type directly into that cell.
- **Code cell** — a gray box you can run. Press **Shift+Enter** (or click ▶) to run it. Run cells top to bottom in order — later cells often depend on classes/variables defined earlier.

**Adding a new cell:**
- VS Code: hover below a cell → click `+ Code` or `+ Markdown`.
- Jupyter Lab/Notebook: click a cell, press `B` (insert below), then `Esc → Y` (code) or `Esc → M` (markdown).

## The workflow on a lesson page

1. Read the markdown explanation at the top.
2. Run the example code cells so you see the concept working.
3. Find the **"Homework Hack"** sections — marked with a comment like `// Q1 Hack:` or `# TODO: Your code here!`. This is the assignment.
4. Write your answer directly into that stub cell (or add a new code cell right after it), then run it. Check your output against any comment hints (e.g. `// Should be 'A'`).
5. Repeat for every hack on the page.

## The workflow on a quiz page (`uXquiz.ipynb`)

- Each question is multiple choice with the answer already given (e.g. "Answer: c) 2") — read only, nothing to fill in there.
- Some questions instead have a written-answer blank ("Answer: ") — type your answer into that markdown cell.
- Each question has a paired **Hack** code cell (e.g. `// Q2.1 Hack: Show in code...`) — this is empty and is yours to write, demonstrating the concept in code.

## Submitting

After finishing a lesson's hacks:
1. Take a screenshot of your completed work.
2. Post it to a GitHub issue.
3. Submit the issue link via the Google Form linked at the bottom of the lesson.
4. Homework is generally due within a few days of the lesson — check the specific lesson page for the exact deadline.

---

## Checklist

- [ ] Open lessons **in order** within a unit (1.1 → 1.2 → 1.3 …)
- [ ] For each lesson: read the markdown, then run every existing code cell
- [ ] Find every "Hack" / `# TODO` cell and write your own code there
- [ ] Run each hack cell and confirm the output looks right
- [ ] Skip lessons that are empty stubs (title only) — nothing assigned yet
- [ ] Do the unit quiz the same way: read questions, fill in the paired Hack code cells (and any written-answer blanks)
- [ ] Screenshot completed hacks → post to a GitHub issue → submit the issue link via the Google Form
- [ ] Repeat for the next unit
