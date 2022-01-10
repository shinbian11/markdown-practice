# 제목 (Header)

# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6

<br>

# 문장

이것은 문장입니다. <br> br 태그나 스페이스키 2번을 사용하면 개행(줄 바꿈 - Line Breaks)이 가능합니다.

<br>

# 강조 

_이텔릭_  
**두껍게**  
**_이텔릭 + 두껍게_**  
~~취소선~~  
<u>밑줄</u>

<br>

# 목록 (List)

1. 순서가 필요한 목록
1. 순서가 필요한 목록
    1. 순서가 필요한 목록
    1. 순서가 필요한 목록
1. 순서가 필요한 목록

- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
        - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록

<br>

# 링크 (Links)

[GOOGLE](https://google.com)

[NAVER](https://naver.com "NAVER로 이동! - hover시 이 text가 보임!")

<br>

# 이미지 (Images)

<!-- 링크와 이미지는 맨 앞의 ! 의 차이이다 -->
![HEROPY](https://heropy.blog/css/images/logo.png)

[![HEROPY](https://heropy.blog/css/images/logo.png)](https://heropy.blog/)

<br>

# 인용문 (BlockQuote)

> 인용문 인용문 인용문 인용문 인용문 인용문 인용문  
>> 중첩된 인용문  
>>> 중첩된 인용문  

> (네이버 국어 사전)


# 인라인 (inline) 코드 강조

CSS에서 `background` 혹은  
`background-image` 속성으로 요소에  
배경 이미지를 삽입할 수 있습니다.

<br>

# 블럭(block) 코드 강조

```html
<div> 이것은 블럭 코드 강조! </div>
```

```css
div {
    color : #fff;
}
```

```javascript
function func() {
    let a = 'AAA'
    return a;
}
```

```bash
$ git commit -m 'Study Markdown'
```

```plaintext
이것은 plaintext 입니다.
```

<br>

# 표 (Table)

position 속성

값 | 의미 | 기본값
-- | :--: | --:
static | 기준 없음 | O
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X

<br>

# 원시 HTML (Raw HTML)

- Markdown 문법에서 실제 HTML 문법을 사용하는 것<br><br>
<u>언더라인</u><br>
<span style = "text-decoration : underline;">언더라인</span>

<br>

# 수평선 (Horizontal Rule)

---
수평선
***
수평선
___