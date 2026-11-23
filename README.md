# 수산식품생화학실험실 홈페이지

국립부경대학교 식품영양학전공 수산식품생화학실험실(Marine Food Biochemistry Laboratory) 홈페이지입니다.

- 사이트: https://tjrals0300-cell.github.io
- 한국어 화면으로 바로 열기: https://tjrals0300-cell.github.io/?lang=ko

## 파일 구성

```
index.html   홈페이지 전체(디자인·내용·동작)
assets/      로고, 사진, 그림
```

## 내용 고치는 곳 (index.html)

| 내용 | 위치 |
| --- | --- |
| 연구실 이름·연락처·주소 | `const SITE` |
| 연구 분야 | `const RESEARCH` |
| 연구 주제 | `const PROJECTS` (그림은 `PROJECT_IMAGES`) |
| 학술지 논문 | `const PUBLICATIONS` (새 논문은 같은 형식으로 맨 위에 추가) |
| 학회 발표·프리프린트 | `const OTHER_WORKS` |
| 연구 과제 | `const GRANTS` |
| 소식 | `const NEWS` |
| 구성원 | `const MEMBERS` |
| 앨범 | `const ALBUMS` |
| 한국어 화면의 고정 문구 | `STATIC_KO`, `UI.ko` |

각 목록의 `ko` 항목이 한국어 화면에 쓰입니다. 논문 목록과 피인용 수는 자동으로 갱신되지 않습니다.
