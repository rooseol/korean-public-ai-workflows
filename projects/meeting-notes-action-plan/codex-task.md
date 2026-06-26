# Codex Task: Meeting Notes Action Plan

## Goal

Build a simple Python command-line script that converts meeting notes into a structured action plan.

The script should read meeting notes from `input.txt` and generate an output similar to `expected-output.txt`.

---

## Project Files

| File | Purpose |
|---|---|
| `README.md` | Project overview |
| `input.txt` | Sample meeting notes input |
| `expected-output.txt` | Example of the desired output |
| `main.py` | Python script to be created |

---

## Input

The script should read from:

```text
input.txt
```

The input contains plain Korean meeting notes.

---

## Expected Output

The script should create a structured report with these sections:

1. Meeting Summary
2. Key Decisions
3. Action Items
4. Follow-up

The output should be saved as:

```text
output.txt
```

---

## Requirements

- Use Python
- Create a simple command-line script
- Read text from `input.txt`
- Write result to `output.txt`
- Keep the code beginner-friendly
- Use functions where appropriate
- Add comments to explain important parts
- Do not use a database
- Do not create a web interface
- Do not require login

---

## First Version Scope

The first version does not need to be perfect.

It only needs to:

- Read the input file
- Generate a structured output
- Save the result to a text file

---

## Codex Instruction

```text
Create a beginner-friendly Python script named main.py.

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
7. Do not use a database or web interface

Use the existing input.txt and expected-output.txt files as references.
```

---

## Review Checklist

After Codex creates the script, check:

- [ ] Does `main.py` exist?
- [ ] Does it read `input.txt`?
- [ ] Does it create `output.txt`?
- [ ] Is the code understandable?
- [ ] Are comments included?
- [ ] Is the result similar to `expected-output.txt`?
