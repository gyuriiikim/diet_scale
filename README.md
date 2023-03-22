<h1>다이어트 체중계</h1>
<p>당신의 건강몸무게를 알아보세요!</p>

<P>계산식) 적정체중 = (본인신장-100)*0.9</p>

<P>변수명 예) userHeight, userWeight, normal_w</p>

---
<P>1.prompt 현재 키, 몸무게 입력받기</p>

`let userHeight = window.prompt('당신의 현재 키는?')`

`let userWeight = window.prompt('당신의 몸무게는?')`

`let normal_w = (userHeight-100)*0.9`

`let result = userWeight-normal_w`

---
<P>2. DOM객체 변수 생성하기</p>

`const span_height = document.getElementsByClassName('height')[0]`
`const span_weight = document.getElementsByClassName('weight')[0]`
`const span_normal = document.getElementsByClassName('normal')[0]`
`const span_weight2 = document.getElementsByClassName('weight2')[0]`

---

<P>검사</p>

`console.log(userHeight, userWeight, normal_w, result)`

`console.log(span_height, span_normal, span_weight, span_weight2)`

---

<P>DOM변수에 데이터변수 생성하기</p>

`span_height.innerHTML = userHeight`

`span_weight.innerHTML = userWeight`

`span_normal.innerHTML = normal_w`

`span_weight2.innerHTML = result`

---


<P></p>
<P></p>
