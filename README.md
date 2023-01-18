# git-training

git-training

Git 원리 - 분산 저장 시스템
 서버나 클라이언트나 Clone을 가지고 있다면 이를 통해 버전 관리 및 복구가 가능하다.

github Create Repository & Commit (git-training)

github issues - 게시판 개념

git config - 사용자 설정

- git config --global user.name "Hodu-C"
- git config --global user.email za4758@icloud.com

git init - 초기화 현재 디렉토리를 로컬 저장소로 사용한다.

git add <filename> - 변경된 파일을 Staging Area로 옮긴다.
 - ex)git add . git add *.c
 
git commit -m "" - 로컬 저장소에 수정된 내용 저장
 - ex)git commit -m "start"
 
git clone <url> - git 저장소 복제
 - ex) git clone https://github.com/Hodu-C/git-training (git-training 이라는 디렉토리를 만들고 그 하위에 .git 디렉토리를 생성하고 가장 최신버전을 복제한다.)
 - ex) git clone https://github.com/Hodu-C/git-training.git
 - ex) git clone https://github.com/Hodu-C/git-training <filename> (뒤에 filename을 적어주어 다른 이름으로 디렉토리 생성 가능)
 - ex) git clone https:// or git:// or SSH 프로토콜 사용 등의 형식으로 사용할 수 있다.

git push - 로컬 저장소 -> 원격 저장소로 변경 사항 저장
= fetch + merge
git pull - 원격 저장소 -> 로컬 저장소 변경 사항 저장

git fetch - 원격 저장소에 변경 사항을 다운로드

git merge - 다운로드된 변경 사항 적용

Q1. 충돌 및 오류 처리는 어떻게 할까? ex)원격 저장소와 변경 사항을 맞추지 않고, 여러 사람이 동시에 개발.
 - 병합하여 새로운 브랜치 생성. 아직 이해 안됨.
 
Q2. 원격 저장소의 이름이 바꼇거나, 없어져서 찾을 수 없을 때 어떻게 할까?
 - 좀더 공부하고 답해보자.
 
