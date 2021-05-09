# 제목(Header)
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6
#의 갯수에 따라 h1 ~ h6까지

## 문장(Paragraph)
동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세

## 줄바꿈(Line breaks)
띄어쓰기 2번 + enter시 줄바꿈  
혹은 &lt;br/&gt;로 줄바꿈

## 강조()
[& 특수문자리스트](http://kor.pe.kr/util/4/charmap2.htm)

&#95;강조할 문자&#95; : _강조할 문자_
<br/>
&#42;&#42;두껍게&#42;&#42; : **두껍게**
<br/>
&#95;&#42;&#42;이텔릭 + 두껍게&#42;&#42;&#95; : _**이텔릭 + 두껍게**_
<br/>
&#126;&#126;취소선&#126;&#126; : ~~취소선~~
<br/>
&lt;u&gt;밑줄&lt;/u&gt; : <u>밑줄</u>
<br/>

## 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
    1. 얍얍
    1. 얍얍
1. 순서가 필요한 목록
<br/>

숫자 + . 입력 시 입력한 숫자와 관계없이 ol이 만들어짐.  

- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
- + 내용

## 링크
&lt;a href='주소'&lt;구글&lt;/a&gt;
<br/>

[구글](https://google.com)
<br/>
&lt;a title='네이버로 이동'>네이버&lt;/a>

[네이버](https://naver.com "네이버로 이동")

## 이미지

&#33;&#91;대체텍스트&#40;alt&#41;&#93;&#40;주소&#41;
![HEROPY](https://heropy.blog/css/images/logo.png)

[![HEROPY](https://heropy.blog/css/images/logo.png)
](https://heropy.io)

## 인용문
> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
> (네이버 국어사전)  
>> 중첩된 인용문
>>> 중첩된 인용문

## inline코드 강조
CSS에서 `background` 혹은  
`background-image` 속성으로  
요소에 배경이미지를 삽입할 수 있습니다.

## block 코드 강조
```html
<a href='https://google.com' target='_blank'>Google</a>
```

```javascript
function func() {
    var a = 'AAA';
    return a;
}
```

```css
.list > li {
    position : absolute;
    top : 40px;
}
```

```bash
$ git commit -am 'Study Markdown'
```

```plaintext
동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세
```

## 표(table)

position 속성

값 | 의미 | 기본값
--|:--:|--:
static | 기준이 없음 | o
relative | 요소 자기자신 | x
absolute | 위치 상 부모 요소 | x
fixed | 뷰포트 | x

table header 밑의 --의 양쪽에 :를 넣으면  
:가 있는쪽으로 문자열이 정렬됨  
양쪽으로 넣으면 중간정렬  

## 원시 HTML(Raw HTML)

Markdown문서 내에 <span style="text-decoration: underline;">HTML코드</span>를 집어넣어서<br/>
<u>문서</u>를 꾸미는것

[Google](https://google.com)의 경우  
target을 지정할 수 없으므로, target을 지정하려는 경우  
a태그를 사용하여 target="_blank"를 넣어줌  
<a href='https://naver.com' target='_blank'>Naver</a>

&#33;&#91;&#93;&#40;&#41;
이미지의 경우 width, height를 적용할 수 없으므로  
width, height의 조절이 필요한 경우  
원시태그(img)를 사용해서 조절해야함.

<img src='https://heropy.blog/css/images/logo.png' width='70' alt='heropy'/>

## 수평선

&#45;&#45;&#45;

---

&#42;&#42;&#42;

***

&#95;&#95;&#95;
___

