# moveWebService


useState의 두번째 인자인 modifier함수를 실행하면 해당 컴포넌트가 리렌더링 된다.

예) cosnt [index, setIndex] = React.useState();
setIndex가 modifier함수

[리렌더링 조건]
1) props이 바뀔때
2) state가 바뀔때
3) 부모 컴포넌트가 리렌더링 될 때
