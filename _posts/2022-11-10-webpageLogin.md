---
title: "웹페이지 로그인"
categories: WebProgramming
tags: [php, login, a major class]
author_profile: false
sidebar:
	nav: "docs"
---
# 웹페이지 로그인
**[전공수업]** 웹프로그래밍 수업 복습
{: .notice--danger}

자바스크립트

- js/login.js

로그인 페이지

- login_form.php

기능페이지

- login.php
- logout.php

---

## login_form.php

로그인을 하기 위한 아이디와 비밀번호를 입력할 수 있는 폼

입력

- login.php
- 아이디 - text
- 비밀번호 - password
- 제출 - 이미지

## login.php
회원정보가 저장된 테이블에 아이디 존재 여부 확인 후 존재하는 경우 비밀번호가 일치한지 확인후 일치하면 로그인 된 회원정보 세션으로 저장

아이디 존재 여부

- 존재
    - 비밀번호 일치 확인
- 없음
    - 로그인 폼으로 이동

비밀번호 일치 여부

- 일치
    - 회원정보 세션으로 저장 후 index.php로 이동
- 불일치
    - 로그인 폼으로 이동

## login.js
check_input() 함수 정의

check_input() : 로그인을 위한 정보가 모두 입력되었는지 검사