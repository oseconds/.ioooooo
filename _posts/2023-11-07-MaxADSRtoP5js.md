---
title: "Max-ADSR-Envelope-to-P5JS"
date: 2023-11-07 HH:MM:SS +/-09:00
categories: [P5JS-IN-MAX], UTILLITY]
tags: [p5jsinmax, p5.sound, adsr, envenlope, function]     # TAG names should always be lowercase
---

## P5JS에서 쉽게 ADSR을 컨트롤 하기  
p5.sound 라이브러리에서는 기본적으로 [p5.Envelope](https://p5js.org/reference/#/p5.Envelope){: target="_blank"} 를 사용할때     
```javascript
p5.Envelope(t1, l1, t2, l2);
```    
이러한 형태로 어택타임, 어택 레벨, 디케이 타임, 디케이레벨 을 각각 숫자로 입력해야한다.    

Max의 function 을 연결해서 마우스로 손쉽게 adsr을 조절하는 방법을 알아보자.
