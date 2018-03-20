# git practice (2018-02-10 스터디 정리)

### 1. 리눅스 명령어
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

### 2. git bash 실습
* 작업디렉토리-인덱스(스테이지)-저장소

### 3. github 실습 : local repository를 remote repository로 복제(?)하기
#### 1) github 페이지 로그인 후 repository 만들기
#### 2) bash에서 다음 코드 입력(+ github 아이디/패스워드 입력)
    git remote add origin 원격저장소주소
    git push -u origin master
