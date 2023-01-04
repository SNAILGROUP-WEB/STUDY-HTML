# HTML Basic Syntax
html 학습 내용 정리

---

## HTM

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

## Semantic Tag

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
  - **기능** :
  
  - **유형** : block tag
  
  - **`<article>` 태그와 차이점**

- `<article>`
  - **기능** :
  
  - **유형** : block tag
  
  - **`<section>` 태그와 차이점**

</details>

<details><summary><h4>사이드바 태그</h4></summary>

- `<nav>` (**NAV**igation links)
  - **기능** : 사이드바 구성하기
  
  - **유형** : block tag
  
  - **`<aside>` 태그와 차이점**

- `<aside>`
  - **기능** : 사이드바 구성하기
  
  - **유형** : block tag
  
  - **`<nav>` 태그와 차이점**

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

## Contents Tag

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
  - **기능** :
  
  - **유형** :
  
  - **하위 태그 목록**
    - `<th>`
    - `<td>`
    - `<tr>`

</details>

<details><summary><h4>이미지 태그</h4></summary>

- `<figure>`
  - **기능** :
  
  - **유형** :
  
  - **하위 태그 목록**
    - `<img>` : 후술
    - `<figcaption>`

- `<img>`
  - **기능** :
  
  - **유형** : 
  
  - **속성 목록**
    - `src`
    - `alt`

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

## TEXT Tag

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
