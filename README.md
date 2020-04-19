# practice

### html 01
Hello World

```html
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>First day</title>
</head>
<body>
<div>
<p title="할만한데?">첫 날 입니다.<br>어려워요.</p>
<a href="https://github.com/woooyoung/practice"> 눌러주세요</a>
<hr />
<img src="https://avatars1.githubusercontent.com/u/63499356?s=40&v=4" width="100" heigth="100"  alt="이미지가 없습니다."/>
</div>
<div>
<video src="https://www.youtube.com/watch?v=61uXIqHCg3s" width="100" alt="영상자리입니다" />
<br />
</div>
<span>유튜브 첫 화면 첫 영상</span>
</body>
</html>
```


### html02
```html
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>2nd day</title>
</head>
<body>
<h1>둘쨰 날 입니다.</h1>
<p>아직 뭘 해야 할지 모르겠어</p>
<p>이것 저것 <br>넣어보는 중</p>
<button>Click me</button>
<p style="color:red">이건 빨간색 </p>

</body>
</html>
```


### html03
```html
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>3rd day</title>
</head>
<body>
<pre>셋째 날 입니다. 
html기초 공부 중
서버가 돌아가지 않는데 이유를 못 찾는 중
</pre>
<body style="background-color:powderblue;">
<p style="font-family:courier;">바탕체 계열</p>
<p style="font-size:160%;">폰트 사이즈 160%</p>
<p style="text-align:right;">문단 우측 정렬 </p>
</body>
</html>
```

### html04
```html
<html>
<head>
<meta charset="UTF-8">
<title>4th day</title>
</head>
<body><p>html 공부 시작 4일</p>
<p>아직 원인을 모르겠어요</p>
<h2>이건 <small>작은</small>글자</h2>
<p>이게<del>이거</del>였구나</p>

<blockquote cite="인용한 웹 주소">
인용문 입니다.
</blockquote>
<bdo dir="rtl">거꾸로 쓰는 중</bdo>
<!-- 코멘트 브라우저 상에 나타나지 않음 -->
<h1 style="background-color:rgba(255, 99, 71, 0);">rgba(255, 99, 71, 0)</h1>
<h1 style="background-color:rgba(255, 99, 71, 0.2);">rgba(255, 99, 71, 0.2)</h1>
<h1 style="background-color:rgba(255, 99, 71, 0.4);">rgba(255, 99, 71, 0.4)</h1>
<h1 style="background-color:rgba(255, 99, 71, 0.6);">rgba(255, 99, 71, 0.6)</h1>
<h1 style="background-color:rgba(255, 99, 71, 0.8);">rgba(255, 99, 71, 0.8)</h1>
<h1 style="background-color:rgba(255, 99, 71, 1);">rgba(255, 99, 71, 1)</h1>
<!-- RGB 색 참고 -->
<h1 style="background-color:#ff0000;">#ff0000</h1>
<h1 style="background-color:#0000ff;">#0000ff</h1>
<h1 style="background-color:#3cb371;">#3cb371</h1>
<h1 style="background-color:#ee82ee;">#ee82ee</h1>
<h1 style="background-color:#ffa500;">#ffa500</h1>
<h1 style="background-color:#6a5acd;">#6a5acd</h1>
<!-- HEX 색 참고 -->
<h1 style="background-color:hsl(0, 100%, 50%);">hsl(0, 100%, 50%)</h1>
<h1 style="background-color:hsl(240, 100%, 50%);">hsl(240, 100%, 50%)</h1>
<h1 style="background-color:hsl(147, 50%, 47%);">hsl(147, 50%, 47%)</h1>
<h1 style="background-color:hsl(300, 76%, 72%);">hsl(300, 76%, 72%)</h1>
<h1 style="background-color:hsl(39, 100%, 50%);">hsl(39, 100%, 50%)</h1>
<h1 style="background-color:hsl(248, 53%, 58%);">hsl(248, 53%, 58%)</h1>
<!-- HSL 색 참고 -->
</body>
</html>
```

### html05-1
```html
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>5th day</title>
<style>
body {background-color: black;}
h1   {color: yellow;}
p    {color: white;}
#p01 {
  color: grey;
}
</style>
</head>
<body>
<h1>Internal CSS: 내부 스타일 시트</h1>
<p>HTML문서내에서 head사이에 스타일을 정의하는 방법이다.</p>
<p id="p01">이 문장만 다르게 할 수도 있다.</p>
</body>
</html>
```


### html05-2
```html
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>5th day</title>
</head>
<body>
<h1>CSS: stands for Cascading Style Sheets.</h1>
<p style="color:blue; font-family: courier; font-size: 300%;"> Inline Styles(HTML 태그 내에 스타일 지정): 
스타일을 적용하고 싶은 HTML태그안에서 정의하는 방법이다.</p>
<p>External Style Sheet(외부 스타일 시트): css라는 확장자를 가진 스타일 시트 파일을 만들고 이 파일을 HTML 문서에 연결하여 사용하는 방법이다.</p>

</body>
</html>
```


### html06
```html
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>6th day</title>
<style>
div.first {
  opacity: 0.3;
}
h1 {
  background-color: lightblue;
}
</style>
</head>
<body>
<h1 style="border: 3px solid Tomato;">여섯 째 날 입니다.</h1>
<pre>현재 html,css,포토샵,일러스트
공부를 병행 하고 있어요.
할 공부가 넘치는데 시간은 빨리 가는 기분입니다.</pre> <!-- 사실 포토샵과 일러스트 위주로 하는 중 -->
<div class="first">
  <p>opacity 0.3</p> <!-- 불투명도 -->
</div>
</body>
</html>
```


### html07
```html
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>7th day</title>
<style>
body {background-color: lightgrey;}
h1   {color: royalblue;}
h3   {color: lightcoral}
p    {color: black;}
p    {text-indent: 20px;}
a {
  color: blue;
}
</style>
</head>
<body>
<h1>오늘은 한 것 들을 좀 정리 해보려 합니다.</h1>
<p>1. photoshop : 현재 cs6 version으로 공부 중 입니다.<br> 기본적인 툴 사용법을 익히고 있습니다.</p>
<p>2. illustrator : cc version으로 공부 중 입니다.<br> 위와 마찬가지로 기본적인 사용 법을 익히고 있습니다. </p>
<p>3. html,CSS : <a href="https://www.w3schools.com/html/">w3school.com</a>을 참고하여 공부 하고 있습니다.<br>
예상보다 양이 방대하여 이것 저것 경험해 보는 것에 중점을 두고 있습니다.</p>
<p>4. java : 이론 적인 부분을 공부하고 있습니다.</p>
<h3>이번 주말에 좀 더 상세하게 정리하여 내가 할 수 있는 부분과 앞으로 공부 할 부분을 파악 해보겠습니다.</h3>
</body>
</html>
```

### html08
```html
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>8th day</title>
<style>
body {background-color: white;}
h1   {color: rosybrown;}
p    {color: black;}
p    {text-indent: 10px;}
td   {color: black}
th   {color:brown}
caption {color:chocolate}
table, th, td {
  border: 2px solid black;
  border-collapse: collapse;
}
th, td {
  padding: 6px;
}
</style>
</head>
<body>
  <h1>정리해 보자면</h1>
  

  <table style="width: 50%">
    <caption>공부 한 영역</caption>
    <tr>
      <th>photoshop</th>
      <th>illustrator</th> 
      <th>html</th>
      <th>JAVA</th>
    </tr>
    <tr>
      <td>선택윤곽 도구</td>
      <td>선택,직접 선택 도구</td>
      <td>Elements</td>
      <td>특징</td>
    </tr>
    <tr>
      <td>올가미 도구</td>
      <td>올가미 도구</td>
      <td>Attributes</td>
      <td>제어</td>
    </tr>
    <tr>
      <td>빠른 선택 도구</td>
      <td>펜 도구</td>
      <td>Headings</td>
      <td>타입</td>
    </tr>
    <tr>
      <td>브러쉬 도구</td>
      <td>문자 도구</td>
      <td>Paragraphs</td>
      <td></td>
    </tr> 
    <tr>
      <td>스탬프 도구</td>
      <td></td>
      <td>Styles</td>
      <td></td>
    </tr> 
    <tr>
      <td>그라데이션 도구</td>
      <td></td>
      <td>Text Formatting</td>
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td>Links</td>
      <td></td>
    </tr>
  </table>
<p>CSS는 내용이 방대하여 추후 따로 정리해 보도록 한다.</p>

  <!--영역에 따른 내용 정리가 필요하다.-->
</body>
</html>
```

### html09
```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>9th day</title>
    <style> 
    .first {background-color: black;}
    .second {background-color: brown;}
    .third{background-color: white;}
    body{background-color: grey;}
    h1{color:yellowgreen}
    p{color:white}
    #p01{color:black}
    </style>
    
</head>
<body>
    <h1><span style="border:1px solid red">아홉</span> 째 날</h1>
    <br><div class="first"><p>visual studio code의 사용빈도가 eclipse의 사용빈도를 넘었다.</p></div>
    <br><div class="second"><p>손에 익기 전에 도움을 받는 느낌이어서 좋긴 하지만 실질적으론 도움이 되지 않을 것 같다</p></div>
    <br><div class="third"><p id=p01>1일 1commit을 목표로 하고 있지만 쉽지 않아, 습관을 들이는게 중요할 것 같다.</p></div>

</body>
</html>
```