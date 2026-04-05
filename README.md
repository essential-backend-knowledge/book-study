# 📚 주니어 백엔드 개발자가 반드시 알아야 할 실무 지식

> **최범균 저 · 한빛미디어 · 2025**

---

## 🎯 스터디 소개

백엔드 개발자로서 실무에 꼭 필요한 기초 지식을 함께 학습하고 토론하는 모임입니다.

---

## 👥 스터디원
<table>
  <tr>
    <td align="center">
      <a href="https://github.com/incheol789">
        <img src="https://github.com/incheol789.png" width="120" /><br/>
        <b>정인철</b>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/da4isy">
        <img src="https://github.com/da4isy.png" width="120" /><br/>
        <b>정다희</b>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/anewjean">
        <img src="https://github.com/anewjean.png" width="120" /><br/>
        <b>안유진</b>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/vividswan">
        <img src="https://github.com/vividswan.png" width="120" /><br/>
        <b>박수환</b>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/dd-jiny">
        <img src="https://github.com/dd-jiny.png" width="120" /><br/>
        <b>김대진</b>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/adminhelper">
        <img src="https://github.com/adminhelper.png" width="120" /><br/>
        <b>변숭문</b>
      </a>
    </td>
  </tr>
  <tr>
    <td align="center">
      <a href="https://github.com/lim-jaein">
        <img src="https://github.com/lim-jaein.png" width="120" /><br/>
        <b>임재인</b>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/iohyeon">
        <img src="https://github.com/iohyeon.png" width="120" /><br/>
        <b>임나현</b>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/zeexzeex">
        <img src="https://github.com/zeexzeex.png" width="120" /><br/>
        <b>김지혜</b>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/katiekim17">
        <img src="https://github.com/katiekim17.png" width="120" /><br/>
        <b>김평숙</b>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/yewonahn">
        <img src="https://github.com/yewonahn.png" width="120" /><br/>
        <b>안예원</b>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/essaysir">
        <img src="https://github.com/essaysir.png" width="120" /><br/>
        <b>손주선</b>
      </a>
    </td>
  </tr>
</table>

---

## 📅 진행 방식

| 항목 | 내용 |
|------|------|
| **주기** | 주 1회(매주 일요일) |
| **형식** | 발표 + Q&A / 토론(선택적) |
| **발표자** | 매주 발표자 선정 |
| **자료** | 발표자가 PR로 자료 제출 → 리뷰 후 머지 |

---

## 📖 챕터 구성

| 주차 | 챕터 | 주제 | 발표자 |
|:---:|:---:|------|:---:|
| 1 | Ch.2 | 느려진 서비스, 어디부터 봐야 할까 | 변숭문, 임나현 |
| 1 | Ch.3 | 성능을 좌우하는 DB 설계와 쿼리 | 임나현 |
| 2 | Ch.4 | 외부 연동이 문제일 때 살펴봐야 할 것들 | 안유진 |
| 2 | Ch.5 | 비동기 연동, 언제 어떻게 써야 할까 | 박수환 |
| 3 | Ch.6 | 동시성, 데이터가 꼬이기 전에 잡아야 한다 | 정인철 |
| 3 | Ch.7 | IO 병목, 어떻게 해결하지 | 손주선 |
| 4 | Ch.8 | 실무에서 꼭 필요한 보안 지식 | |
| 5 | Ch.9 | 최소한 알고 있어야 할 서버 지식 | 정다희 |
| 5 | Ch.10 | 모르면 답답해지는 네트워크 기초 | 임재인 |
| 6 | Ch.11 | 자주 쓰는 서버 구조와 설계 패턴 | |

---

## 📁 폴더 구조

```
book-study/
├── README.md
├── ch02-서비스-성능/
│   ├── 발표자료.md
│   └── 토론정리.md
├── ch03-DB-설계와-쿼리/
│   ├── 발표자료.md
│   └── 토론정리.md
├── ch04-외부-연동/
├── ch05-비동기-연동/
├── ch06-동시성/
├── ch07-IO-병목/
├── ch08-보안/
├── ch09-서버-지식/
├── ch10-네트워크/
└── ch11-설계-패턴/
```

---

## 📝 발표 자료 작성 가이드

### 발표자료에 포함할 것
- 챕터 핵심 내용 요약
- 본인이 인상 깊었던 부분 + 이유
- 실무 또는 프로젝트와 연결되는 지점(선택적)
- 토론하고 싶은 질문 1~2개(선택적)

### PR 규칙
- 브랜치: `ch{번호}-{이름}` (예: `ch02-incheol`)
- PR 제목: `[Ch.02] 느려진 서비스 — 정인철`

---

## 🤝 Ground Rules

1. **완독보다 이해가 우선** — 다 읽는 것보다 이해한 것을 나누는 게 중요합니다.
2. **질문에 정답은 없다** — "왜?"라는 질문이 가장 좋은 질문입니다.
3. **실무와 연결** — 책 내용을 본인 경험이나 프로젝트에 연결해봅니다.
4. **서로 존중** — 모르는 건 부끄러운 게 아닙니다. 함께 배우는 자리입니다.

---

## 📌 참고 자료

- [한빛미디어 도서 페이지](https://m.hanbit.co.kr/store/books/book_view.html?p_code=B2432813386)
- [저자 블로그 (최범균)](https://javacan.tistory.com/)
- [저자 유튜브](https://www.youtube.com/@madvirus)
