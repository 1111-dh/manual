Git Hub 명령어
============

초기 설정
-------
    git config --global user.name [github 가입 이름]
    git config --global user.email [github 가입 이메일]

파일 업로드
--------
    git init
    git add .
    git ststus
    git commit -m "230123"
    git push -u origin master

로그 수정
-------
    git commit --amend --no-edit --date="JAN 23 23:59:00 2022 +0900"

    git commit --amend {커밋}

    git log

    git rebase -i {log에서 복사한것}
    git reabse --continue

###### i : insert
###### :wq! : 저장 후 종료