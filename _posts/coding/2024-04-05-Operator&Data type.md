---
layout: post
title: 프로그래밍 연산자 & 자료형
date: 2024-04-02 17:29 +0900
description: 자바스크립트 연산자와 자료형에 대해서 알아보기
image: ../assets/img/javascript01.jpg
category: 자바스크립트
tags: 객체 생성자 함수 객체생성자함수
published: true
sitemap: true
---

## 자바스크립트 생성자 함수

자바스크립트에서 생성자 함수(Constructor Function)는 객체를 만들기 위한 템플릿과 같은 역할을 합니다.
이를 사용하여 동일한 구조를 갖는 객체들을 여러 개 생성할 수 있습니다. 생성자 함수는 new 키워드를 사용하여 호출되며,
일반 함수와 마찬가지로 함수의 정의 방식을 가지지만, 관례적으로 생성자 함수의 이름은 대문자로 시작합니다.

````javascript
let x = 100, y = 200, z = "javascript";

console.log(x);     // 100
console.log(y);     // 200
console.log(z);     // javascript
````