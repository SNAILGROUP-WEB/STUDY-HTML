<h1 align='center'>📚 HTML BASIC SYNTAX 📚</h1>
html 학습 내용 정리

---

## 📖 HTML

- **구조**
  - `<html>` : 하나의 html 페이지를 묶는 태그임
  
  - `<head>` : 페이지의 메타 정보를 하위 태그로 가지는 태그임
  
  - `<body>` : 페이지에 출력되는 내용에 관한 정보를 하위 태그로 가지는 태그임

- **구성요소**
  - 태그 (Tag)
    - 정의 :
    - 유형 :
      - block tag :
      - inline tag : 
  
  - 속성 (Attribute)

---

## 🏛 Semantic Tag

<details><summary><h4>머릿말 태그</h4></summary>

- `<header>`
  - **기능** : 머릿말 영역을 설정하는 최상위 태그
  
  - **유형** : block tag

</details>

<details><summary><h4>메인 페이지 태그</h4></summary>

- `<main>`
  - **기능** : 메인 페이지 영역을 설정하는 최상위 태그
  
  - **유형** : block tag
  
  - **하위 태그 목록**
    - `<section>` : 후술
    - `<article>` : 후술

- `<section>`
  - **기능** : 단일 주제 영역을 설정하는 상위 태그
  
  - **유형** : block tag
  
  - **`<article>` 태그와 차이점**
    - 통상적으로 하나의 대주제를 설정하는 태그로서 사용됨
    - 반드시 `<article>` 의 상위에 자리해야 하는 것은 아님

- `<article>`
  - **기능** : 단일 주제 영역을 설정하는 상위 태그
  
  - **유형** : block tag
  
  - **`<section>` 태그와 차이점**
    - 통상적으로 대주제의 하위 주제들을 구분하는 태그로서 사용됨
    - 반드시 `<section>` 의 하위에 자리해야 하는 것은 아님

</details>

<details><summary><h4>사이드바 태그</h4></summary>

- `<nav>` (**NAV**igation links)
  - **기능** : 사이드바 구성하기
  
  - **유형** : block tag
  
  - **`<aside>` 태그와 차이점**
    - 통상적으로는 목차를 구성하는 태그로서 사용됨
    - 반드시 메인 페이지의 좌우에 자리해야 하는 것은 아님
    - 간혹 `<header>` 태그의 하위 태그에 자리하기도 함

- `<aside>`
  - **기능** : 사이드바 구성하기
  
  - **유형** : block tag
  
  - **`<nav>` 태그와 차이점**
    - 통상적으로는 광고 등을 구성하는 태그로서 사용됨
    - 대개 메인 페이지의 좌우에 자리함
    - 간혹 `<main>` 태그의 하위 태그에 자리

</details>

<details><summary><h4>꼬릿말 태그</h4></summary>

- `<footer>`
  - **기능** : 꼬릿말 영역을 설정하는 최상위 태그
  
  - **유형** : block tag

</details>

<details><summary><h4>논리적 구분 태그</h4></summary>

- `<p>` (**P**aragraph)
  - **기능** : 단락 구분하기
  
  - **유형** : block tag
  
  - **여타 태그와의 차이점**
    - 통상적으로는 텍스트 문단 구분 시 사용됨
    - `<div>` 태그와 차이점 : 상하여백이 설정되어 있음
    - `<span>` 태그와 차이점 : block tag 임
  
  - **하위 태그 목록**
    - 일반적인 block tag와 달리 inline tag 만을 하위 태그로 취할 수 있음

- `<div>` (**DIV**ition)
  - **기능** : 단락 구분하기
  
  - **유형** : block tag
  
  - **여타 태그와의 차이점**
    - `<p>` 태그와 차이점 : 상하여백이 설정되어 있지 않음
    - `<span>` 태그와 차이점 : inline tag 임

- `<span>`
  - **기능** : 단락 구분하기
  
  - **유형** : inline tag
  
  - **여타 태그와의 차이점**
    - `<p>` 태그와 차이점 : 상하여백이 설정되어 있지 않음
    - `<div>` 태그와 차이점 : inline tag 임

</details>

---

## ✂ Contents Tag

<details><summary><h4>목록 태그</h4></summary>

- `<ul>` (Unorderd List)
  - **기능** : 순서가 없는 목록을 하위 태그 가지는 상위 태그
  
  - **유형** : block tag
  
  - **하위 태그 목록**
    - `<li>` (**L**ist **I**tem) : 목록 기입

- `<ol>` (**O**rdered **L**ist)
  - **기능** : 순서가 있는 목록을 하위 태그로 가지는 상위 태그
  
  - **유형** : block tag
  
  - **하위 태그 목록**
    - `<li>` (**L**ist **I**tem) : 목록 기입

- `<dl>` (**D**efinition **L**ist)
  - **기능** : 내용과 설명이 쌍을 이루는 목록을 하위 태그로 가지는 상위 태그
  
  - **유형** : block tag
  
  - **하위 태그 목록**
    - `<dt>` (**D**efinition **T**ext) : 목록의 내용 기입
    - `<dd>` (**D**efinition **D**escription) : 목록의 설명 기입

</details>

<details><summary><h4>표 태그</h4></summary>

- `<table>`
  - **기능** : 표를 구성하는 최상위 태그
  
  - **유형** : block tag
  
  - **하위 태그 목록**
    - `<th>` (**T**able **H**eader) : 칼럼명 기입
    - `<td>` (**T**able **D**escription) : 내용 기입
    - `<tr>` (**T**able **R**ow) : 행 바꾸기

</details>

<details><summary><h4>이미지 태그</h4></summary>

- `<figure>`
  - **기능** : 이미지를 구성하는 최상위 태그
  
  - **유형** : block tag
  
  - **하위 태그 목록**
    - `<img>` : 후술
    - `<figcaption>` : 이미지의 주석을 기입하는 태그

- `<img/>`
  - **기능** : 이미지 주소를 기입하는 태그
  
  - **유형** : inline tag
  
  - **속성 목록**
    - `src` : 이미지 주소 입력
    - `alt` : 이미지 대체 텍스트 입력

</details>

<details><summary><h4>하이퍼링크 태그</h4></summary>

- `<a>` (**A**nchor)
  - **기능** : 하이퍼링크 연결하기
  
  - **유형** : inline tag
  
  - **속성 목록**
    - `href` (**H**yper-text **REF**erence) : 하이퍼링크 url 설정
    
    - `target` : 페이지 열람 방식 설정
      - `target = "_self"` : 기존 페이지에서 하이퍼링크 주소로 이동
      - `target = "_blank"` : 새 페이지를 열어서 하이퍼링크 주소로 이동

</details>  
  
---

## Input Tag

<details><summary><h4>FORM & BUTTON</h4></summary>  
  
- `<form>`
  - **기능** :
  
  - **유형** :
  
  - **속성 목록**
    - `id` : 해당 속성의 값을 매개로 `<button>` 과 매핑함
  
  - **하위 태그 목록**
    - `<fieldset>` : 후술
    - `<legend>` : 후술
    - `<label>` : 후술
    - `<input>` : 후술

- `<button>`
  - **기능** :
  
  - **유형** :
  
  - **속성 목록**
    - `type`
    
    - `form` : 해당 버튼이 기능할 상위 태그 `<form>` 설정
      - 해당 속성값은 상위 태그 `<form>`의 속성 `id` 값에 대응함
  
  - **`type` 속성값 목록**
    - `type = "button"` : 상위 태그 `<form>` 에 대하여 기능할 수 있는 버튼 생성
      - JS를 활용하여 임의로 기능을 설정하고자 하는 경우 사용함
    
    - `type = "reset"` : 상위 태그 `<form>` 에서 입력받은 값을 초기화하는 버튼 생성
    
    - `type = "submit"` : 상위 태그 `<form>` 에서 입력받은 값을 서버로 전송하는 버튼 생성  

</details> 

<details><summary><h4>FIELDSET & LEGEND</h4></summary>    
  
- `<fieldset>`
  - **기능** :
  
  - **유형** :
  
  - **하위 태그 목록**
    - `<legend>` : `<fieldset>` 의 제목을 명시함
    - `<label>` : 후술
    - `<input>` : 후술

</details>   

<details><summary><h4>LABEL & INPUT</h4></summary>   
  
- `<label>`
  - **기능** : 
  
  - **유형** :
  
  - **속성 목록**
    - `for` : 해당 속성의 값을 매개로 `<input>` 과 매핑함

- `<input>`
  - **기능** :
  
  - **유형** :
  
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
      - JS를 활용하여 임의로 기능을 설정하고자 하는 경우 사용함
  
    - `type = "file"` : 파일 선택 버튼 생성
  
    - `type = "submit"` : 서버 전송 버튼 생성
  
    - `type = "image"` : submit 기능하는 이미지 생성
      - `src` 속성값으로 이미지 주소 기입

</details>  
  
---

## ✏ TEXT Tag

<details><summary><h4>제목 태그</h4></summary>

- 폰트 크기 순으로 `<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>`, `<h6>`이 있음

- 모든 제목 태그의 유형은 block tag 임

</details>

<details><summary><h4>서식 태그</h4></summary>
  
- `<blockqoute>`
  - **기능** : 인용구 입력하기
  
  - **유형** : block tag
  
- `<abbr>` (**ABBR**eviation)
  - **기능** : 축약자 입력하기  
  
  - **유형** : inline tag
  
  - **속성 목록**
    - `title` : 축약자의 full name 입력

- `<adress>`
  - **기능** : 오프라인 주소 입력하기
  
  - **유형** : block tag
  
---

- `<em>` (**EM**phasized text)
  - **기능** : 텍스트 강조하기
  
  - **유형** : inline tag
  
  - **`<strong>` 태그와 차이점**
    - 텍스트를 기울임체로 강조함
    - 주관적인 내용을 강조할 때 사용됨

- `<strong>`
  - **기능** : 텍스트 강조하기
  
  - **유형** : inline tag
  
  - **`<em>` 태그와 차이점**
    - 텍스트를 볼드체로 강조함
    - 객관적인 내용을 강조할 때 사용됨
  
---

- `<br/>`
  - **기능** : 줄 바꾸기
  
  - **유형** : inline tag

- `<hr/>` (**H**orizontal **R**ule)
  - **기능** : 수평선 그리기
  
  - **유형** : block tag

</details>
