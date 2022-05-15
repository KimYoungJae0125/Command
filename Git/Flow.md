# Git Flow

## Git Repository로 파일을 옮기는 과정
### 1. WorkSpace(offline)에 있는 파일을 Local Repository(.git 폴더 : offline)으로 이동
```bash
$ git commit
```
<br>

### 2. Local Repository(.git 폴더 : offline)에 있는 파일을 Remote Repository(Github, Gitlab, ...etc : online)으로 이동
```bash
$ git push <remoteName> <branchName>
```