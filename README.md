# Everyday10 Content

iOS 앱 Everyday10 의 단어 콘텐츠 레포지토리.

## 구조
- `books.json` — 책 카탈로그
- `words/<book-id>-words.json` — 책별 단어 데이터

## 새 책 추가 방법
1. `books.json` 의 books 배열에 새 항목 추가
2. `version` 필드를 +1
3. `words/<new-book-id>-words.json` 파일 추가
4. Commit & push to main

앱이 다음 실행 시 자동으로 새 카탈로그를 받아옵니다.
