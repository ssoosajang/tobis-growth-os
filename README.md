# Tobis Growth OS

**2천만 예산 지키는 7일 창업 검증 시스템**

Tobis Lab · Private Beta v2.4

## URL 구조
- `/` — 랜딩 페이지 (공개)
- `/app` — 대시보드 (7일 체크인 + BMC + AI 자기 채점)

## 구조
```
tobis-growth-os/
├── index.html      랜딩 페이지
├── app/
│   └── index.html  대시보드 본체
├── vercel.json     배포 설정
├── robots.txt
└── sitemap.xml
```

## 배포
Vercel에 연결 시 `vercel.json`의 `cleanUrls` + `/dashboard → /app` redirect 설정이 자동 적용됩니다.

## 라이선스
© 2026 Tobis Lab · Private Beta
