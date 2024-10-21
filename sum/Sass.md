# Scss 언어 취합 내용 (abc, ㄱㄴㄷ 순서)

## A

## B

## C

## D

## E

## F

## G

## H

## I

## J

## K

## L

## M

## N

## O

## P

## Q

## R

## S

## T

## U

## V

## W

## X

## Y

## Z

## 기타 부호

1. // -> Scss에서의 주석, 내용은 Scss에서만 보임<br>
   <br>
2. /\* -> Scss에서의 주석, 내용은 Scss와 Css 파일에서 출력이 됨, Css 압축모드에서는 출력 안됨<br>
   <br>
3. /\*! -> Scss에서의 주석, 내용은 Scss와 Css파일에서 출력이 됨, Css 압축모드에서도 출력이 됨<br>
   <br>
4. @at-root -> 부모를 따르지 않는 최 우선의 사용 코드 <br>
   EX) 부모 요소에서 'border:0' 으로 하였으나, '@at-root boder:1'로 할 경우 border은 1로 출력이 됨<br>
   <br>
5. @extend : 부모의 클래스를 따라갈때 사용하는 코드 <br>
   EX) 부모 요소에서 'abc {color=red'}로 코딩 할 경우, 자식 요소에서 '@extend .abc'를 선언할 경우 색상으 red로 표시가 됨<br>
   <br>
6. & -> 접미사로 사용, 클래스를 상세히 구조화 할때 이용 함<BR>
   EX) 'TabMenu &item' 으로 작성할 경우-> Css에서는 'Tabmenu\_\_item' 로 노출이 됨<br>
   <br>
7. % : 플레이스홀더 선택자로 만듬, 주로 Css에는 코드를 노출시키지 않을 때 사용
   EX) 부모 요소에서 '%abc {color=red}로 코딩 할 경우, 자식 요소에서 'efg{%abc}'로 코딩하게 되면 Css에서는 'efg{color=red}'로 코딩이 됨
