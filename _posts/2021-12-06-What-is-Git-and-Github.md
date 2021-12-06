---
layout: post
title: What is Git and Github
comments: true
---

# Git과 Github

## git이란?

분산 버전관리 시스템(VCS)중 하나로, 여러 사람이 한번에 코드를 관리할 때 사용한다.

## local과 remote

git에서 파일을 저장하는 장소는 크게 local과 remote로 나눌 수 있는데, local은 내가 작업하는 장소(내 컴퓨터), remote는 git이 제공하는 장소이다.

local 저장소는 working directory, staging area, repository로 나눌 수 있는데, git add 명령어를 통해 working에서 staging으로, git commit 명령어를 통해 staging에서 local repository로 파일을 옮길 수 있으며, git reset을 통해 add를 취소할 수 있다.

git push 명령어를 통해 local repositiry에 있는 파일을 remote repository로 옮길 수 있으며, 그 반대는 git pull을 통해 실행할 수 있다.

원래 push를 할 때는 아이디와 비밀번호가 필요했지만, 최근에 비밀번호 대신 토큰이라는 새로운 기능을 사용하도록 바뀌었다.

## branch

git은 branch를 통해 마치 평행세계처럼 코드의 흐름을 분산시킬 수 있다.

이를 이용하여 따로 작업을 하다가 나중에 다른 branch와 합칠 수도 있다.

##github란?

가장 많이 사용되는 무료 git 저장소이다.

다른 사람들과 협업하거나, 오픈 소스를 배포할 때 사용할 수 있다.
