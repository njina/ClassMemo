# position

**html 유효성 검사**  https://validator.kldp.org/



absolute는 상위 요소를 기준으로 따라간다. 부모만 따라가는거야. 형제는 안 따라가. 

z-index는 내가 사용하는 수치가 아무리 높아도, 자신의 부모z-index가 낮으면.......

z-index는 항상 부모의  수치를 따른다.

*position에 들어가는 내용은 철저한 계산 아래 사용해야한다.*



ex) 이미지 위에 옆으로 옮기는 화살표 이미지는 position을 사용하여 제작한 것임. 화살표는 absolute, 그 아래 광고배너는 relative.

ex) 쇼핑몰 판매 순위 보여주는 div. 

**css pie**  
http://css3pie.com/  > 다운로드 받기 > 압축풀기 > ~/a_basic/ie으에 폴더 넣기

**벤더프리픽스 prefix**
: 새로나온 css기술에서 브라우저가 테스트용으로 기능을 부여하고도 일반 요소로 사용이 안 될 때, 강제로 사용(수행)할 수 있도록 처리하는 기능.
앞 뒤로 벤더(-)를 달고 내부에 해당 브라우저의 형식을 기입하도록 처리.;
=새로나온 기술이지만 아직 지원을 하지 않을 때 강제적으로 수행하게 하는 기능이다.
[예시]
position: -webkit-stickcy : 크롬,사파리,크로미움 엣지
position: -moz-stickcy : 모질라(파이어폭스)
position: -ms-stickcy : 마이크로 소프트
position: -o-stickcy : 오페라 



# layout 어제이어서 짜기

**IR기법**
: 보여주고자 하는 이미지는 나타나고 그 해석이 되는 설명은 숨김 처리하는 기법. 넘치는 내용은 안 보여주겠다. 
```overflow:hidden; ``` 넘치는 내용은 숨겨라



```inherit``` 
: 부모값 그대로 똑같이 쓰겠습니다.  부모가 1920px이면 나도 1920px. 만약 부모값이 바뀌게 되면 자식 값을 안 바꿔도 부모값만 바꾸면 자식값은 알아서 반영이 되지롱~





눈으로 보이는 영문 대문자  쓰는법



---

---



# align

# rotate, scale

# gradient
