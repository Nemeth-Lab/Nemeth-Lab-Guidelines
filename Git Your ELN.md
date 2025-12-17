# **“How to Use GitHub as Your Electronic Lab Notebook (ELN)”**

##**Audience:** New lab members (undergraduate, graduate, postdoc)  
## **Goal:** Learn how to document experimental procedures using GitHub as an electronic lab notebook (ELN)

---

## Why We Use GitHub

GitHub helps us:
- Keep a permanent, time-stamped record of experiments
- Track changes and corrections automatically
- Collaborate without overwriting each other’s work
- Meet reproducibility and data-sharing expectations

### **Important:**  
GitHub is where we document *what we did*, *why we did it*, and *where the data lives* —  
### **NOT where large raw data files are stored.**

---

## What You Will Be Using

You do **not** need to know programming.

You will mainly use:
- **Markdown files (`.md`)** → for notes and procedures
- **YAML headers** → structured experiment metadata
- **GitHub Desktop or the GitHub website** → to upload and edit files

---

## Repository Layout (What Goes Where)

Every project repository follows the same structure:

```

project-name/

├── notebooks/     ← your daily experiment entries

├── protocols/     ← step-by-step procedures (like this one)

├── data/          ← small processed data + links to raw data

├── analysis/      ← scripts and figures

└── README.md

```

You will mostly work in:
- `notebooks/`
- `protocols/`

---

## Step 1: Get Access to the Repository

1. Accept the GitHub invitation sent by the lab
2. Log in at https://github.com
3. Navigate to the correct **project repository**
4. Bookmark it ⭐

If you are unsure which repository to use, ask before starting.

---

## Step 2: Create a New Experiment Notebook Entry

Every experiment gets its **own file**.

### File naming format
```

YYYY-MM-DD_short_description.md

```

### Example
```

2025-03-18_fear_conditioning_training.md

````

---

## Step 3: Start with the ELN Template

1. Go to the `templates/` folder
2. Copy `eln_template.yml`
3. Paste it at the **top of your new notebook file**
4. Fill in what you know — use `NA` if something does not apply

Example:

```markdown
---
eln_version: "1.0"
experiment:
  title: "Fear conditioning training"
  date:
    start: "2025-03-18"
  researcher:
    name: "Your Name"
  project: "Project Name"
---

## Notes
(Your notes go here)
````

Do **not** delete fields — just fill them in.

---

## Step 4: Link to the Correct Protocol

Do **not** rewrite protocols in your notebook.

Instead, reference the official protocol:

```markdown
## Procedure
This experiment followed the protocol:
- `protocols/fear_conditioning.md`
```

If you deviated from the protocol, clearly note it.

---

## Step 5: Document What You Did (In Plain Language)

Write as if **future-you** or **another lab member** will read this.

Good notes include:

* What animals/samples were used
* What settings or parameters were changed
* Anything unexpected

Example:

```markdown
## Observations
- Mouse A12 froze excessively during baseline
- Chamber fan failed during first trial and was reset
```

Bad notes:

> “Did fear conditioning, everything normal”

---

## Step 6: Record Where the Data Lives

Large files **DO NOT** go on GitHub.

Instead, write exactly where they are stored:

```markdown
## Data Location
- Raw data: Lab server → `/mnt/behavior/2025_03_18/`
- Processed data: `data/processed/freezing_summary.csv`
```

If data is missing or delayed, say so.

---

## Step 7: Save and Commit Your Work

### If using GitHub website

1. Scroll down
2. Write a short commit message:

   ```
   Add fear conditioning experiment notes
   ```
3. Click **Commit changes**

### If using GitHub Desktop

1. Save the file
2. Write a commit message
3. Click **Commit to main**
4. Click **Push**

**Commit at the end of every experimental day.**

---

## Step 8: Updating an Experiment

You may update the same notebook file over multiple days.

Each update should:

* Add new dates under a new header
* Never delete old entries

Example:

```markdown
## 2025-03-19 – Scoring
- Video files uploaded
- Freezing manually scored
```

GitHub automatically keeps the full history.

---

## Step 9: Common Mistakes to Avoid

❌ Uploading large files (images, sequencing data)
❌ Editing someone else’s notebook
❌ Deleting or overwriting past entries
❌ Using vague descriptions
❌ Forgetting to commit changes

---

## Step 10: When to Ask for Help

Ask your mentor or PI if:

* You are unsure where to store data
* A protocol did not work as expected
* You need to deviate from a procedure
* You are confused about GitHub

**Asking early prevents mistakes.**

---

## Final Checklist Before You Leave the Lab

* [ ] Notebook entry created
* [ ] Protocol referenced
* [ ] Deviations noted (if any)
* [ ] Data location recorded
* [ ] Changes committed to GitHub

---

## Key Takeaway

> If it’s not in GitHub, it didn’t happen.

Your notebook protects **you**, the **lab**, and the **science**.

Welcome to the lab 🧪

```

---


```
