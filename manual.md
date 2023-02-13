💻Git Hub 명령어
============

📌초기 설정
-------
    git config --global user.name [github 가입 이름]
    git config --global user.email [github 가입 이메일]

📌파일 업로드
--------
    git init
    git add .
    git ststus
    git commit -m "230123"
    git push -u origin master

📌로그 수정
-------
    git commit --amend --no-edit --date="JAN 23 23:59:00 2022 +0900"

    git commit --amend -m {커밋 메세지}

    git log

    git rebase -i {log에서 복사한것(branch)}
    git reabse --continue

📌대용량 파일(LFS)
-------
설치

    brew install git-lfs
    
파일 경로에서

    git lfs install
    
    // psd 확장자를 가진 파일들을 LFS로 관리
    git lfs track "*.psd"

    // 특정 파일을 LFS로 관리
    git lfs track "images/MainLogo.psd"
    
    git add .gitattributes
🎸기타
---
###### i : insert
###### :wq! : 저장 후 종료
