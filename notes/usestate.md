# ⭐ UseState

* 화살표함수

const funcName () => {
//body
}

* 리액트에서 이벤트 설정을 주로 "on이벤트이름={함수이름}" 형태로 작성한다.

* state 선언 방식
  const [number, setNumber] = useState(0);
return(
<div>{number}</div>
)

* usSstate 동작 원리
배열 비구조화 할당을 활용
첫번째 원소는 현재 상태, 두번째 원소는 setter 함수
원래대로라면

const numberState = useState(0);
const number = numberState[0];
const setNumber = numberState[1];
