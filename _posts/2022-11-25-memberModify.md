---
title: "웹페이지 로그인"
categories: web_programming
tags: [a_major_class, modify, php]
toc: true
author_profile: false
sidebar:
    nav: "docs"
---
# 웹페이지 회원 정보 수정
**[전공수업]** 웹프로그래밍 수업 복습
{: .notice--danger}

자바스크립트

- js/member_modify.js

회원 정보 수정 페이지

- member_modify_form.php

기능 페이지

- member_modify.php

---

## member_modify_form.php

회원정보를 수정하기 위한 폼

입력

- 아이디
- 비밀번호
- 비밀번호 확인
- 이름
- 이메일

버튼

- 저장하기
- 취소하기

## member_modify.php

members 테이블의 회원정보 업데이트

수정 완료 시 인덱스 페이지로 이동

## member_modify.js

회원정보 수정에 필요한 함수 정의

- check_input() : 반드시 입력해야하는 정보가 입력되었는지 확인
- reset_form() : 입력된 정보 초기화