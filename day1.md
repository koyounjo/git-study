# 처음 시작하는 HTML과 CSS
## 개발 환경 설정
* 모던 웹 브라우져 설치(크롬, 파이어폭스)  
* 확장 프로그램 설치
    * web developer  
    * headingsmap  
    * OpenWax  
    * WhatFont
* visual studio code 설치  
* 확장 프로그램
    * Live Server  
    * Auto Close Tag
    * Auto Rename Tag  
    * JS-CSS-HTML Formatter  
    * Korean Language Pack for Visual Studio code  
    * Markdown Preview Enhanced  
    * Markdown Preview Github Styling

## CLI 명령어
* mkdir(디렉토리 생성)
* cd(디렉토리 이동)  
* rmdir(디렉토리 삭제)
* touch(빈문서 생성)
* echo(파일 생성과 내용 입력)
* cp(파일 복사)
* mv(파일 이동 및 이름 변경)

## Git의 활용
* git init : 저장소 초기화
* git status : 상태 확인  
* git add : index로 이동(스테이지 이동)
* git commit -m : 커밋 및 메시지
* git commit -am : 한번 커밋한 경우 다시 커밋시 add 없이
* git commit --amend : 커밋 메시지 수정(HEAD 위치에서)
* git push - 원격 저장소로 전송

## 웹표준과 웹접근성
* 웹표준  
  * HTML(구조)
  * CSS(디자인)
  * Javascript(동작)
* 웹접근성
    * 장애와 비장애 모두를 만족시키기 위한 노력

## HTML 기본 문법
### index.html
``` HTML
<!DOCTYPE html>
<html lang="ko-KR">

<head>
    <meta charset="UTF-8">
    <title>기본구조</title>
    <link rel="stylesheet" href="css/style.css">
</head>

<body>
    <h1>커피</h1>
    <p>커피는 마시면 기운이 솟아나요.</p>
</body>

</html>
```
### style.css
``` CSS
@charset "utf-8";
h1 {
    background-color: yellow;
    margin-bottom: 0px;
}

p {
    background-color: pink;
    margin-top: 0px;
}
```