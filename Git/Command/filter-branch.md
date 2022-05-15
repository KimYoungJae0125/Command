# filter-branch

## 사용법
### branch에 존재하는 특정 파일의 히스토리만 제거
  ```bash
  $ git filter-branch --force --index-filter "git rm --cached --ignore-unmatch <경로/fileName>" --prune-empty --tag-name-filter cat -- --all
  ```
