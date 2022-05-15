# ps
- 컨테이너 정보를 확인하는 명령어

<br>

## 사용법
### 현재 실행중인 컨테이너 정보 확인
```bash
$ docker ps
```

<br>

### 현재 실행중인 컨테이너의 ID 확인
```bash
$ docker ps -q
```

<br>

### 로컬에 있는 모든 컨테이너 정보를 보여준다.
```bash
docker ps -a
```

<br>

### 로컬에 있는 모든 컨테이너의 ID를 보여준다.
```bash
docker ps -aq
```