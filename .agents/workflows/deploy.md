---
description: 수정된 코드를 버전업하고 Firebase 및 GitHub에 배포합니다.
---

1. 현재 index.html 파일의 버전 번호를 자동으로 0.0.1 올립니다.
// turbo
2. npx firebase-tools deploy --only hosting
// turbo
3. git add .
// turbo
4. git commit -m "Auto deploy and version up"
// turbo
5. git push -f origin main
