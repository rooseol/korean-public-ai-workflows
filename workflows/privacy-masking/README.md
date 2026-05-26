# Privacy Masking Workflow

## Purpose

This workflow helps remove or mask personal information from administrative documents before sharing them with AI systems.

---

## Supported Information Types

- Resident registration numbers
- Phone numbers
- Addresses
- Email addresses
- Names
- Vehicle numbers

---

## Prompt (Korean)

```text
다음 문서에서 개인정보를 비식별화하세요.

규칙:
- 주민등록번호 일부 마스킹
- 전화번호 일부 마스킹
- 주소 일부 제거
- 이름 익명화 가능
- 문맥은 최대한 유지

출력은 원본 형식을 유지하세요.
```

---

## Example

### Input

홍길동 / 010-1234-5678 / 광주광역시 북구 / 900101-1234567

---

### Output

홍OO / 010-****-5678 / 광주광역시 북구 / 900101-1******
