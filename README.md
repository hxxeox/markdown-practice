# 제목(Header)

# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6

# 문장 (Paragraph)
동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세

# 줄바꿈 (Line Breaks)
동해물과  백두산이 마르고 닳도록 하느님이 보우하사 우리나라 만세 <br>무궁화 삼천리 화려 강산 대한 사람<br> 대한으로 길이 보전하세

# 강조 (Emphasis)
_이텔릭_  
**두껍게**  
**_이텔릭 + 두껍게_**  
~~취소선~~  
<u>밑줄</u>

# 목록(List)
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

# 링크(Links)
<a href="http://google.com">Google</a>  
[Google](http://google.com)

<!-- hover시 툴팁보임 -->
<a href="http://google.com" title="구글">Google</a>    
[Google](http://google.com "구글로 이동!")

<a href="http://google.com" title="구글" target="_blank">Google</a>    
[Google](http://google.com "구글로 이동!")

# 이미지(Images)
<!-- 대체 텍스트 HEROPY -->
![HEROPY](https://i.ytimg.com/vi/FL3WMfS1rJY/hqdefault.jpg?sqp=-oaymwEcCOADEI4CSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLBgcKuJLSm5DnzXZX8sz8jmw8s8SQ)

<!-- 이미지 클릭시 링크로 이동 -->
[![HEROPY](https://i.ytimg.com/vi/FL3WMfS1rJY/hqdefault.jpg?sqp=-oaymwEcCOADEI4CSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLBgcKuJLSm5DnzXZX8sz8jmw8s8SQ)
](http://hxxeox.com/STARTER/index.html)

# 인용문(BlockQuote)
> 남의 말이나 글에서 직접 또는  간접으로 따온 문장.  
> (네이버 국어 사전)

> 인용문을 작성하세요!
>> 중첩된 인용문
>>> 중중첩된 인용문 1
>>>> 중중첩된 인용문 2
>>>> 중중첩된 인용문 3

# 인라인(inline) 코드 강조
<!-- 상단 숫자1번 왼쪽 기호 / 글자 드래그 후 ` 누르면 한번에 묶임-->
CSS에서 `Background` 혹은 `background-image` 속성으로 요소에 배경 `이미지를 삽입할 수 있습니다.`

# 블록(block) 코드 강조
```html
<a href="http://google.com" title="구글" target="_blank">Google</a>  
```

```css
li {
    list-style:none
}
```

```bash
$ git commit -m 'Study Markdown'
```

```plaintext
동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세
```

# 표 (Table)

position 속성  
<!-- 좌우로 : 기호를 넣으면 가운데 정렬 -->
<!-- 오른쪽에만 : 기호 넣을시 오른쪽 정렬 -->
값  |  의미  |  기본값  
--|:--:|--:
static | 기준-없음 | O
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X

# 원시 HTML (Raw HTML)
<!-- u태그 보다 span에 style을 입력하는것을 더 권장한다 -->
동해물과 <span style="text-decoration:underline">백두산이</span> 마르고 닳도록<br>
하느님이 보우하사 우리나라 만세

<!-- target이 필요할 시 html문법으로 작성 가능-->
<a href="http://google.com" title="구글" target="_blank">Google</a> 

<!-- width로 지정가능 -->
<img width="800" src="https://i.ytimg.com/vi/FL3WMfS1rJY/hqdefault.jpg?sqp=-oaymwEcCOADEI4CSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLBgcKuJLSm5DnzXZX8sz8jmw8s8SQ">

# 수평선 (Horizontal Rule)

---
---
---
