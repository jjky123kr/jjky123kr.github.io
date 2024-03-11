---
layout: post
title:  "Proxy error Could not proxy request /test/hello from localhost:3000 to http://localhost:8080/ (ECONNREFUSED). 에러발생"
categories: error
description: >
     '에러 '
---
# Proxy error Could not proxy request /test/hello from localhost:3000 to http://localhost:8080/ (ECONNREFUSED). 에러발생


## 에러 

![스크린샷 2024-03-11 150815](https://github.com/jjky123kr/jjky123kr.github.io/assets/107549149/0eec9403-2e8c-43ac-8b09-b83388ab5a72)

## 원인 

1. react 와 연동 할때, port 번호 

2. react 연동 시 Spring boot 어플리케이션 실행 과 react 실행 해준다. 

3. 이때 벡엔드 Spring boot 어플리케이션 실행이 제대로 되지 않아서 오류 발생 

