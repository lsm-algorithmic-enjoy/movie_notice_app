# Movie Notice Website project

프로젝트 설명: fetch 대신 axios를 사용하여 movie app start 프로젝트와 유사한 로직 적용을 통해 영화 정보 웹사이트를 구현하였습니다.
(깃허브 업로드 문제로 BrowserRouter대신 HashRouter를 사용하였고 각각의 Route가 중복 렌더링되어 화면에 동시에 나타나는 문제를 Home Route 코드에 exact={true}를 삽입하여 해결했습니다.)

<참고: 자바스크립트의 setTimeout을 이용하여 componentDidMount를 통해 6초 후에 로딩상태를 false로 전환하는 코드.
구현코드: componentDidMount() {
setTimeout(() => {
this.setState({ isLoading: false });
}, 6000);
}>

CSS 버그 해결 사항: Link component로 인해 CSS가 제대로 작동하지 않는 문제를 display: contents; 적용을 통해 해결하였습니다.
