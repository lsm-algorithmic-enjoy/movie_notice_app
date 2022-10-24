# Movie Notice Website project

프로젝트 설명: fetch 대신 axis 사용하여 movie app start 프로젝트와 유사한 로직을 적용하여 영화 정보 앱 구현 웹사이트를 구현하였습니다. CSS 스타일 적용하였습니다.
(깃허브 업로드 문제로 BrowserRouter대신 HashRouter 이용과정에서 중복 렌더링되어 화면에 같이 나타나는 문제를 Route에 exact={true} 삽입하여 해결했습니다.)

<참고: 자바스크립트의 setTimeout을 이용하여 componentDidMount를 통해 렌더링을 직후 6초가 지나서 로딩상태를 false로 전환하는 코드.
구현코드: componentDidMount() {
setTimeout(() => {
this.setState({ isLoading: false });
}, 6000);
}>
