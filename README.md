# git practice (2018-02-10 스터디 정리)

## 1. 리눅스 명령어
* 윈도우 운영체제에서 리눅스 명령어 사용하려면 powershell을 사용
#### 1) print working directory
    pwd
#### 2) pwd에 있는 폴더 확인
    ls
#### 3) change directory
    cd
* cd 폴더명 -> 해당 폴더로 이동
* cd .. -> 상위폴더로 이동
#### 4) make directory
  mkdir 만들 폴더명


## 2. git bash 실습
* 작업디렉토리-인덱스(스테이지)-저장소

#### 1) git 저장소 초기화
    git init

#### 2) git 저장소 상태확인
    git status

#### 3) 작업 디렉토리에 파일을 추가한다.
* 다시 git status 명령어로 상태 확인해보기 -> 파일명이 빨간색으로 보임

#### 4) 스테이지 영역에 파일 추가하기
    git add
* git add 폴더명 -> 해당 폴더를 인덱스로 이동시킴
* git add . -> 전체를 이동시킴

* 다시 git status 명령어로 상태 확인 -> 파일명이 빨간색에서 초록색으로 바뀜(스테이지로 추가되었다는 뜻)

#### 5) 드디어 커밋!
    git commit -m "수정내용 설명"
* git status로 상태 확인 -> nothing to commit, working tree clean
* git log로 커밋 로그 확인 -> 해쉬값의 앞 8자리 확인


## 3. github 실습 : local repository를 remote repository로 복제(?)하기
#### 1) github 페이지 로그인 후 repository(리모트 저장소) 만들기
#### 2) bash에서 다음 코드 입력
    git remote add origin 원격저장소주소
    git push -u origin master
* 원격저장소주소는 깃헙페이지에서 확인 가능
#### 3) 아이디 및 패스워드 입력


## 4. 깃헙 사용법 간단 정리

#### 1) 처음
    git init
    git add .
    git commit -m "내용"
    git remote add origin 내원격저장소주소
    git push -u origin master

#### 2) 이후 변경사항이 있다면(수정했다면)
    git add .
    git commit -m "수정 내용"
    git push -u origin master
