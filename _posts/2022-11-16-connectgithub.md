---
title: "로컬파일 깃허브 연결"
categories: github
tags: github
toc: true
author_profile: false
sidebar:
    nav: "docs"
---
깃허브의 저장소와 연결하여 로컬파일 업로드하기

1. 저장소 생성 (웹페이지에서)
2. 생성 후 초기화면에 나오는 지시사항대로 하기

## 저장소에 업로드하기

1. git bash 실행
2. 로컬 저장소로 설정할 위치로 이동
    1. cd 로컬 저장소 위치
3. git 초기화 (master branch 생성)
    1. git init
4. 저장소와 로컬폴더 연결
    1. git remote add origin 저장소_경로
        1. git remote add : 원격 저장소와 연결
        2. origin : 로컬에서 저장소를 지칭하는 것
5. 로컬 파일 저장소에 저장하기
    1. git add
    2. git commit
    3. git push {repository} {branch}
        1. commit된 파일 push
6. 짜잔! 완료! ヾ(≧▽≦*)o