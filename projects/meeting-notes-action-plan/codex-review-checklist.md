# Codex Review Checklist

## Purpose

This checklist is used to review Codex-generated code before accepting or merging changes.

The goal is to make sure the first version stays simple, understandable, and aligned with the project scope.

---

## Expected Project Files

| File | Status | Purpose |
|---|---|---|
| `README.md` | Existing | Project overview |
| `input.txt` | Existing | Sample input |
| `expected-output.txt` | Existing | Desired output example |
| `codex-task.md` | Existing | Task definition |
| `codex-run-prompt.md` | Existing | Prompt to give Codex |
| `main.py` | To be created | Python script |
| `output.txt` | Generated | Script output |

---

## Code Review Checklist

- [ ] `main.py` was created in the correct folder
- [ ] `main.py` reads `input.txt`
- [ ] `main.py` creates `output.txt`
- [ ] The script can run from the command line
- [ ] The code is beginner-friendly
- [ ] The code uses simple functions
- [ ] Important parts have comments
- [ ] No database was added
- [ ] No login feature was added
- [ ] No web interface was added
- [ ] No unnecessary external service was added

---

## Output Review Checklist

- [ ] Output contains `Meeting Summary`
- [ ] Output contains `Key Decisions`
- [ ] Output contains `Action Items`
- [ ] Output contains `Follow-up`
- [ ] Output is similar to `expected-output.txt`
- [ ] Output is readable
- [ ] Output does not overcomplicate the result

---

## Safety Rule

Do not merge Codex changes just because the code was generated.

Review the changed files first.

Use the `Files changed` tab in the Pull Request before merging.

---

## Decision

| Review Result | Action |
|---|---|
| Looks good | Merge |
| Needs small fix | Ask Codex to revise |
| Too complex | Close PR and simplify task |
| Wrong direction | Rewrite the prompt |
