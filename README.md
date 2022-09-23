# 마크다운 사용법
## 목차
[1. 제목](#제목-1)  
[2. 문장(Paragraph)](#문장(Paragraph))  
[3. 줄바꿈(Line Breaks)](#줄바꿈(Line-Breaks))  
[4. 강조(Emphasis)](#강조(Emphasis))  
[5. 목록(List)](#목록(List))  
[6. 링크(Links)](#링크(Links))  
[7. 이미지(Images)](#이미지(Images))  
[8. 인용문(BlockQuote)](#인용문(BlockQuote))  
[9. 인라인(inline)&블록(block)](#인라인(inline)-코드-강조)  
[10. 표(Table)](#표(Table))  
[11. 원시 HTML(Raw HTML)](#원시-HTML(Raw-HTML))  
[12. 수평선](#수평선)  
[13. 이모지](#이모지-사용법)  

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
<!-- 띄어쓰기 두 번  -->
동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세  
무궁화 삼천리 화려 강산 <br/>
대한 사람 대한으로 길이 보전하세

# 강조(Emphasis)

_이텔릭_  
**두껍게**  
**_이텔릭 + 두껍게_**  
~~취소선~~  
<u>밑줄</u>

# 목록(List)

1. 순서가 필요한 목록
1. 순서가 필요한 목록
    1. 순서가 필요한 목록 <!--들여쓰기 두 번-->
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

# 링크(Links)

<a href="https://google.com">GOOGLE</a>

[GOOGLE](https://google.com)

<a href="https://naver.com" title="NAVER로 이동!">NAVER</a>

[NAVER](https://naver.com "NAVER로 이동!")

<a href="https://naver.com" title="NAVER로 이동!"
   target="_blank">NAVER</a>  <!--새 탭으로 열기 기능, 마크다운에는 없음-->

# 이미지(Images)
`![]()<!--구조-->`
  
![HEROPY](https://cdn.pixabay.com/photo/2016/11/23/13/48/beach-1852945_960_720.jpg) <!--이미지는 맨 앞에 느낌표!!-->

- 이미지에 링크 삽입하는 
[![HEROPY](https://heropy.blog/css/images/logo.png)](https://heropy.blog/) <!--이미지에 링크 삽입-->

# 인용문(BlockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
> (네이버 국어 사전)

> 인용문을 작성하세요!
>> 중첩된 인용문
>>> 중중첩된 인용문 1
>>> 중중첩된 인용문 2
>>> 중중첩된 인용문 3

# 인라인(inline) 코드 강조
<!--백틱 사용-->
CSS에서 `background` 혹은 `background-image` 속성으로 요소에 배경이미지를 삽입할 수 있습니다.

# 블록(block) 코드 강조
<!--백틱 3번 + 문법 이름-->
```html
<a href="https://naver.com" title="NAVER로 이동!">NAVER</a>
```

```css
.list > li {
  position: absolute;
  top: 40px;
}
```
```javascript
function func() {
  var a = 'AAA';
  return a;
}
```

```bash
$ git commit -m 'Study Markdown'
```

```plaintext
동해물과 백두산이 마르고 닳도록 하느님이 보우하사 우리나라 만세
```

# 표(Table)

position 속성
<!-- '--|--|--' 표의 머리와 몸통 분리, 왼쪽, 가운데, 오른쪽 정렬 조정 -->

값 | 의미 | 기본값 
--|:--:|--:              
static | 기준 없음 | O
relative | 요소 자신 | X 
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X

# 원시 HTML(Raw HTML) 
`주석 표시 방법:  <!--마크다운 문법안에서 HTML 사용하는 것-->`

동해물과 <u>백두산</u>이 마르고 닳도록<br/>
하느님이 보우하사 <span style="text-decoration: underline;">우리나라</span> 만세 

<!--마크다운에 지원되지 않는 기능이라서 HTML 사용-->
---

<a href="https://naver.com" title="NAVER로 이동!">NAVER</a>

<img width="70" src="https://heropy.blog/css/images/logo.png" alt="HEROPY">

# 수평선

---

***

# 이모지 사용법
- `:smile:` -> :smile:
  
![image](https://user-images.githubusercontent.com/78733700/191871039-5c8397dd-10ca-41c5-b3ef-4f383743d66e.png)
- [참고 사이트](https://www.webfx.com/tools/emoji-cheat-sheet/)
