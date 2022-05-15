# commit
- commit을 하게 되면 스테이지에서 로컬 저장소로 이동을 하게 된다.
- 스테이지 -> .git/index
- 저장소 -> .git/HEAD
- 이후 push를 통해 Remote Repository로 파일을 복사한다.

## 사용법
### workSpace의 파일을 Local Repository로 이동
```bash
$ git commit
```
- 해당 명령어 입력 시 vi 창으로 이동 
- i 누르고 커밋 메시지 입력 후 esc 버튼 누르고 wq 입력 후 엔터
- 이후는 [push](push.md) 명령 수행
