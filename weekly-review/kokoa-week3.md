### 이번 주 목표

---

- [ ] _코코아 클론 강의 6.11까지 완강_
- [ ] _코코아 클론 챌린지 완출_

### 이번 주 결과

---

- [ ] _코코아 클론 강의 부분 완강 실패 😫_
- [ ] _코코아 클론 챌린지 완출_

### 😎 기억할 것

---

- _중앙에 위치하게 만드는 법_

  - alt 1
    - justify-content:center와 어떤 차이가 있는지는 모르겠지만,
    - 부모 {
      justify-content: center;
      align-items: center;}
    - left-end {
      margin-right: auto;}
    - right-end {
      margin-left: auto;}

  -alt 2
  - 부모{
    justify-content: center;
    align-items: center;}
  - column\*3 -> 각 width:33%
  - column:nth-child(2) {
    justify-content:center; 혹은
    text-align:center;
    }
  - column:last-child {
    justify-content:flex-end;
    }
