# Incident Report Workflow

## Purpose

This workflow helps generate structured incident reports for administrative and operational environments.

It is designed to support fast, consistent, and readable reporting during system failures, operational incidents, or unexpected situations.

---

## Report Structure

- Incident Summary
- Time and Location
- Cause Analysis
- Actions Taken
- Current Status
- Follow-up Actions

---

## Prompt (Korean)

```text
다음 상황 내용을 기반으로 사고/장애 보고서를 작성하세요.

출력 형식:
- 사고 개요
- 발생 시간
- 원인 분석
- 조치 사항
- 현재 상태
- 향후 계획

규칙:
- 객관적으로 작성
- 추측 표현 최소화
- 보고서 스타일 유지
- 핵심 중심으로 간결하게 작성
```

---

## Example

### Input

- 서버 네트워크 장애 발생
- 오전 09:10부터 연결 불가
- 스위치 오류 확인
- 장비 재부팅 후 정상화

---

### Output

#### 사고 개요
- 서버 네트워크 장애 발생

#### 발생 시간
- 오전 09:10

#### 원인 분석
- 스위치 장비 오류 발생

#### 조치 사항
- 스위치 재부팅 진행

#### 현재 상태
- 정상 복구 완료
