---
title: "히든클래스"
date: 2023-08-01 00:00:00 -0400
categories: [Tech, javascript]
tags: [javascript, hidden-class, v8, engine, array]
excerpt: "V8 엔진에서의 히든클래스에 대해 알아보자."
---

### 자바스크립트가 배열의 크기를 지정하지 않고도 사용할 수 있는 이유

자바스크립트는 배열의 크기를 지정하지 않고도 사용할 수 있다.

```javascript
const arr = [];
arr[0] = 1;
arr[1] = 2;
arr[2] = 3;
arr[3] = 4;
arr[4] = 5;

console.log(arr); // [1, 2, 3, 4, 5]
```

위와 같이 배열의 크기를 지정하지 않고도 사용할 수 있는 이유는 자바스크립트의 히든클래스 때문이다.

### 히든클래스
