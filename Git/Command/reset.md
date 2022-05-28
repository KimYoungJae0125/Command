# reset
- commit을 취소하는 명령어입니다.
- git log를 사용하면 commitId를 알 수 있습니다.
 
## 사용법
### commitId 시점으로 변경
```bash
$ git reset <commitId>
```
- commitId 시점으로 돌아갑니다.
- 파일은 변경되지 않습니다.

### commitId 시점으로 커밋 및 파일 변경
```bash
$ git reset <commitId> --hard
```
- commitId 시점으로 돌아가고 파일도 그 시점에 있던 파일로 변경됩니다.
- 삭제 된 파일을 복구할 때 사용합니다.
