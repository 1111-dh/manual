๐ปGit Hub ๋ช๋ น์ด
============

๐์ด๊ธฐ ์ค์ 
-------
    git config --global user.name [github ๊ฐ์ ์ด๋ฆ]
    git config --global user.email [github ๊ฐ์ ์ด๋ฉ์ผ]

๐ํ์ผ ์๋ก๋
--------
    git init
    git add .
    git ststus
    git commit -m "230123"
    git push -u origin master

๐๋ก๊ทธ ์์ 
-------
    git commit --amend --no-edit --date="JAN 23 23:59:00 2022 +0900"

    git commit --amend -m {์ปค๋ฐ ๋ฉ์ธ์ง}

    git log

    git rebase -i {log์์ ๋ณต์ฌํ๊ฒ(branch)}
    git reabse --continue

๐๋์ฉ๋ ํ์ผ(LFS)
-------
์ค์น

    brew install git-lfs
    
ํ์ผ ๊ฒฝ๋ก์์

    git lfs install
    
    // psd ํ์ฅ์๋ฅผ ๊ฐ์ง ํ์ผ๋ค์ LFS๋ก ๊ด๋ฆฌ
    git lfs track "*.psd"

    // ํน์  ํ์ผ์ LFS๋ก ๊ด๋ฆฌ
    git lfs track "images/MainLogo.psd"
    
    git add .gitattributes
๐ธ๊ธฐํ
---
###### i : insert
###### :wq! : ์ ์ฅ ํ ์ข๋ฃ
