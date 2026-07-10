# billigo-landing

빌리고(BILLIGO) 서비스 소개 랜딩 페이지 — **순수 HTML + CSS + JS** (빌드 불필요).

- `index.html` — 전체 마크업 (히어로 · 문제 · 작동 방식 · 핵심 기능 · 스크린샷 · 수수료 · 보안 · CTA · 푸터)
- `styles.css` — 스타일 (브랜드 팔레트: 파란색 + 하얀색, 노란색은 액센트로 듬성듬성)
- `main.js` — lucide 아이콘 초기화
- `shots/` — 실제 앱 스크린샷 (billigo-client-pwa에서 캡처)
- 폰트: Pretendard(OFL, 상업 이용 가능) · 아이콘: lucide(ISC) — 둘 다 CDN

모든 경로가 **상대경로**라 `username.github.io/billigo-landing/` 하위 경로에서도 안 깨진다.

## 로컬 미리보기

```bash
python3 -m http.server 8080   # http://localhost:8080
```

## GitHub Pages 배포

1. 이 폴더를 push (기본 브랜치 `main`)
2. GitHub → **Settings → Pages → Source = "Deploy from a branch" → main / (root)**
3. 잠시 뒤 `https://<계정>.github.io/billigo-landing/` 로 공개

`.nojekyll` 포함(원본 그대로 서빙).
