# Gukhwa — Motion Design Studio

모션그래픽 디자인 스튜디오 Gukhwa의 브랜드 포트폴리오 사이트.

- **Hero**: 기울어진 모션 영상 월 · 스크롤 시 타이틀 페이드 & 월 확대
- **About**: 스크롤 스크럽 매니페스토 · 실적 카운터
- **Work**: 필터 가능한 영상 그리드 · 패럴랙스 · 라이트박스
- **Services / Process / Pricing / Testimonials**
- **Booking**: 3단계 상담 예약 → FormSubmit(이메일) 또는 Formspree 전송 · .ics 캘린더
- **Visit**: 경로 드로잉 애니메이션 + 실제 주소 지도 (경기도 고양시 일산서구 하이파크1로91번길 8-11 1층)

## Stack
정적 HTML 한 파일 · GSAP 3.12 + ScrollTrigger · Lenis 1.1 (CDN). 빌드 없음.
배포: GitHub Pages (main 브랜치 루트, push 시 자동 배포) — https://yyy138158187-commits.github.io/gukhwa/
Cloudflare Pages로 옮길 때: GitHub 연동, Build command 없음, Output directory `/` (`_headers` 적용됨).

## 예약 설정
`index.html`의 `FORMSPREE_ID` 또는 `BOOKING_EMAIL` 값으로 접수처를 바꿉니다.

## Credits
Videos via [Mixkit](https://mixkit.co) (Mixkit License, free for commercial use) — 실제 작업물로 교체 예정인 플레이스홀더입니다.
