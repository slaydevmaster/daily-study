# Daily Study

매일 공부할 주제를 모아두는 개인 학습 허브.

**Live:** https://slaydevmaster.github.io/daily-study/

## 구조

```
daily-study/
├── index.html              # 메인 허브 (주제 목록)
├── pairs-trading/
│   └── index.html          # 페어트레이딩 14일 커리큘럼
└── README.md
```

진행도는 브라우저 `localStorage`에 저장됩니다. 기기/브라우저별로 별도 저장돼요.

## 새 주제 추가하기

1. 루트에 폴더 하나 만들기 (예: `economy/`)
2. 그 안에 `index.html` 생성
3. 메인 `index.html`의 카드 섹션에서 해당 주제 카드의 `card-coming` 클래스 제거하고 `href` 연결
4. 필요하면 진행도 계산 스크립트도 추가

## 로컬에서 보기

그냥 `index.html` 더블클릭하거나:

```bash
python3 -m http.server 8000
# http://localhost:8000
```

## 배포

GitHub Pages로 자동 배포됩니다.
Settings → Pages → Source: `main` branch / root
