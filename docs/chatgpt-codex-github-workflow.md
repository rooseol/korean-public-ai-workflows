# ChatGPT, Codex, and GitHub Workflow

## Purpose

This document explains how to use ChatGPT, GitHub, and Codex together.

The goal is to separate planning, storage, and implementation.

---

## Role Separation

| Tool | Role |
|---|---|
| ChatGPT | Planning, explanation, prompt design, review |
| GitHub | Source storage, documentation, history, project management |
| Codex | Code generation, code modification, pull request creation |

---

## Basic Workflow

```text
ChatGPT
↓
Create project plan and task document

GitHub
↓
Store README.md, input examples, expected outputs, and task instructions

Codex
↓
Read task document and create or modify code

GitHub
↓
Review changes, create pull request, merge if acceptable
```

---

## Important Principle

ChatGPT and Codex are not automatically connected to each other.

GitHub acts as the shared workspace.

ChatGPT helps design the work.

Codex performs coding tasks inside the GitHub repository.

---

## Example Workflow

### Step 1. Plan with ChatGPT

Use ChatGPT to create:

- Project idea
- README.md
- input.txt
- expected-output.txt
- codex-task.md

---

### Step 2. Save the Plan to GitHub

Save the files in a project folder.

Example:

```text
projects/meeting-notes-action-plan/
├── README.md
├── input.txt
├── expected-output.txt
└── codex-task.md
```

---

### Step 3. Ask Codex to Work

Tell Codex:

```text
Repository: korean-public-ai-workflows

Please read this file first:

projects/meeting-notes-action-plan/codex-task.md

Then create:

projects/meeting-notes-action-plan/main.py

Use these files as references:
- projects/meeting-notes-action-plan/input.txt
- projects/meeting-notes-action-plan/expected-output.txt

After creating the script, explain how to run it.
```

---

### Step 4. Review the Result

Check:

- Does the new file exist?
- Does the code follow the task?
- Does it read the correct input file?
- Does it create the expected output file?
- Is the code understandable?
- Is the change small enough?

---

### Step 5. Pull Request and Merge

If Codex creates a pull request:

1. Open the PR
2. Read the description
3. Check `Files changed`
4. Review the code
5. Merge only if the result is acceptable

---

## Key Difference

| Action | Meaning |
|---|---|
| Commit | Save a change history |
| Branch | Create a safe working space |
| Pull Request | Request review |
| Merge | Apply changes to main |
| Release | Publish a usable version |

---

## Recommended Rule

Do not ask Codex to build a complete system at once.

Use this order:

```text
Small task
↓
Small code
↓
Review
↓
Commit
↓
Improve
```

---

## Checklist Before Using Codex

- [ ] Is the project folder ready?
- [ ] Is README.md written?
- [ ] Is input.txt prepared?
- [ ] Is expected-output.txt prepared?
- [ ] Is codex-task.md clear?
- [ ] Is the requested task small enough?
- [ ] Can I review the result?

---

## Summary

ChatGPT helps define the work.

GitHub stores the work.

Codex performs the coding task.

The user connects them by writing clear instructions and reviewing the result.
