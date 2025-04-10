# 마크다운 문법

★ 마크다운(Markdown) 이란?  
마크다운은 일반 텍스트 기반의 가벼운 마크업 언어의 일종으로, 특정한 기호를 사용하여 문서의 구조를 표현한다.  
일반 마크업 언어에 비해 문법이 쉽고 간단하다.  
HTML과 리치 텍스트(RTF) 등 서식 문서로 쉽게 변환되기 때문에 응용 소프트웨어와 함께 배포되는 README 파일이나 온라인 게시물 등에 많이 사용된다. 가독성이 좋고, 다양한 플랫폼에서 지원되기 때문에 개발자뿐만 아니라 많은 사람들이 사용하고 있다.  
파일의 확장자는 .md 또는 .markdown을 쓴다.

★ 탄생  
2004년, 존 그루버(John Gruber)와 아론 스워츠(Aaron Swartz)가 문서를 쉽고 빠르게 작성하는 것을 목적으로 만들었다.

★ 장점과 단점  
**<장점>**  
· 쉽고 간편해서 배우기 쉽고 직관적이다.  
· 가독성이 뛰어나 구조를 쉽게 파악할 수 있다.  
· 다양한 플랫폼에서 지원하며, HTML이나 PDF 등 다양한 형식으로 변환이 가능하다.

**<단점>**  
· 마크다운 자체로는 글자 색상 변경, 폰트 설정 등이 불가능하여 디자인 기능이 제한적이다.  
· 차트, 그래프, 각주 같은 고급 기능이 부족하며 추가 기능을 위해서는 HTML, LaTeX 등을 함께 사용해야 한다.  
· 플랫폼마다 지원하는 문법이 조금씩 달라 표준이 부족하다.

★ 문법  
**제목**  
· #을 붙여서 제목을 만든다. #의 개수가 많아질수록 제목의 크기가 작아진다.

# 1단계 제목

## 2단계 제목

### 3단계 제목

#### 4단계 제목

##### 5단계 제목

###### 6단계 제목

**<순서 없는 목록>**  
· -, *, + 를 사용하여 불릿 리스트(•)를 만든다. 들여쓰기로 하위 목록을 만들 수 있다.

- 첫 번째 항목
- 두 번째 항목
  - 하위 항목 1
  - 하위 항목 2

* 세 번째 항목
  - 하위 항목 1

**<순서 있는 목록>**  
· 숫자(1., 2., 3.)를 사용하여 만든다. 숫자는 1.로 통일해도 자동으로 순서가 맞춰진다.

1. 첫 번째 항목
2. 두 번째 항목
   1. 하위 목록 1
   2. 하위 목록 2
3. 세 번째 항목
   1. 하위 목록 1

**<굵게>**  
· ** 또는 __ 로 감싸서 만든다.

**굵은 글씨**  
**Bold 글씨**

**<기울임>**  
·* 또는 _ 로 감싸서 만든다.

_기울어진 글씨_  
_Italic 글씨_

**<취소선>**  
·~~ 로 감싸서 만든다.

~~취소 글씨~~

**<하이퍼링크>**  
· [링크명](URL) 로 만든다.

[멋쟁이사자처럼](https://likelion.net/)

**<인라인 코드>**  
· 백틱(`)을 이용하여 한 줄 코드를 만든다.

이것은 `인라인 코드` 입니다.

**<여러 줄 코드 블록>**  
·백틱(```) 3개로 감싸서 만든다. 프로그래밍 언어를 지정하면 문법 강조도 가능하다.

```javascript
function hello() {
  console.log("Hello, Markdown!");
}
```

**<인용문>**  
· > 기호를 사용하여 만든다. 여러 단계의 인용문도 가능하다.

> 인용문입니다.
>
> > 다음 단계의 인용문입니다.

**<개행>**  
· 띄어쓰기 두번 + 엔터로 개행한다. 마크다운에서는 일반적으로 엔터 한 번만으로는 줄바꿈이 되지 않는다.

첫번째 줄입니다.  
두번째 줄입니다.  
세번째 줄입니다.
