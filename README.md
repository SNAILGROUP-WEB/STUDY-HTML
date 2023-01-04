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
    - 유형
      - block tag :
      - inline tag : 
  
  - 속성 (Attribute)

---

## Semantic Tag

<details><summary><h4>머릿말 태그</h4></summary>

- `<header>`

</details>

<details><summary><h4>메인 페이지 태그</h4></summary>

- `<main>`

- `<section>`

- `<article>`

</details>

<details><summary><h4>사이드바 태그</h4></summary>

- `<nav>` (**NAV**igation links)

- `<aside>`

</details>

<details><summary><h4>꼬릿말 태그</h4></summary>

- `<footer>`

</details>

<details><summary><h4>논리적 구분 태그</h4></summary>

- `<p>` (**P**aragraph)
  - 기능 : 단락 구분하기
    - 주로 텍스트 문단 구분 시 사용됨
  - block tag
  - 상하여백이 자동으로 설정되어 있음

- `<div>` (**DIV**ition)
  - 기능 : 단락 구분하기
  - block tag
  - 상하여백이 설정되어 있지 않음

- `<span>`
  - 기능 : 단락 구분하기
  - inline tag
  - 상하여백이 설정되어 있지 않음

</details>

---

## Contents Tag

<details><summary><h4>목록 태그</h4></summary>

- `<ul>` (Unorderd List)
  - 기능
  - 유형 : block tag
  - 하위 태그 목록
    - <li> (**L**ist **I**tem)

- `<ol>` (**O**rdered **L**ist)
  - 기능
  - 유형 : block tag
  - 하위 태그 목록
    - <li> (**L**ist **I**tem)

- `<dl>` (**D**efinition **L**ist)
  - 기능 : 내용과 설명이 쌍을 이루는 목록을 하위 태그로 가지는 상위 태그
  - 유형 : block tag
  - 하위 태그 목록
    - `<dt>` (**D**efinition **T**ext) : 내용 기입
    - `<dd>` (**D**efinition **D**escription) : 설명 기입

</details>

<details><summary><h4>표 태그</h4></summary>

- `<table>`
  - 기능 :
  - 유형 :
  - 하위 태그 목록
    - `<th>`
    - `<td>`
    - `<tr>`

<details><summary><h4>이미지 태그</h4></summary>

- `<figure>`
  - 기능 :
  - 유형 :
  - 하위 태그 목록
    - `<img>`
    - `<figcaption>`

- `<img>`
  - 기능 :
  - 유형 : 
  - 속성 목록
    - `src`
    - `alt`

</details>

---

## ETC

<details><summary><h4>제목 태그</h4></summary>

- 폰트 크기 순으로 `<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>`, `<h6>`이 있음

- block tag

</details>

<details><summary><h4>서식 태그</h4></summary>

- `<abbr>` (**ABBR**eviation)
  - 기능 : 축약자 입력하기  
  - 유형 : inline tag
  - 속성 목록
    - `title` : 축약자의 full name 입력

---
  
- `<blockqoute>`
  - 기능 : 인용구 설정하기
  - 유형 : block tag
  
---

- `<adress>`
  - 기능 : 오프라인 주소 입력하기
  - 유형 : block tag
  
---

- `<em>` (**EM**phasized text)
  - 기능 : 텍스트 강조하기
    - 텍스트를 기울임체로 강조함
    - `<strong>` 태그에 비해 주관적인 내용을 강조할 때 사용됨
  - 유형 : inline tag
  
---

- `<strong>`
  - 기능 : 텍스트 강조하기
    - 텍스트를 볼드체로 강조함
    - `<em>` 태그에 비해 객관적인 내용을 강조할 때 사용됨
  - 유형 : inline tag

---

- `<u>` (**U**nder bar)
  - 기능 : 텍스트 밑줄 치기
  - 유형 : inline tag
  
---

- `<br/>`
  - 기능 : 줄 바꾸기
  - 유형 : inline tag
  
---

- `<hr/>` (**H**orizontal **R**ule)
  - 기능 : 수평선 그리기
  - 유형 : block tag

</details>

<details><summary><h4>하이퍼링크 태그</h4></summary>

- `<a>` (**A**nchor)
  - 기능 : 하이퍼링크 연결하기
  - 유형 : inline tag
  - 속성 목록
    - `href` (**H**yper-text **REF**erence) : 하이퍼링크 url 설정
    - `target` : 페이지 열람 방식 설정
      - `target = "_self"` : 기존 페이지에서 하이퍼링크 주소로 이동
      - `target = "_blank"` : 새 페이지를 열어서 하이퍼링크 주소로 이동

</details>
