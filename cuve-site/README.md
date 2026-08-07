# CUVE Website — 설정 가이드

이 ZIP 안의 모든 파일을 GitHub 레포지토리에 업로드하세요.

자세한 사용법은 별도로 제공된 "CUVE-운영가이드.html" 파일을 참고하세요.
(GitHub 업로드, Netlify 배포, 어드민 사용법, 디자인 수정법, Contact Us 폼 설정,
폰트/색상/배경 변경법 등이 전부 포함되어 있습니다.)

## 파일 구조
```
cuve-site/
├── index.html          ← 메인 웹사이트 (Contact Us 폼 포함)
├── netlify.toml
├── admin/
│   ├── index.html
│   └── config.yml      ← ★ repo: 값을 본인 GitHub 아이디로 수정 필요
├── data/
│   ├── reels.json
│   └── works.json
└── images/
```

## Contact Us 폼 안내
Netlify Forms 를 사용합니다 (무료, 별도 서버 불필요).
배포 후 Netlify 대시보드 → Forms 탭에서 자동으로 "contact" 폼이 인식됩니다.
이메일 알림 설정 방법은 운영가이드 Ch.14 참고.
