# reactSkill
리액트를 다루는 기술

MVC, MVVM, MVW 등과 같은 여러 구조가 지닌 공통점은 
모델과 뷰가 있다는 것이다.
모델은 어플리케이션에서 사용하는 데이터를 관리하는 영역이고,
뷰는 사용자에게 보이는 부분이다.

페이스북팀은 어떤 데이터가 변할 떄마다 어떤 변화를 줄지 고민하는 것이 아니라
그냥 기존 뷰를 날려 버리고 처음부터 새로 렌더링 하는 방식이다.

오직 V만 신경 쓰는 라이브러리이다.

리액트에서는 뷰를 업데이트할 때 "업데이트 과정을 거친다"라고 하기보다는
"조화 과정을 거친다"라고 하는 것이 정확한 표현이다.

DOM은 XML이나 HTML로 작성한다.

Virtual DOM을 사용하면 실제 DOM에 접근하여 조작하는 대신, 
이를 추상화한 자바스크립트 객체를 사용한다.

Node.js는 크롬 V8 자바스크립트 엔진으로 빌드한 자바스크립트 런타임이다.
이것으로 웹 브라우저 환경이 나닌 곳에서도 자바스크립트를 사용하여 연산할 수 있다.

ES6를 호환해주는 바벨
모듈화된 코드를 한 파일로 합치고(번들링) 코드를 수정할 때마다 리로딩하는 여러 기능을 지닌 웹팩이 있다.

npm으로 수많은 개발자가 만든 패키지(재사용 가능한 코드)를 설치하고 설치한 패키지의 버전을 관리할 수 있다.


