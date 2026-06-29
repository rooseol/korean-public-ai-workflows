# Codex Run Prompt

## Purpose

This file contains the actual prompt to give Codex when asking it to create the first Python script for this project.

---

## Prompt to Codex

```text
Repository: korean-public-ai-workflows

Please work on this project folder:

projects/meeting-notes-action-plan/

First, read this task document:

projects/meeting-notes-action-plan/codex-task.md

Also use these reference files:

projects/meeting-notes-action-plan/input.txt
projects/meeting-notes-action-plan/expected-output.txt

Task:
Create a beginner-friendly Python script named main.py in the same folder.

The script should:
1. Read meeting notes from input.txt
2. Generate a structured action plan
3. Include these sections:
   - Meeting Summary
   - Key Decisions
   - Action Items
   - Follow-up
4. Save the result to output.txt
5. Use simple functions
6. Add comments for beginners
7. Avoid database, login, web interface, or external services

After creating main.py, explain:
- What files were created or modified
- How to run the script
- What output file will be created

Please keep the first version simple.
```

---

## Expected Files After Codex Work

| File | Expected Status |
|---|---|
| `main.py` | Created |
| `output.txt` | Created after running script |
| `input.txt` | Already exists |
| `expected-output.txt` | Already exists |
| `codex-task.md` | Already exists |

---

## Review Checklist

After Codex finishes, check:

- [ ] Did Codex create `main.py`?
- [ ] Does `main.py` read `input.txt`?
- [ ] Does it create `output.txt`?
- [ ] Is the code simple enough?
- [ ] Are comments included?
- [ ] Is the output similar to `expected-output.txt`?
- [ ] Did Codex avoid unnecessary features?
