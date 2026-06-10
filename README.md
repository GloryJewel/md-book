# md-book — 화폐의 미래 스테이블코인 스터디

화폐의 미래(The Future of Money) 1~2장 **발표용 정리**를 mdBook + GitHub Pages로 발행합니다.

## 구성

- `book.toml` — mdBook 설정
- `src/SUMMARY.md` — 목차
- `src/schedule.md` — 9주 스터디 일정
- `src/ch01.md` — 1장 (미래를 향한 경주)
- `src/ch02.md` — 2장 (화폐와 금융의 기초)
- `src/appendix.md` — 한 장 요약
- `.github/workflows/mdbook.yml` — GitHub Pages 자동 배포

## 배포 (최초 1회 설정)

1. GitHub 저장소 → **Settings → Pages**
2. **Build and deployment → Source**를 **GitHub Actions**로 선택
3. `main` 브랜치에 push하면 자동 빌드·배포

배포 주소: `https://gloryjewel.github.io/md-book/`

## 로컬 미리보기 (선택)

```bash
cargo install mdbook   # 최초 1회
mdbook serve --open
```
