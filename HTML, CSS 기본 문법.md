# HTML 기본 문법

HTML(Hypertext Markup Language, 하이퍼텍스트 마크업 언어). 프로그래밍 언어는 아니고, 우리가 보는 웹페이지가 어떻게 구조화되어 있는지 브라우저로 하여금 알 수 있도록 하는 마크업 언어이다. 이는 개발자로 하여금 복잡하게도 간단하게도 프로그래밍을 할 수 있다.



**가장 기본적인 형태**

```
<head>

<title>제목</title>

</head>
```



**HTML 주석**

```
<!--(주석 내용)-->
```



**주요 HTML 요소**

```
<br> : 줄 바꾸기

<p> : 단락 바꾸기

<hr> : 가로줄

<center>...</center> : 가운데 정렬

<font>...</font> : 폰트 변경
```



###### 하이퍼텍스트

**a 태그 속성**

```
href : hypertext reference 의 약자. 연결할 주소(절대 주소 또는 삭대 주소) 지정.

target : 지정된 href 주소를 보여줄 때 널어줄 설정.

title : 마우스를 링크위에 올려두면 나오는 설명.

id : href 속성으로 링크가 아닌 현태 페이지에서 이동할 때 사용.
```



# CSS란?

CSS(Cascading Style Sheet, 종속형 시트). HTML이 뼈대라면 CSS는 이 뼈대에 살을 붙이는 작업.

CSS는 HTML 또는 XHTML에 주로 사용되며 XML에서도 사용 할 수 있다.

레이아웃과 스타일의 자유도가 높음



**HTML 요소 선택자**

```
<style>

    h2 { color: teal; text-decoration: underline; }

</style>

...

<h2>이 부분에 스타일을 적용합니다.</h2>
```



**클래스(class) 선택자**

```
<style>

    .headings { color: lime; text-decoration: overline; }

</style>

...

<h2 class="headings">이 부분에 스타일을 적용합니다.</h2>

<p>class 선택자를 이용하여 스타일을 적용할 HTML 요소들을 한 번에 선택할 수 있습니다.</p>

<h3 class="headings">이 부분에도 같은 스타일을 적용합니다.</h3>
```



**CSS 주석**

```
/* 주석 내용 */
```



