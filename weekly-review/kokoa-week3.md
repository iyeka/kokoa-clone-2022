### 이번 주 목표

---

- [ ] _코코아 클론 챌린지 완출_
- [ ] _바닐라JS 강의 #3.5까지 완강_

### 이번 주 결과

---

- [ ] _코코아 클론 챌린지 완출_
- [ ] _바닐라JS 강의 부분 완강 실패 😫_

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

- _GITHUB Pages 배포_

  - gh-pages branch로 fetch
  - Github Pages로 배포한 결과물은 https://(userID).github.io/(repositoryTitle)의 형태로 제공됩니다.
  - 파일 제목에 대문자가 없어야 함.
  - 수정시 master branch에서 수정 -> commit -> fetch -> gh-pages branch -> branch: update from main -> fetch

- _flex child의 순서 바꾸는 법_

  - 바꾸고자 하는 flex child {
    order: 1;}
  - flex parents {
    flex-direction: row-reverse;
    }

- _애니메이션 마지막 keyframes 유지하는 법_

  - animation: forwards;

- _요소 감추는 법_

  - Element 무시하려면 visibility: hidden
  - html에서 아예 없애려면 JS 써야함

- _.reply:focus-within .reply-column:_

  - reply 내부에 어떤 element가 focus되어 있다면? reply-column에 뭔갈 해라

  ### 😭 보완사항

---

- _코코아 클론코딩 #6.39 뭔 말인지 하나도 모르겠음... css animations 추가 공부가 필요할 듯_
- _코코아 클론코딩 최종제출과제 디벨롭_

## 📌 주간 회고록을 제출해주세요 (필수)

[10주스터디\_Weekly_ProgressReport](https://docs.google.com/spreadsheets/d/1UZNSc5GhAPwFGSGfqMW9qDQjQBzab-5vgoywnQGaPzg/edit?usp=sharing)

## 핵심 3줄 요약 (예시)

- _css animations 연습이 필요하다 주말에 연습할 것_
- _코코아클론 최종제출과제 발전시킬 것_
- _디스코드 사이드프로젝트 방에 참여할 수 있도록 사이드프로젝트 시작할 것_
