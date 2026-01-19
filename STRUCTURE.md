# 멍멍 스테이 웹사이트 구조

**웹사이트 유형**: 프리미엄 애견 펜션 랜딩 페이지

---

## 전체 구조

```
index.html
├── <header> - 네비게이션 바
├── <main> - 메인 콘텐츠
│   ├── #home (Hero 섹션)
│   ├── #about (소개 섹션)
│   ├── #amenities (시설 섹션)
│   ├── #rooms (객실 섹션)
│   └── #gallery-cta (CTA 섹션)
└── <footer> - 푸터
```

---

## 세부 섹션 분석

| 섹션 | ID | 내용 |
|------|-----|------|
| **헤더** | `#navbar` | 로고 + 네비게이션 메뉴 (홈, 소개, 객실, 시설, 예약하기) + 모바일 버거 메뉴 |
| **히어로** | `#home` | 메인 비주얼, 슬로건, CTA 버튼 (예약하기/둘러보기) |
| **소개** | `#about` | 2컬럼 레이아웃 - 텍스트 + 이미지 (`about.png`) |
| **시설** | `#amenities` | 3컬럼 그리드 - 개별 수영장, 천연 잔디 운동장, 펫 스파 |
| **객실** | `#rooms` | 2컬럼 그리드 - Suite A (Deluxe), Suite B (Premium) |
| **CTA** | `#gallery-cta` | 다크 배경 + 예약 유도 버튼 |
| **푸터** | `footer` | 사업자 정보, 연락처, SNS 링크 |

---

## 외부 리소스

| 종류 | 파일/URL |
|------|----------|
| CSS | `styles.css` |
| JavaScript | `script.js` |
| 폰트 | Google Fonts (Noto Sans KR, Outfit) |
| 아이콘 | FontAwesome (CDN) |
| 이미지 | `about.png` |

---

## 주요 특징

1. **반응형 디자인**: 모바일 버거 메뉴 포함
2. **스크롤 애니메이션**: `data-scroll`, `animate-up` 클래스 사용
3. **한국어 콘텐츠**: `lang="ko"` 설정
4. **Lazy Loading**: 이미지에 `loading="lazy"` 적용

---

## 네비게이션 메뉴

- 홈 (`#home`)
- 소개 (`#about`)
- 객실 (`#rooms`)
- 시설 (`#amenities`)
- 예약하기 (`#contact`) - 버튼 스타일

---

## 객실 정보

### Suite A (Deluxe)
- 기준 2인 / 최대 4인 (반려견 2마리 포함)
- 개별 바비큐장, 4K 빔프로젝터, 어메니티 제공

### Suite B (Premium)
- 기준 2인 / 최대 6인 (반려견 3마리 포함)
- 초대형 수영장, 복층 구조, 프리미엄 침구

---

## 연락처 정보

- **대표**: 김멍멍
- **사업자등록번호**: 123-45-67890
- **주소**: 강원도 속초시 멍멍로 123번길 45
- **전화**: 010-1234-5678
- **이메일**: hello@mungmungstay.com
