---
layout: post
title: "배운 내용"
date: 2021-12-16 00:30:14
comments: true
---

## Git

- Git이란 분산 버전관리 시스템이다
- git <명령어>를 통해서 git을 관리
- 현재 작업중인 디렉토리를 git 저장소로 지정하는 명령어  
*user $ git init*

## Git 파일 상태

- 현재 git 상태 확인  
 *user $ git status*
- git에 변경사항 반영하기
- example.py를 생성하고, 이를 commit에 반영하고 싶은 경우  
 *user $ git add example.py*
- 변경사항이 반영된 new commit 생성  
 *user $ git commit -m "add example.py"*
- commit 기록 확인하기  
 *user $ git log*

## Git Branch

- 코드의 흐름을 분산시켜 더욱 효율적인 개발 가능
- git branch (branch 이름) 을 통해 branch 생성  
 *user $ git branch (branch_name)*
- 현재 작업중인 branch를 전환  
 *user $ git checkout (ranch_name)*
- 현재 작업중인 branch를 원하는 branch에 병합  
 *user $ git merge (branch_name)*
- git branch -d (branch 이름) 을 통해 branch 삭제  
 *user $ git branch -d (branch_name)*

## GitHub

- 원격 저장소 중 대표적인 것이 GitHub
- 다른 사람들과 협업 가능

## MarkHub

- 일반 텍스트로 서식이 있는 문서 작성이 가능하다
- 문법이 몇 가지 존재한다
1. Header  
 해시태그 한 개, 두 개, 세 개로 제목 작성
2. Italic  
 내용 양 쪽에 별표 하나 혹은 언더바 하나로 기울임체 작성
3. Bold  
 내용 양 쪽에 별표 두 개  혹은 언더바 두 개로 강조체 작성
4. Strikethrough   
 내용 양 쪽에 물결표로 취소선 작성
5. Unordered List  
 하이픈, 별표로 순서없는 리스트 작성
6. Ordered List  
 숫자+. 으로 리스트 작성
7. Code  
 내용 양 쪽에 작은 따옴표로  코드 작성
8. Code Block  
 내용 앞 줄과 뒷 줄에 작은 따옴표 3개로 코드 블록 작성

## Jekyll

- Ruby 기반 정적 웹사이트 생성기
- 디렉토리에 Jekyll을 설치하면 많은 파일들이 생김
- 그 중 config.yml 파일이 존재하는데, 이 파일은 블로그의 속성을 정보로 가짐
- post 폴더에 .md 파일을 넣어서 게시글 등록 가능
- 테마는 사이트에서 적절한 것을 찾아 git을 통해 클론
- 이후 의존성을 감안하여 포스트 폴더를 제외하고 덮어쓰기 
