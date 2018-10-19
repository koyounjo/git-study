#### Day 3 요약정리
## 메인 메뉴 레이아웃 및 디자인
* 디스플레이 속성의 flex 값을 지정해서 가로 방향 배치
* 글자 크기(font-size) 굵기(font-weight), 그림자(text-shadow)
* 웹폰트 활용
  * [구글 웹폰트](https://fonts.google.com/)
  * Noto Sans KR(Regular, Bold)
  * @import url(폰트경로)

## 새소식 마크업 및 디자인
이미지의 캡션을 지정할 수 있는 새로운 HTML5 요소인 figure 요소를 활용
* h2: 새소식 제목
* time: 날짜 및 시간
* p: 새소식 본문
* figure, figcaption - 캡션 컨테이너  
이미지 요소의 width를 조절할 경우 반드시 height 속성의 값을 auto로 지정할 것

## 추천 영상 마크업 및 디자인
iframe 요소를 이용한 비디오 콘텐츠 삽입  
유투브에서 원하는 동영상을 퍼가기 기능으로 복사해서 삽입한다. iframe의 경우 크기 조절을 위해 컨테이너를 랩핑해서 사용한다.
``` HTML
<div class="media-container">
                <div class="iframe-wrapper">
                    <iframe width="560" height="315" src="" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
                </div>
            </div>
```
iframe 비디오의 크기를 유연하게 조절하고자 할 경우 iframe-wrapper 영역의 가로 크기는 100%로 설정하고 높이인 height 속성의 값은 0으로 할당한다.  
그리고 padding-top 속성의 값을 비디오 크기의 가로 세로 비율에 따른 백분율 값으로 할당한다. 만약 비디오가 4대3 비율일 경우 가로는 100% 세로는 75%로 지정한다.  
iframe 영역의 경우 position 속성의 값을 absolute로 설정하고 width와 height를 100%로 지정한다.


## 푸터 마크업 및 디자인
* address: 주소 영역
* small: 저작권 정보(특수문자를 사용할 경우 특수문자 이름이나 번호를 사용하여 마크업한다. 예 '&copy')

[CSS animation](https://www.webdesignerdepot.com/2014/05/8-simple-css3-transitions-that-will-wow-your-users/)  
[모바일 브라우져 검사](http://troy.labs.daum.net/)  
[W3Schools](https://www.w3schools.com/)  
[김데레사 유투브](https://www.youtube.com/user/seulbinim)