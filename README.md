# MarkDown
For Studying MarkDown!


줄바꿈을 할 때는 enter를 2번 눌러서 한 라인을 비워두어야한다.

## 제목 "#"
"#" 2개 까지는 하단에 구분선이 생김
#### #는 6개까지 사용 가능
##### 제목으로 사용하고 싶다면 #과 text 사이에 한칸의 여백 필요

## 가로줄
---
- - -
***
* * *

## 목록
####순서 있는 목록
1. 목록은 항목 전체가 하나의 단락이기에
2. 한칸의 여백 라인을 둘 필요가 없다
####순서 없는 목록
 - "-" or "+" or "*"
 - Tab key를 통해 여러 단계 목록 생성 가능
  + Tab1
    * Tab2

## 텍스트 강조
- **굵게1** or __굵게2__ : 앞뒤로 ** or __ 로 감싼다.
-  *기울기1* or _기울기2_ : 앞뒤로 * or _ 로 감싼다.
- ***굵은기울임*** or ___굵은기울임___ : 앞뒤로 *** or ___ 로 감싼다.
- ~~취소선~~ : 앞뒤로 ~~ 으로 감싼다.

## 소스코드
Grave(백콤) 기호를 사용 `Grave`   

`한 줄의 소스`를 삽입할 때는 ` 를 앞뒤에 붙이고, 
```rl
여러줄을 
삽입할 때
```    
는 ```를 앞뒤에 붙인다.

## 링크
하이퍼 링크는 다양한 형태로 삽입 가능하다.   
`<링크주소>` : 주소가 그대로 화면에 나타나고, 클릭 시 해당 주소로 이동   
<https://github.com/jej10e5>   

`[링크텍스트](링크주소)`: 링크 텍스트만 나타나고, 텍스트 클릭 시 해당 주소로 이동   
[MyGit](https://github.com/jej10e5)   

`[링크텍스트](링크주소,"설명")` : 링크 텍스트가 나타나고, 링크에 마우스를 올리면 "설명"이 출력된다.   
[MyGit](https://github.com/jej10e5, "내 깃허브 주소")   
    
## 줄바꿈
마지막 줄에서    
**3번** 띄어쓰기를 하면 줄이 바뀐다.

---
# Design on readme

## bedge
<https://shields.io/>   
<https://simpleicons.org>  
![image](https://user-images.githubusercontent.com/61136630/192518625-accd1e8b-ab96-422c-ba6e-ce48704d4f15.png)    
 :one: 로고이름, :two: 배경색   
:star: 배경색 입력시 #는 빼야함   
`<img src="https://img.shields.io/badge/내용-배경색?style=flat&logo=로고이름&logoColor=폰트색"/>`   
<img src="https://img.shields.io/badge/인스타-E4405F?style=flat&logo=Instagram&logoColor=white"/>

## Github status
<https://github.com/anuraghazra/github-readme-stats>   

## header & footer
<https://github.com/kyechan99/capsule-render>
```
![header](https://capsule-render.vercel.app/api?type=wave&color=gradient &height=300&section=header&text=capsule%20render&fontSize=90)
```
![header](https://capsule-render.vercel.app/api?type=wave&color=gradient&height=300&section=header&text=capsule%20render&fontSize=90)

## emoji
<https://gist.github.com/rxaviers/7360908>
