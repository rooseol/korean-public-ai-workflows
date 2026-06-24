# Meeting Notes Action Plan Project

## Purpose

This project converts plain meeting notes into a structured action plan.

The goal is to create a small automation tool that helps users extract:

- Meeting summary
- Key decisions
- Action items
- Owners
- Deadlines
- Follow-up items

---

## Project Scope

### Version 0.1

The first version should be simple.

It should support:

- Plain text input
- Structured text output
- Command-line execution
- Beginner-friendly Python code

It should not include:

- Login
- Database
- Web interface
- Email sending
- Advanced UI

---

## Input Example

```text
서버 교체 일정에 대해 논의함.
예산 검토가 필요하며, 다음 주까지 견적서를 받아보기로 함.
김 담당자가 업체 3곳에 문의하고, 박 담당자가 예산 검토를 진행하기로 함.
```

---

## Expected Output Example

```text
Meeting Summary:
서버 교체 일정 및 예산 검토에 대해 논의함.

Key Decisions:
- 다음 주까지 견적서를 확보하기로 함.
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

## Codex Task Draft

```text
Build a simple Python command-line script.

Goal:
Convert plain meeting notes into a structured action plan.

Input:
A text file containing meeting notes.

Output:
A text file containing:
- Meeting Summary
- Key Decisions
- Action Items
- Owners
- Deadlines
- Follow-up Items

Requirements:
- Use Python
- Keep the code beginner-friendly
- Use simple functions
- Add comments
- Do not use a database
- Do not create a web interface
```

---

## Project Status

| Item | Status |
|---|---|
| Project folder created | Done |
| Input example prepared | Done |
| Output example prepared | Done |
| Codex task draft prepared | Done |
| Python script created | Not started |
| Test completed | Not started |

---

## Next Steps

1. Create `input.txt`
2. Create `expected-output.txt`
3. Ask Codex to generate the first Python script
4. Review the result
5. Commit the first working version
