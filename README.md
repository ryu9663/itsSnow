# itsSnow
눈이와요!!

[니콜라스 영상보고만듬](https://www.youtube.com/watch?v=3CuUmy7jX6k)


![ezgif com-gif-maker](https://user-images.githubusercontent.com/66232436/209904599-c4e232c4-ada7-496b-976e-1faa72ce15a0.gif)


---
리액트에서 쓰려면 그냥 index.html에 넣어야 할 것 같음

이 레포지토리는 dom element를 계속 지웠다 만들었다 하는데 이는 가상돔시스템에 맞지 않음

아래와 같이 작성하면 가상돔은 `<div id = 'root'>` 에서 돌고 눈내리는 배경은 가상돔과 독립적으로 `<div class='snowflake'>`에서 작동하게 된다.
(SSR은 아님, snowflake.js에 의해 동작함)

<img width="553" alt="스크린샷 2022-12-29 오후 9 27 05" src="https://user-images.githubusercontent.com/66232436/209951054-6eaac687-99e2-47f1-87a6-6a447915bcfc.png">


리액트웹에 적용한 모습
![ezgif com-gif-maker (1)](https://user-images.githubusercontent.com/66232436/209951317-a9b35999-8f73-4c11-b9b8-c2117ed4bd48.gif)
