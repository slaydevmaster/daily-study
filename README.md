# Daily Study

매일 공부할 주제를 모아두는 개인 학습 허브.

**Live:** https://slaydevmaster.github.io/daily-study/

## 구조

```text
daily-study/
├── index.html              # 메인 허브 (주제 목록 + 통합 진행도)
├── english/
│   └── index.html          # 영어회화 90일 로드맵 + 일일 교재
├── pairs-trading/
│   ├── index.html          # 페어트레이딩 14일 커리큘럼
│   └── audio/
└── README.md
```

진행도는 브라우저 `localStorage`에 저장됩니다. 기기/브라우저별로 별도 저장됩니다.

## English Conversation · 90 Days

- 기준: 한국어 모국어, 회화 출력 CEFR A1 초반
- 학습량: 하루 약 2시간
- 목표: 익숙한 생활 주제에서 영어 문장을 스스로 만들고 20~30분 대화를 유지하는 능력
- 운영: 90일 전체 로드맵은 미리 제공하고, 상세 일일 교재는 전날 학습 결과를 반영해 순차적으로 추가
- 진행도 키: `en_done`

## Pairs Trading

- 14일 커리큘럼
- 진행도 키: `pt_done`

## 새 주제 추가하기

1. 루트에 폴더 하나 만들기 (예: `economy/`)
2. 그 안에 `index.html` 생성
3. 메인 `index.html`의 카드 섹션에 링크 추가
4. 필요하면 진행도 계산 스크립트도 추가

## 로컬에서 보기

```bash
python3 -m http.server 8000
# http://localhost:8000
```

## 배포

GitHub Pages로 자동 배포됩니다.
Settings → Pages → Source: `main` branch / root
