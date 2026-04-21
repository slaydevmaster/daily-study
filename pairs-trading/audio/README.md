# Audio files

이 폴더에 오디오 강의 파일을 넣으면 해당 날짜 카드의 🎧 오디오 버튼이 자동으로 재생합니다.

## 파일명 규칙

```
day-01.mp3    ← 1일차
day-02.mp3    ← 2일차
...
day-14.mp3    ← 14일차
```

## 활성화하는 법

1. 파일을 이 폴더에 `day-XX.mp3` 이름으로 넣기
2. 상위 폴더의 `index.html` 파일을 열어서 `DAYS` 배열에서 해당 날짜 객체에 아래 한 줄 추가:
   ```js
   audio:'./audio/day-XX.mp3',
   ```
3. `git add . && git commit -m "add day X audio" && git push`

## 참고

- 포맷: MP3 권장. (OGG, WAV, M4A도 대부분 브라우저에서 재생됩니다)
- GitHub repo 단일 파일 용량 제한: 100MB. 권장 <25MB.
- 저작권 있는 자료 업로드 전 확인하세요. (public repo이므로 아무나 접근 가능)
