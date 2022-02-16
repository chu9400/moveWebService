# React 기초
# moveWebService

### 무작정 쓰는 리액트 정보

속성으로 value 를 가질 수 있으면 onChange 속성을 붙일 수 있다.
useState의 두번째 인자인 modifier함수를 실행하면 해당 컴포넌트가 리렌더링 된다.  
예) const [index, setIndex] = React.useState();
setIndex가 modifier함수.

[리렌더링 조건]
1) props이 바뀔때
2) state가 바뀔때
3) 부모 컴포넌트가 리렌더링 될 때

###[Props]
Props는 일종의 방식이다.
부모 컴포넌트로 부터 자식 컴포넌트에 데이터를 보낼 수 있게 해주는 방법