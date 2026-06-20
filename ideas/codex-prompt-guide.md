# Codex Prompt Guide

## Purpose

This document provides a simple guide for writing better prompts for AI coding tools such as Codex.

The goal is to turn vague automation ideas into clear implementation instructions.

---

## Bad Prompt Example

```text
회의록 정리 프로그램 만들어줘.
```

Problem:

- Input is unclear
- Output format is unclear
- Programming language is unclear
- First version scope is unclear
- Too broad

---

## Better Prompt Structure

A good Codex prompt should include:

1. Goal
2. Input
3. Output
4. Required features
5. Excluded features
6. Technical constraints
7. Beginner-friendly requirements

---

## Prompt Template

```text
I want to build a simple automation tool.

Goal:
[What the tool should do]

Input:
[What kind of data the tool receives]

Output:
[What result the tool should produce]

Required features:
- [Feature 1]
- [Feature 2]
- [Feature 3]

Not required in the first version:
- Login
- Database
- Web interface
- Advanced error handling

Technical requirements:
- Use Python
- Keep the code beginner-friendly
- Use simple file input and output
- Add comments to important parts
```

---

## Example: Meeting Notes to Action Plan

```text
I want to build a simple Python script that converts meeting notes into a structured action plan.

Goal:
Extract meeting summary, key decisions, action items, owners, deadlines, and follow-up items from plain text meeting notes.

Input:
A plain text file containing meeting notes.

Output:
A structured text report with the following sections:
- Meeting Summary
- Key Decisions
- Action Items
- Owners
- Deadlines
- Follow-up Items

Required features:
- Read meeting notes from a text file
- Generate structured output
- Save the result as a new text file
- Keep the output format consistent

Not required in the first version:
- Login
- Database
- Web interface
- Automatic email sending
- Complex UI

Technical requirements:
- Use Python
- Keep the code beginner-friendly
- Add comments
- Use simple functions
```

---

## Checklist Before Asking Codex

- [ ] Is the goal clear?
- [ ] Is the input defined?
- [ ] Is the output defined?
- [ ] Is the first version small enough?
- [ ] Are unnecessary features excluded?
- [ ] Is the programming language specified?

---

## Key Principle

Do not ask Codex to build a complete system at once.

Start with a small working version.
Then improve it step by step.
