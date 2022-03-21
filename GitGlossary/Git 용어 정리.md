# <center>Git 용어 정리</center>
- Repository
  - 스테이지에서 대기하고 있던 파일들을 버전으로 만들어 저장하는 곳
    - 원격 저장소(Remote Repository), 로컬 저장소(Local Repository)로 나뉨
      1. 원격 저장소(Remote Repository)
         - 여러 사람들이 함께 공유하기 위한 저장소
      2. 로컬 저장소(Local Repository)
         - 내 PC에 저장되는 개인 저장소(타인하고 공유 안 됨)
         - 로컬 저장소를 만드는 두 가지 방법
           1. 새로운 저장소를 만든다.
           2. 원격 저장소(Remote Repository)를 clone 한다.
- Workspace
  - 내 작업 공간
- Working Tree(Working Directory)
  - 저장소의 어느 한 시점을 바라보는 작업자의 현재 시점
  - 파일 수정, 저장 등의 작업을 하는 디렉토리
- SnapShot
  - 특정 시점의 상태를 의미
  - 특정 시점에서 특정 파일에 어떤 내용이 기록되어 있었는지, 해당 파일의 폴더 구조는 어떻게 되었는지, 어떤 파일이 존재했었는지 등의 저장소의 정보를 확인 할 수 있다.
  - Git에서는 commit을 실행 시 스냅샷이 저장된다.
- Branch
  - 작업을 저장하는 공간
- Checkout
  - 현재 선택된 Branch 말고 다른 Branch로 이동
- Staging Area
  - 로컬 저장소에 commit 하기 전 commit을 준비하는 위치(원격 저장소는 commit 후 push를 해야한다)
  - Unstaged와 Staged가 있는데 Staged에 있는 파일만 commit이 가능하다.
- Commit
  - Staged(변경된 파일)에 있는 파일들을 로컬 저장소에 저장하는 작업
- Head
  - 현재 작업중인 Branch를 가리킨다(파일 명 옆에 써있는 Branch)
  - Commit하면 해당 Head로 이동

