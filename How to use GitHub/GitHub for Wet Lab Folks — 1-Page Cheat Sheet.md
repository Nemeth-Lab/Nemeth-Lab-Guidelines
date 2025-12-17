# GitHub for Wet Lab Folks — 1-Page Cheat Sheet

**Purpose:**  
Use GitHub as your electronic lab notebook (ELN) to document experiments clearly, safely, and reproducibly.

You do **not** need to know coding.

---

## What GitHub Is (in Our Lab)

✔ A time-stamped lab notebook  
✔ A shared folder with rules  
✔ A way to track who did what and when  

❌ Not a place for large raw data files  
❌ Not a substitute for lab servers  

---

## The Only 5 Things You Need to Know

### 1️⃣ Repository = Project
Each GitHub **repository** is one research project.

You will usually work in:
- `notebooks/` → daily experiment records
- `protocols/` → step-by-step procedures

---

### 2️⃣ Every Experiment Gets Its Own File

**File name format:**
```

YYYY-MM-DD_short_description.md

```

**Example:**
```

2025-03-18_fear_conditioning.md

```

Never reuse a file for a new experiment.

---

### 3️⃣ Markdown = Plain Text (Easy)

Markdown is just text with simple formatting.

| You type | You get |
|--------|---------|
| `# Title` | Big title |
| `## Section` | Section header |
| `- item` | Bullet |
| `**bold**` | **bold** |

No special software needed.

---

### 4️⃣ Always Start with the ELN Template

At the top of every notebook file:
- Paste the ELN YAML template
- Fill in what you know
- Use `NA` if something doesn’t apply
- Never delete fields

This makes notebooks consistent and reviewable.

---

### 5️⃣ Commit = Save Permanently

A **commit** is like signing your notebook.

✔ Saves your work  
✔ Time-stamps it  
✔ Records your name  

**Commit at the end of every experimental day.**

**Good commit message:**
```

Add fear conditioning training notes

````

---

## What Goes Where (Very Important)

### ✅ Goes on GitHub
- Experiment notes
- Protocol references
- Small CSV files
- Analysis scripts
- Figures

### ❌ Does NOT Go on GitHub
- Microscopy image stacks
- Sequencing data
- Large videos
- Instrument raw files

Instead, **write where the data is stored**.

---

## How to Record Data Locations

Example:
```markdown
## Data Location
- Raw data: Lab server → `/mnt/behavior/2025_03_18/`
- Processed data: `data/processed/freezing.csv`
````

If you didn’t generate data that day, say so.

---

## Protocols: Don’t Rewrite Them

✔ Reference existing protocols
❌ Don’t copy-paste protocols into notebooks

Example:

```markdown
Followed protocol:
- protocols/fear_conditioning.md
```

**If you deviated, write it down clearly.**

---

## Golden Rules

✔ Write for future-you
✔ Be specific, not vague
✔ Never delete old entries
✔ Ask if unsure
✔ Commit daily

---

## Common Mistakes (Avoid These)

❌ Uploading large files
❌ Editing someone else’s notebook
❌ “Everything went fine”
❌ Forgetting to commit
❌ Waiting days to write notes

---

## When in Doubt, Remember

> **If it’s not in GitHub, it didn’t happen.**

Your notebook protects:

* You
* The lab
* The science 🧪

Welcome to the lab!

```

---

If you want, I can also:
- Add **screenshots** (GitHub Desktop workflow)
- Create a **laminated bench-side version**
- Write a **“What to write when nothing worked” guide**
- Customize this for **undergrads vs grad students**

Just tell me what you’d like next.
```
