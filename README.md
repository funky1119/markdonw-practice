# 제목(Header) - # 의 갯수가 적을수록 중요 내용

# 제목 1

## 제목 2

### 제목 3

#### 제목 4

##### 제목 5

###### 제목 6

# 문장 (Paragraph)

동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세

# 줄바꿈 (Line Breaks) - 띄어쓰기를 넣거나 br 태그를 사용

동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세  
무궁화 삼천리 화려강산<br />
대한 사람 대한으로 길이 보전하세

# 강조 (Emphasis)

_이탤릭_  
**두껍게**  
**_이탤릭 + 두껍게_ **  
~~취소선~~  
<u>밑줄</u>

# 목록 (List)

1. 순서가 있는 목록
   1. 순서가 있는 목록
   1. 순서가 있는 목록
2. 순서가 있는 목록
3. 순서가 있는 목록

- 순서가 없는 목록
- 순서가 없는 목록
  - 순서가 없는 목록
  - 순서가 없는 목록
- 순서가 없는 목록

# 링크 (Links)

<a href="https://google.com">GOOGLE</a>

[GOOGLE](https://google.com)

<a href="https://naver.com" title="네이버로 이동">NAVER</a>

[NAVER](https://naver.com "NAVER로 이동!")

<a href="https://naver.com" title="네이버로 이동" target="_blank">NAVER</a>

# 이미지 (Images)

![HEROPY](https://heropy.blog/css/images/logo.png)

[![HEROPY](https://heropy.blog/css/images/logo.png)](https://heropy.blog/)

# 인용문 (BlockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장  
> (네이버 국어 사전)
>
> 인용문을 작성하세요!
>
> > 중첩된 인용문
> >
> > > 중첩된 인용문
> > >
> > > > 중첩된 인용문

# 인라인 (Inline) 코드 강조

CSS에서 `background` 혹은 `background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.

# 블록 (Block) 코드 강조

```html
<a href="https://naver.com" title="네이버로 이동">NAVER</a>
```

```css
div {
  width: 100px;
  height: 100px;
  background-color: red;
}
```

```javascript
function hello() {
  alert("안녕하세요!");
}
```

```bash
$ git commit -m "Study Markdown"
```

```plaintext
동해물과 백두산이 마르고 닿도록
하나님이 보우하사 우리나라 만세
```

```python
def hello():
  print("안녕하세요!")
```

# 표 (Table)

position 속성

- Head 부분과 Body 부분 사이에 | --- | 을 넣어 구분
- 사이에 --- 을 왼쪽에 : 을 넣으면 왼쪽 정렬 오른쪽은 오른쪽 정렬 가운데는 가운데 정렬

| 값       |              의미 |                               설명                                | 기본값 |
| -------- | ----------------: | :---------------------------------------------------------------: | ------ |
| static   |         기준 없음 |                  요소를 문서의 흐름에 따라 배치                   | O      |
| relative |         요소 자신 | 요소를 문서의 흐름에 따라 배치하고 자기 자신을 기준으로 위치 설정 | X      |
| absolute | 위치 상 부모 요소 | 요소를 문서의 흐름에서 제거하고 브라우저 창을 기준으로 위치 설정  | X      |
| fixed    |           뷰 포트 | 요소를 문서의 흐름에서 제거하고 브라우저 창을 기준으로 위치 설정  | X      |

# 원시 HTML (Raw HTML)

동해물과 <span style="text-decoration: underline;">백두산이</span> 마르고 닳도록<br />
하느님이 보우하사 <span style="color: red">우리나라</span> <span style="color: blue">만세</span>

<a href="https://naver.com" title="네이버로 이동" target="_blank">NAVER</a>

<img width="70" src="https://heropy.blog/css/images/logo.png" alt="HEROPY" width="300" />

# 수평선 (Horizontal Rule)

`---`

`***`

`___`

---
