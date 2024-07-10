# Git 필기
## 커밋/푸쉬 규칙
* 꼭! 항상! 절대!  `add`, `commit`, `push`는 최상단 폴더에서 작업하기

## 내가 지금 사용하고있는 컴퓨터에서 처음으로 깃 작업을 할 때 1번만 하면 되는 작업

### `git config`
* 계정설정
    * `git config --global user.name [나의 유저 네임]`
    * `git config --global user.email [나의 깃헙 이메일]`
* 계정확인
    * `git config --global user.email`
    * `git config --global user.name`
    * 잘못 썼을 때는 덮어쓰기

## 처음으로 깃을 시작할 때 1번만 하면 되는 작업

### `git init`

### `git remote`
* `git remote add origin [나의 깃헙의 원격저장소(github) 레포 주소]`

* `git remote -v`: 내가 등록한 원격 저장소 레포 주소 확인

* `git remote remove origin`: 등록한 원격저장소 삭제

## working directory에 변동이 있을 때마다 하는 작업

### `git add`

### `git commit`

### `git push`

## 상태확인
### working directory에서
- `git status`
    - add 전/후

### staging area에서 (.git)
- `git status`
    - 추적이 되고 있는지만 확인 가능
- `git log`
    - commit 이후에만!!!
    - `--oneline`: 간결하게 보여줌
    - 내림차순