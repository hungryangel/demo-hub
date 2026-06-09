# 벨녹웍스 데모 사이트 (demo.velnoc.com)

Cloudflare Pages 정적 사이트. 벨녹웍스 포트폴리오 데모 갤러리.

## 배포 정보
- **URL**: https://demo.velnoc.com
- **플랫폼**: Cloudflare Pages (GitHub 자동 배포)
- **저장소**: https://github.com/hungryangel/demo-hub
- **브랜치**: main

## Git 권한
- `git push origin main --force` 허용 — 이 프로젝트에서 명시적으로 허용된 작업
- 커밋 후 자동 push 허용 (사용자 요청 시)

## 절대 건드리지 말 것
- jungsooksung.vercel.app
- olimen-brand-compass.pages.dev
- hej-film-page.pages.dev
- florist.demo.velnoc.com
- velnoc.com
- site.velnoc.com

## SEO 차단 유지
- `_headers` 에 `X-Robots-Tag: noindex, nofollow` 반드시 유지
- `index.html` 에 `<meta name="robots" content="noindex, nofollow">` 반드시 유지

## 기술 스택
- 순수 HTML/CSS/JS (빌드 도구 없음)
- WebGL GLSL 히어로 셰이더 (velnoc-digital-canvas 원본 파라미터 1:1)
- Pretendard Variable 웹폰트
