# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6



# 문장(Paragraph)

동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세
  
  
# 줄바꿈(Line Breaks)

1. 띄어쓰기 두번 이어서 쓰기  
2. br태그 써도 됨  

동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세
  
  
# 강조(Emphasis)

_이탤릭_ : 언더바 사이에 글자 넣기  
**두껍게** : ** 사이에 글자 넣기  
**_이탤릭+두껍게_** **,_ 사이에 글자 넣기  
~~취소선~~ : ~~ 사이에 글자 넣기  
<u>밑줄</u> : u태그 사이에 글자 넣기


# 목록(List)

1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
    1. 순서가 필요한 목록 (들여쓰기 두번)
    1. 순서가 필요한 목록 (들여쓰기 두번)
1. 순서가 필요한 목록 1.만 써도 알아서 순서가 들어감

- 하이픈 띄어쓰기 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록 (들여쓰기 두번)
    - 순서가 필요하지 않은 목록 (들여쓰기 두번)
- 순서가 필요하지 않은 목록


# 링크(Links)

<a href="http://google.com">GOOGLE</a>

```plaintext
[GOOGLE](http://google.com)
```

대괄호 사이에 표시 텍스트  
소괄호 사이에 url 입력  </p>

<a href="http://naver.com"
title="NAVER로 이동!">NAVER</a>  
```plaintext
[NAVER](http://naver.com "네이버로 이동!" ) 
``` 

맨 뒤 띄어쓰기 필수  
큰따옴표 사이 호버되었을 때의 설명추가  


# 이미지(image)
```plaintext
![]()
![text](https://avatars.githubusercontent.com/u/16679082?v=4)
```

![text](https://avatars.githubusercontent.com/u/16679082?v=4)

이미지에 링크넣기  
대괄호로 묶어주고 바로 뒤에 소괄호 추가해서 안에 링크삽입
```html
[![text](https://avatars.githubusercontent.com/u/16679082?v=4)](githubusercontent.com/u/16679082?v=4)
```
[![text](https://avatars.githubusercontent.com/u/16679082?v=4)](githubusercontent.com/u/16679082?v=4)

# 인용문(BlockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
> (네이버 국어 사전)

앞에 꺽쇠모양(>)써주기  
1.처럼 중첩할 수 있음

>인용문
>> 중첩된 인용문1
>>> 중첩된 인용문2

# 인라인(inline) 코드 강조

CSS에서 background 혹은 background-image 속성으로 요소에 배경 이미지를 삽입할 수 있다.  
`백틱기호 사용` 드래그해서 백틱(`)기호 사용해도 적용 됨

# 블록(block) 코드 강조

```html
<a href="http://google.com">GOOGLE</a>
```

```html
```html ~ ``` 사이에 넣어주기
```

```plaintext
그냥 글자
```

```plaintext
```plaintext ~ ``` 사이에 넣어주기
```


# 표(table)

position 속성

값 | 의미 | 기본값
--|:--:|--:
static | 기준 없음 | O
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X

```plaintext
값 | 의미 | 기본값
--|:--:|--
static | 기준 없음 | O
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X

기본: 왼쪽 정렬
가운데정렬: -- 양쪽에 : 추가
오른쪽정렬: -- 뒤에 : 한개 추가

단순한 형태의 표만 제작 가능
```

# 원시 HTML(Raw HTML)

Markdown 문법 안에서 실제 HTML 문법을 사용하는 것<br>
이미지 넣기, 링크 넣기 등<br>

동해물과 <u>백두산</u>이 마르고 닳도록 <br/>
하느님이 보우하사 우리나라 만세

```plaintext
동해물과 <u>백두산</u>이 마르고 닳도록 <br/>
하느님이 보우하사 우리나라 만세
```

# 수평선(Horizontal Rule)

하이픈 세번 넣기
---

별표시 세번 넣기
***

언더바 세번 넣기
___