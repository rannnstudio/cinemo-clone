# CINEMO (시네모) - OTT 서비스 웹 프로젝트

> **학습 목적의 가상 OTT 서비스 웹 사이트 반응형 퍼블리싱 프로젝트**  
> Figma 디자인 시스템을 기반으로 HTML5 시맨틱 태그와 CSS3(Flexbox, Grid, Media Queries)를 활용해 제작되었습니다.

---

## 프로젝트 개요

- **프로젝트명**: CINEMO (가상 OTT 플랫폼)
- **개발 기간**: 2026.10.23 ~ 2026.10.29 (5일간)
- **팀명 / 역할**: 마스터 (7조) / HTML & CSS 반응형 웹 퍼블리싱
- **기술 스택**: HTML5, CSS3, Git, GitHub

---

## 주요 구현 기능 및 특징

1. **메인 페이지 (`index.html`)**
   - 상단 히어로 배너 및 영화/시리즈 카렉션 레이아웃
   - Flexbox 기반의 가로 스크롤(`overflow-x: auto`) 카드 리스트 구현
2. **마이페이지 (`mypage.html`)**
   - 사용자 프로필 카드 및 계정 설정 정보
   - CSS Grid 기반의 2열 찜한 콘텐츠 목록 구현 및 체크박스 인터페이스
3. **프로필 선택 페이지 (`profile.html`)**
   - 사용자 계정 선택 UI 및 프로필 관리 화면
4. **공통 및 반응형 최적화 (`common.css`)**
   - `@media (max-width: 768px)` 미디어 쿼리 기반 모바일 최적화
   - PC vs Mobile 환경에 맞춘 UI 요소 및 텍스트(`display: none/block`) 스위칭
   - CSS `:root` 변수를 활용한 컬러 테마 및 디자인 시스템 구축

---

## 파일 구조

```text
├── index.html        # 메인 홈 페이지
├── mypage.html       # 마이페이지
├── profile.html      # 프로필 선택 페이지
├── styles/
│   ├── reset.css     # CSS 리셋
│   ├── common.css    # 공통 헤더, 푸터, 테마 변수
│   ├── style.css     # 메인 페이지 전용 스타일
│   ├── mypage.css    # 마이페이지 전용 스타일
│   └── profile.css   # 프로필 선택 페이지 전용 스타일
└── asset/            # 이미지 및 SVG 아이콘 자산
```
