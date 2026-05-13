# AI 프롬프트 변환기

사용자가 작업 유형과 핵심 조건을 선택하면, 역할·목표·맥락·입력 자료·기준·금지사항·출력 형식·검토 방식이 포함된 실행형 프롬프트를 생성

## 지원 작업 유형

1. 검색
2. 코딩
3. 요약
4. 아이디어
5. 글쓰기
6. 투자/재테크
7. 마케팅
8. 리서치/분석
9. 학습/코치·작업 파트너
10. 여행/코스
11. 재미/생활/기타
12. 이미지 생성

## 파일 구조

```text
prompt-builder/
├─ index.html
├─ assets/
│  ├─ app.js
│  └─ styles.css
├─ data/
│  └─ prompt-config.js
├─ README.md
└─ IMPLEMENTATION_AUDIT.md
```

## 실행 방법

외부 라이브러리가 없으므로 `index.html`을 바로 열어도 됩니다. 로컬 서버로 확인하려면 아래 중 하나를 사용하세요.

```bash
npx serve prompt-builder
```

또는 VS Code Live Server로 `index.html`을 실행하면 됩니다.
