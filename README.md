# study_html
### HTML의 요소
    <p> You are better </p>
    <태그이름> 콘텐츠 </태그이름>

1) 여는 태그(Opening tag): 요소의 이름(p)과 열고 닫는 꺽쇠 괄호로 구성된다.
2) 닫는 태그(Closing tag): 요소의 이름(p) 앞에 슬래시(/)가 있다.
3) 내용(Content): 요소의 내용이며, 단순한 텍스트를 의미한다.
<br></br>
### HTML 요소의 종류
> #### 블록 요소 (block element)
- p, h, ul, ol, div, form, table,... 등
- 코드 상에 한 줄로 이어 써도 화면 상에서는 앞 뒤 요소 사이에 새로운 줄을 만들어서 나타난다.
  1) 코드
  ```<p>apple</p><p>banana</p>```
  2) 화면
		<p>apple</span><p>banana</p>

- 영역이 정확히 구분되어 있기 때문에, width, height 속성을 수정할 수 있다.
- margin-top, margin-bottom 속성도 잘 적용된다.
- padding-top, padding-bottom 속성도 잘 적용된다.
- div 태그
  1) 다른 HTML 요소들을 하나로 묶는 데 사용되는 대표적인 블록 요소이다.
  2) 주로 여러 요소들의 스타일을 한 번에 적용하기 위해 div 태그를 사용한다.
<br></br>	
> #### 인라인 요소 (inline element)
- span, a, img, strong, em, ... 등
- 새로운 줄을 만들지 않고 작성한 단락 내에 나타난다.
- 안에 있는 내용만큼만 영역을 차지한다.
  1) 코드
  ```<strong>apple</strong><em>banana</em>```
  2) 화면
<strong>apple</strong><em>banana</em>
- 영역이 불분명하기 때문에 width와 height를 임의로 부여할 수 없다(img 태그 제외)
- margin-top, margin-bottom 속성도 적용되지 않는다.
- padding-top, padding-bottom 속성도 적용되지 않는다.
- span 태그
	1. 텍스트의 특정 부분을 묶는 데 자주 사용되는 요소이다.
	2. 주로 텍스트의 특정 부분에 따로 다른 스타일을 적용하기 위해 사용한다.
<br></br>
 > #### 인라인-블록 요소(inline-block element)
- button, input, select, ...
- inline 요소와 동일한 영역(내용만큼)을 가지지만 width와 height를 설정할 수 있다.
- margin-top, margin-bottom 속성도 잘 적용된다.	
- padding-top, padding-bottom 속성도 잘 적용된다.
<br></br>
### HTML 주석
	<!-- 주석 -->: Ctrl + Shift + /
		
