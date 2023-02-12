# 웹 접근성
+ 모든 사용자가 신체적, 환경적 조건에 따른 차별 없이 웹 사이트를 이용할 수 있도록 보장하는 것
- 신체적 : 장애인, 고령자, 비장애인 등
- 환경적 : 회선 속도, 기기, 브라우저 등

## 웹 접근성 지침(WCAG)
- 인지성(Perceivable) : 
모든 콘텐츠는 사용자가 인식 가능해야한다.
- 운용성(Perable) : 
사용자가 모든 기능에 대해 조작이 가능해야한다.
- 이해성(Understandable) : 
모든 사용자에게 콘텐츠에 대해 이해되어야한다.
- 내구성(Robust) : 
미래의 기술로도 현재의 콘텐츠를 이용할 수 있어야한다.

## 웹 접근성 지키기
### 대체 텍스트
```
<img src="image01.jpg" alt="벨리곰 에디션 최대55% 할인">  <!--콘텐츠 이용에 필요한 이미지-->
<img src="image02.jpg" alt="">  <!--디자인용 이미지-->
<img src="image03.jpg" alt="메인 페이지로 가기 버튼">  <!--버튼이미지-->
```

### 자동재생 배경음 금지
화면 낭독 프로그램을 이용하는 사용자에게 방해가 될 수 있다.

### Tab키를 이용해 콘텐츠 선택 가능
Tab 키를 이용하여 콘텐츠를 자유롭게 이용할 수 있게 한다.
```
<p tabindex='0'>탭 키를 이용할 수 있게 함</p>
<p tabindex='-1'>탭 키를 이용할 수 없게 함</p>

<p tabindex='1'>탭 키의 순서 지정</p>
<p tabindex='2'>탭 키의 순서 지정</p>
```

### 페이지 언어 지정
html 태그에 언어를 지정한다.
```
<html lang="ko">
<p>나는 <span lang="en">hungry</span></p>
```

웹접근성 연구소
https://www.wah.or.kr:444/