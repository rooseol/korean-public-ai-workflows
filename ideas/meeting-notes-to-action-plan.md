# Meeting Notes to Action Plan

## Purpose

Convert meeting notes into a structured action plan.

This automation idea is intended to help users quickly identify decisions, tasks, owners, deadlines, and follow-up items from unstructured meeting notes.

---

## Problem

Meeting notes often contain useful information, but the important action items are mixed with general discussion.

Manual takes time and important follow-up tasks can be missed.

---

## Input

Plain text meeting notes.

Example:

```text
서버 교체 일정에 대해 논의함.
예산 검토가 필요하며, 다음 주까지 견적서를 받아보기로 함.
김 담당자가 업체 3곳에 문의하고, 박 담당자가 예산 검토를 진행하기로 함.
```

---

## Expected Output

A structured action plan.

```text
Meeting Summary:
서버 교체 일정 및 예산 검토에 대해 논의함.

Key Decisions:
- 업체 견적서를 다음 주까지 확보하기로 함.
- 예산 검토를 병행하기로 함.

Action Items:
1. 업체 3곳에 견적 문의
   - Owner: 김 담당자
   - Deadline: 다음 주

2. 예산 검토
   - Owner: 박 담당자
   - Deadline: 다음 주

Follow-up:
- 다음 회의에서 견적 결과와 예산 검토 결과 확인
```

---

## First Version Scope

The first version should only support:

- Text input
- Summary generation
- Decision extraction
- Action item extraction
- Owner and deadline extraction

It does not need:

- Login
- Database
- Web interface
- Automatic email sending

---

<details> <summary> ## Codex Prompt Draft </summary>

```text
I want to build a simple Python script that converts meeting notes into a structured action plan.

Requirements:
- Input: plain text meeting notes
- Output: meeting summary, key decisions, action items, owners, deadlines, and follow-up items
- No GUI required
- No database required
- Start with a simple command-line script
- Keep the code beginner-friendly
```
---
</details>


## Status

| Item | Status |
|---|---|
| Idea collected | Done |
| Input defined | Done |
| Output defined | Done |
| First version scope | Done |
| Ready for Codex | Yes |
