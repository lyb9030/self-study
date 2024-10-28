# Tailwind 언어 취합 내용 (abc, ㄱㄴㄷ 순서)

## 개념

- 테일윈드 (Tailwind)는 유틸리티 기반 (Utility-first) 개발 방식을 제공
- 필요한 부품을 조립하는 방식으로 사용자 입맞에 맞게 커스터마이징이 가능
- 모바일 퍼스트 (Mobile-first) 디자인
- View 중심의 쉬운 디자인 변경
- 다만 HTML 요소에 Class 속성이 혼란스럽게 되어있음
- 항상 앞에 'class'를 선언하고 작성을 해야 함.

## A

## B

1. bg-white -> 배경 색(background-color) 를 하얀색으로 변경<br>

2. bg-색상-넘버 -> background-color 를 원하는 색상과 채도를 넣어서 사용<br>
   넘버는 100번 단위의 숫자로 작성을 해야함 <br>
   EX) bg-cyan-200 : 배경을 Cyan 색상의 200 채도로 적용 <br>

3. block -> display의 값을 블럭을 사용함<br>
   해당 코드의 밖에 박스 처리로 보여줌<br>

## C

## D

## E

## F

1. flex -> display의 값을 flex로 설정 함<br>

2. flex-col -> display의 값을 flex로 설정된 것에서 방향 (direction)의 값을 열 (column)로 정렬함<br>

3. flex-row-reverse -> flex로 설정된 display의 값을 열 (row) 방향 (direction) 으로 지정하는데 역 (reverse) 으로 뒤집어서 정렬함<br>

## G

1. gap-넘버 -> 요소와 요소사이의 공간을 설정함<br>
   EX) gap-5 : 갭을 5 (20px, 1.25rem)으로 설정함<br>

2. group -> 부모 요소의 스타일을 자식 요소에 지정해야 하는 경우 부모에 먼저 그룹을 설정하여, 자식에게 상속 시킴<br>
   주로 hover: 와 같이 사용을 함<br>

## H

1. hover: -> hover 상태 (마우스를 해당 위치에 올린 상태) 가 되면 : 이후의 내용으로 변경을 하게 함<br>
   hover는 주로 group의 하위 요소로 사용 되곤 함<br>

2. hover:bg=색상-넘버 -> hover (마우스를 올릴 경우) 배경 색(background-color)를 지정한 색상의 넘버로 변경<br>
   EX) hover:bg-prmary-300 : 마우스가 해당 이미지로 올라갈 경우 배경색을 prmary 색의 300 채도로 적용<br>

3. h-screen -> 높이 (height) 의 값을 100vh 로 설정함<br>

## I

1. items-center -> items의 값을 중앙 (center)로 정렬 함<br>

## J

1. justify-center -> justify-content의 값을 중앙 (center)로 정렬 함<br>

## K

## L

## M

1. m-넘버 -> margin의 값을 주는 언어<br>
   EX) m-10 : margin의 값을 10 번째 값 (40px, 2rem)으로 줌

2. my-넘버 -> margin top 과 margin bottom을 각각 주는 언어 <br>
   EX) my-10 : margin top 과 margin bottom을 각각 10번째(40px, 2.5rem) 으로 줌<br>

## N

1. no-underline -> 글짜 (text) 의 선(line)을 꾸며줌 (decoration)<br>
   EX) text-decoration-line: none; -> 텍스트의 선을 없음으로 표시<br>

## O

## P

1. p-넘버 -> 패딩 (padding) 값을 원하는 넘버로 지정<br>
   EX) p-5 : 패딩 (padding) 값을 5 (20px, 1.25rem) 으로 지정<br>

## Q

## R

1. rounded- -> 해당 박스 (box) 의 모서리를 해당 사이즈 만큼 둥글게 함<br>
   EX) rounded-xl : 해당 박스의 모서리를 xl 사이즈 (7px)만큼 둥글게 만듬<br>

## S

1. shrink-넘버 -> flex 속성에서 레이아웃을 벗어난 아이템 너비를 분배해서 줄이는법<br>
   기본 속성값은 1로 적용되며, 자동으로 아이템이 축소되지 않기위해서는 0으로 설정 하여야 함<br>

## T

1. text-white -> 글짜의 색상을 하얀색으로 변경 <br>

2. text-넘버 -> font-size 와 line-height 의 사이즈를 각각 주는 언어<br>
   단위 : lg, 3xl 등
   EX) text-3xl : font-size 와 line-heigh 의 사이즈를 각각 3xl 으로 줌<br>

## U

## V

## W

## X

## Y

## Z

## 기타 부호

10. no-underline -> 글짜 (text) 의 선(line)을 꾸며줌 (decoration)<br>
    EX) text-decoration-line: none; -> 텍스트의 선을 없음으로 표시<br>
