---
title:  "Blog 작성을 위한 Markdown 공부"
excerpt: "GitHub Blog 작성을 위해 Markdown을 알아보자."

categories:
  - Blog
tags:
  - Blog
last_modified_at: 2022-04-14
---

github 블로그 작성을 하게 되면 Markdown을 알아야 한다.
기본적인 Markdown은 알고 있지만, 더 다양하게 활용하고 싶어 'https://devinlife.com/howto%20github%20pages/markdown-syntax/'를 참고하여 글을 작성한다.

# 1. Markdown이란?

# 2. Markdown 문법
## 2.1. 텍스트 줄바꿈
기본적인 텍스트 표기 방식이다.
마크다운은 줄바꿈을 인식하지 않는다.

줄바꿈을 하기 위해서는 라인 끝에 스페이스를 2번  
표기해야 한다.

여러가지 강조 표시가 존재한다. 첫번째로 *single asterisks*,
enqjsWofh _single underscores_, 세 번째로 **double asterisks**,  
네 번째로 __double underscores__,  다섯 번째로 ~~cancle line~~이 있다.

## 2.2. 글머리 달기
# H1
## H2
### H3
#### H4
##### H5
###### H6까지 있다.

## 2.3. 인용문
인용을 할 때는, '>'를 사용한다.

> 준비가 돼서 지원하는 것이 아니라, 지원을 하고 준비를 하는 것이다!  

아래는 단계별 인용이다.  
  
> 첫 번째 인용  
>> 두 번째 인용  
>>> 세 번째 인용  

## 2.4. 정렬 목록

1. 봄  
2. 여름  
3. 가을  
4. 겨울  

## 2.5. 비정렬 목록  
- 과자
  - 라면
    - 사탕


## 2.6. 코드 인용
```
import pandas as pd
import numpy as np
```

## 2.7. 코드 인용 (언어 별 문법 하이라이트)

- 루비
``` ruby
gem install bundle
markdown = Redcarpet.new("Hello World!")
```

- C
```c
int main() {
  int y = SOME_MACRO_REFERENCE;
  int x = 5+6;
  cout << "Hello World!" << x << std::end();
}
```

- C++
```cpp
int main() {
  int y = SOME_MACRO_REFERENCE;
  int x = 5+6;
  cout << "Hello World!" << x << std::end();
}
```

- Python
```python
s = 'Python syntax highlighting'
print s
```

## 2.8. 수평선

* * *  
***  
*****  
- - -  
-----------------------  

## 2.9. 링크

1) 링크 이름 설정하여 표시
  - [구글](https://www.google.com/)

2) 주소 직접 표시
  - <https://www.google.com/>  

## 2.10. 이미지 삽입
1. ![](https://unsplash.com/photos/LB3wSllhBq0?utm_source=unsplash&utm_medium=referral&utm_content=creditShareLink)

2. ![](https://unsplash.com/photos/LB3wSllhBq0?utm_source=unsplash&utm_medium=referral&utm_content=creditShareLink){: .align-center}

3. ![데이지사진](https://images.unsplash.com/photo-1600264195762-c10ff160b264?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=424&q=80"데이지사진"){: .align-center}


## 2.11. 표 만들기

- 표 내용 중앙정렬  

|메뉴|가격|개수|
|:---:|:---:|:---:|
|쿠키|1,000원|3개|
|딸기케이크|9,300원|1개|
|오레오프라푸치노|5,600원|1개|

- 표 내용 좌측 정렬 - 중앙 정렬 - 우측 정렬

|메뉴|가격|개수|
|:----|:----:|----:|
|쿠키|1,000원|3개|
|딸기케이크|9,300원|1개|
|오레오프라푸치노|5,600원|1개|



끝!

