<h1 align='center'>📚 HTML BASIC SYNTAX 📚</h1>

<details><summary><h4>refer</h4></summary>

- [**MDN Web Docs**](https://developer.mozilla.org/ko/)

- [**W3Schools**](https://www.w3schools.com/)

</details>

---

## 📖 HTML

- **HTML이란 무엇인가**
  - **정의**
    - **H**yper-**T**ext **M**arkup **L**anguage
    - 데이터의 논리적인 구조를 명시하기 위한 규칙을 정의하는 마크업 언어
    - 데이터가 화면에 출력되는 형식을 정의하는 마크업 언어
  
  - **`CSS`, `Java Script` 와의 상관관계**
    - `HTML` : 설계도
    - `CSS` : 디자인
    - `Java Script` : 기능

- **태그**
  - **정의** : HTML을 기술하기 위하여 사용하는 명령어의 집합
  
  - **유형**
    - block tag
      - 내용이 점하는 공간이 위치한 행 전체를 영역으로 가짐
      - 하위 태그로 block tag, inline tag 를 모두 취할 수 있음
    
    - inline tag
      - 내용이 점하는 공간만을 영역으로 가짐
      - 하위 태그로 inline tag 만을 취할 수 있음
    
  - **속성** : 태그에 옵션을 설정하는 명령어의 집합

- **구조**
  - `<html>` : 하나의 html 문서를 묶는 태그임
  
  - `<head>` : html 문서의 메타 정보를 하위 태그로 가지는 태그임
  
  - `<body>` : 화면에 출력되는 내용에 관한 정보를 하위 태그로 가지는 태그임

---

## 🏛 Logical Division Tag

<details><summary><h4>머릿말</h4></summary>

- `<header>`
  - **기능** : 머릿말 영역을 설정하는 상위 시멘틱 태그
  
  - **유형** : block tag

</details>

<details><summary><h4>메인 페이지</h4></summary>

- `<main>`
  - **기능** : 메인 페이지 영역을 설정하는 상위 시멘틱 태그
  
  - **유형** : block tag
  
  - **하위 태그 목록**
    - `<section>` : 후술
    - `<article>` : 후술

- `<section>`
  - **기능** : 단일 주제 영역을 설정하는 상위 시멘틱 태그
  
  - **유형** : block tag
  
  - **`<article>` 태그와 차이점**
    - 통상적으로 하나의 대주제를 설정하는 태그로서 사용됨
    - 반드시 `<article>` 의 상위에 자리해야 하는 것은 아님

- `<article>`
  - **기능** : 단일 주제 영역을 설정하는 중위 시멘틱 태그
  
  - **유형** : block tag
  
  - **`<section>` 태그와 차이점**
    - 통상적으로 대주제의 하위 주제들을 구분하는 태그로서 사용됨
    - 반드시 `<section>` 의 하위에 자리해야 하는 것은 아님

</details>

<details><summary><h4>사이드바</h4></summary>

- `<nav>` (**NAV**igation links)
  - **기능** : 사이드바를 구성하는 중위 시멘틱 태그
  
  - **유형** : block tag
  
  - **`<aside>` 태그와 차이점**
    - 통상적으로는 목차를 구성하는 태그로서 사용됨
    - 반드시 메인 페이지의 좌우에 자리해야 하는 것은 아님
    - 간혹 `<header>` 태그의 하위 태그에 자리하기도 함

- `<aside>`
  - **기능** : 사이드바를 구성하는 중위 시멘틱 태그
  
  - **유형** : block tag
  
  - **`<nav>` 태그와 차이점**
    - 통상적으로는 광고 등을 구성하는 태그로서 사용됨
    - 통상적으로는 메인 페이지의 좌우에 자리함
    - 간혹 `<main>` 태그의 하위 태그에 자리하기도 함

</details>

<details><summary><h4>꼬릿말</h4></summary>

- `<footer>`
  - **기능** : 꼬릿말 영역을 설정하는 상위 시멘틱 태그
  
  - **유형** : block tag

</details>

<details><summary><h4>기타</h4></summary>

- `<div>` (**DIV**ition)
  - **기능** : 단락을 구분하는 하위 시멘틱 태그
  
  - **유형** : block tag
  
  - **여타 태그와의 차이점**
    - `<p>` 태그와 차이점 : 상하여백이 설정되어 있지 않음
    - `<span>` 태그와 차이점 : inline tag 임

- `<span>`
  - **기능** : 단락을 구분하는 하위 시멘틱 태그
  
  - **유형** : inline tag
  
  - **여타 태그와의 차이점**
    - `<p>` 태그와 차이점 : 상하여백이 설정되어 있지 않음
    - `<div>` 태그와 차이점 : inline tag 임

</details>

---

## ✂ Contents Tag

<details><summary><h4>List</h4></summary>

- `<ul>` (**U**norderd **L**ist)
  - **기능** : 순서가 없는 목록을 하위 태그로 가지는 시멘틱 태그
  
  - **유형** : block tag
  
  - **하위 태그 목록**
    - `<li>` (**L**ist **I**tem) : 목록 기입

- `<ol>` (**O**rdered **L**ist)
  - **기능** : 순서가 있는 목록을 하위 태그로 가지는 시멘틱 태그
  
  - **유형** : block tag
  
  - **하위 태그 목록**
    - `<li>` (**L**ist **I**tem) : 목록 기입

- `<dl>` (**D**efinition **L**ist)
  - **기능** : 제목과 설명이 쌍을 이루는 목록을 하위 태그로 가지는 시멘틱 태그
  
  - **유형** : block tag
  
  - **하위 태그 목록**
    - `<dt>` (**D**efinition **T**itle) : 목록의 제목 기입
    - `<dd>` (**D**efinition **D**escription) : 목록의 설명 기입

</details>

<details><summary><h4>Table</h4></summary>

- `<table>`
  - **기능** : 표를 구성하는 시멘틱 태그
  
  - **유형** : block tag
  
  - **하위 태그 목록**
    - `<th>` (**T**able **H**eader) : 칼럼명 기입
    - `<td>` (**T**able **D**escription) : 내용 기입
    - `<tr>` (**T**able **R**ow) : 개행

</details>

<details><summary><h4>Image</h4></summary>

- `<figure>`
  - **기능** : 이미지 영역을 구성하는 시멘틱 태그
  
  - **유형** : block tag
  
  - **하위 태그 목록**
    - `<img/>` : 후술
    - `<figcaption>` : 이미지의 주석을 기입함

- `<img/>`
  - **기능** : 이미지 주소를 기입함
  
  - **유형** : inline tag
  
  - **속성 목록**
    - `src` : 이미지 주소 입력
    - `alt` : 이미지 대체 텍스트 입력

</details>

<details><summary><h4>HyperLink</h4></summary>

- `<a>` (**A**nchor)
  - **기능** : 하이퍼링크를 연결함
  
  - **유형** : inline tag
  
  - **속성 목록**
    - `href` (**H**yper-text **REF**erence) : 하이퍼링크 url 설정
    
    - `target` : 페이지 열람 방식 설정
      - `target = "_self"` : 기존 페이지에서 하이퍼링크 주소로 이동
      - `target = "_blank"` : 새 페이지를 열어서 하이퍼링크 주소로 이동

</details>  
  
---

## ⌨ Input Tag

<details><summary><h4>Logical Division</h4></summary>  
  
- `<form>`
  - **기능** : 입력값을 받는 영역을 구성하는 시멘틱 태그
  
  - **유형** : block tag
  
  - **속성 목록**
    - `id` : 해당 속성의 값을 매개로 `<button>` 과 매핑함
  
  - **하위 태그 목록**
    - `<fieldset>` : 후술
    - `<legend>` : 후술
    - `<label>` : 후술
    - `<input>` : 후술
  
- `<fieldset>`
  - **기능** : `<form>` 의 하위 요소들을 관련에 따라 묶음
  
  - **유형** : block tag
  
  - **하위 태그 목록**
    - `<legend>` : `<fieldset>` 의 제목을 명시함
    - `<label>` : 후술
    - `<input>` : 후술

</details>   

<details><summary><h4>Input</h4></summary>   
  
- `<label>`
  - **기능** : `<input>` 의 제목을 명시함
  
  - **유형** : inline tag
  
  - **속성 목록**
    - `for` : 해당 속성의 값을 매개로 `<input>` 과 매핑함

- `<input>`
  - **기능** : 입력값을 받는 창을 생성함
  
  - **유형** : inline tag
  
  - **속성 목록**
    - `id` : 해당 속성의 값을 매개로 `<label>` 과 매핑함
    - `type` : 입력 양식 설정
    - `name` : 서버에 전송될 입력값의 변수명 설정
    - `value` : 입력값의 초기값 설정
  
  - **`type` 속성값 목록**
    - `type = "text"` : 텍스트 입력창 생성
  
    - `type = "password"` : 비밀번호 입력창 생성
  
    - `type = "radio"` : 라디오 버튼 생성
      - `name` 속성값이 일치된 선택지들을 하나의 묶음으로 취급함
  
    - `type = "checkbox"` : 체크박스 생성
      - `name` 속성값이 일치된 선택지들을 하나의 묶음으로 취급함
  
    - `type = "button"` : 기능이 탑재되지 않은 버튼 생성
      - 임의로 기능을 설정하고자 하는 경우 사용함
      - `onClick` 속성값을 통해 간단한 기능을 설정할 수 있음
      - JS를 활용하여 보다 복잡한 기능을 설정할 수 있음
  
    - `type = "file"` : 파일 선택 버튼 생성
  
    - `type = "submit"` : 서버 전송 버튼 생성
  
    - `type = "image"` : submit 기능하는 이미지 생성
      - `src` 속성값으로 이미지 주소 기입

</details>  

<details><summary><h4>Button</h4></summary>     
  
- `<button>`
  - **기능** : `<form>` 전반에 대하여 기능하는 버튼을 생성함
  
  - **유형** : inline tag
  
  - **속성 목록**
    - `type` : 버튼 기능 설정
    
    - `form` : 해당 버튼이 기능할 태그 `<form>` 설정
      - 해당 속성값은 상위 태그 `<form>`의 속성 `id` 값에 대응함
  
  - **`type` 속성값 목록**
    - `type = "button"` : 상위 태그 `<form>` 에 대하여 기능할 수 있는 버튼 생성
      - 임의로 기능을 설정하고자 하는 경우 사용함
      - `onClick` 속성값을 통해 간단한 기능을 설정할 수 있음
      - JS를 활용하여 보다 복잡한 기능을 설정할 수 있음
    
    - `type = "reset"` : 상위 태그 `<form>` 에서 입력받은 값을 초기화하는 버튼 생성
    
    - `type = "submit"` : 상위 태그 `<form>` 에서 입력받은 값을 서버로 전송하는 버튼 생성    

</details>     
  
---

## ✏ Text Tag

<details><summary><h4>Title</h4></summary>

- 폰트 크기 순으로 `<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>`, `<h6>`이 있음

- 모든 제목 태그의 유형은 block tag 임

</details>

<details><summary><h4>Logical Division</h4></summary>  
  
- `<p>` (**P**aragraph)
  - **기능** : 텍스트 영역을 구성하는 시멘틱 태그
  
  - **유형** : block tag
  
  - **유의점** : 상하여백이 설정되어 있음
  
  - **하위 태그 목록**
    - 일반적인 block tag 와 달리, inline tag 만을 하위 태그로 취할 수 있음

</details>

<details><summary><h4>Form</h4></summary>
  
- `<blockqoute>`
  - **기능** : 인용구를 입력함
  
  - **유형** : block tag
  
  - **속성 목록**
    
    - `cite` : 인용구의 출처를 기입함
  
      - 출처를 검색 엔진에 참조시킬 뿐, 화면에 출력하지 않음
  
  - **하위 태그 목록**
    
    - `<cite>` : 인용구의 출처를 표시함
  
      - 출처를 검색 엔진에 참조시키고 화면에 출력함
  
- `<abbr>` (**ABBR**eviation)
  - **기능** : 축약자와 그 full-name 을 매핑함
  
  - **유형** : inline tag
  
  - **속성 목록**
    - `title` : 축약자의 full-name 입력
  
---

- `<del>` (**DEL**ete)
  - **기능** : 텍스트 취소선을 설정함
  
  - **유형** : inline tag

- `<u>` (**U**nder bar)
  - **기능** : 텍스트 밑줄을 설정함
  
  - **유형** : inline tag  
  
- `<em>` (**EM**phasized text)
  - **기능** : 텍스트 기울임체를 설정함
  
  - **유형** : inline tag

- `<strong>`
  - **기능** : 텍스트 볼드체를 설정함
  
  - **유형** : inline tag
  
---

- `<br/>` (line **BR**eak)
  - **기능** : 줄 바꾸기
  
  - **유형** : inline tag

- `<hr/>` (**H**orizontal **R**ule)
  - **기능** : 수평선 그리기
  
  - **유형** : block tag

</details>
