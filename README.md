###HTML Guide

####코딩 가이드
 - 소프트탭(2칸 공백) 사용
 - 문자열은 큰 따옴표 사용

####태그 속성 순서
 1. class : 재사용이 가능함
 2. id, name : 식별 가능
 3. src, for, type, href, value
 4. title, alt : 접근성 관련
 5. aria, role : 접근성 확장 관련

####상태 Attribute 작성
 - disabled, checked, selected 는 값을 생략
 - 닫는 태그가 없는 단일 태그는 /를 적지 않음(예 : &lt;br&gt;)
 - 불필요한 div, span 태그 자제

-----------

###CSS/Sass Guide

####코딩 가이드
 - 소프트탭(2칸 공백) 사용
 - 문자열은 큰 따옴표 사용
 - : 앞은 공백없음, 뒤는 공백 1칸
 - 중괄호 {, }는 각각 새 라인에 사용
 - 클래스명, 변수명은 -(hyphen) 사용
 - 다중선택자(,)는 줄을 바꿔서 표시
 - ID 선택자는 레이아웃 외에 되도록 사용 금지
 - 스크립트용 클래스는 js- 접두어 사용
 - border가 없을 경우 0 사용
 - 중첩 선택자는 3회까지(3회 이상 들어간다면 HTML과 너무 강하게 연결되어있거나 클래스로 분리 가능한지 확인)

####범주화 
 - 베이스 : 초기화, 기본 스타일
 - 레이아웃 : 위치, 박스
 - 모듈 : 재사용 가능한 것
 - 상태 : 모듈과 레이아웃의 표현을 변경함(예 : hover 효과, active 효과)
 - 테마

####타입별 작성 순서
 1. 위치
 2. 박스
 3. 텍스트
 4. 그 외 시각적 요소(테두리 배경 등)
 5. @include
 6. 중첩 선택자
