# frontend job interview
개발 면접때 자주나오는 질문들과 그에대한 상세한 설명을 기록합니다.
대충 알고있던 개념들을 더욱 명확하게 합니다. 면접대비를 위함이지만, 본질적으로는 개념을 확실하게 익히자는 의도를 갖고있습니다.

# 태그 리스트
- `browser`, `dom`, `event-loop`, `storage`,
- `js`, `callback`, `promise`, `async`, `prototype`, `execution-context`, `error-handling`, `this`, `scope`, `class`, `event`
- `html`, `defer`, `async`, `ts`
- `react`, `jsx`, `hook`, `context`, `ref`, `redux`, `react-query`
- `network`, `secure`
- `performance`, `optimization`, `ssr`
- `pattern`, `paradigm`
- `module`, `bundle`, `webpack`, `babel`
- `css`, `scss`, `emotion`, `styled-component`
- `cs`
- `data-structure`, `algorithm`
- `critical`, `high`, `normal`, `low` (중요도)
- `why`, `history`

# 질문 리스트

## JS/TS

### Critical

- prototype의 장점이 무엇이길래 javascript에서 채택했을까요? 그렇다면 prototype은 무엇인가요? [`critical`, `js`, `prototype`, `why`]
- 최근 js의 동향에 대해 설명해 주세요 [`critical`, `js`]
- javascript의 문제점으로 무엇이 있고, 왜 그게 문제점일까요? [`critical`, `js`, `why`]
- 왜 typescript가 각광받고, js에선 ts를 표준으로 합치려 할까요? (벌써 Stage 1;;) [`critical`, `ts`, `why`]
- javascript 태동기에 목표는 무엇이고, 지금과 어떤게 달라졌나요? [`critical`, `js`] 
- ECMAScript에서 해결하려는 문제는 무엇이고, 앞으로의 과제는 무엇일까요? [`critical`, `js`] 
- 브라우저가 동시성 문제를 어떻게 해결했는지 설명해 주세요 [`critical`, `browser`, `event-loop`] 
- 명령형(Imperative) 프로그래밍 vs 선언형(Declarative) 프로그래밍 [`critical`, `js`, `paradigm`] 
- 최근에 개발중 했던 추상화에 대해 소개해 주세요 [`critical`, `js`] 

### High

- var vs let vs const [`high`, `js`] 
- callback vs promise [`high`, `js`, `async`] 
- 실행 컨텍스트에 대해 설명해 주세요 [`high`, `js`, `execution-context`] 
- 실행 컨텍스트가 없는 다른 언어가 있을까요? [`high`, `js`, `execution-context`] 
- 일반 함수와 화살표 함수의 차이점은 무엇일까요? [`high`, `js`] 
- this에 대해서 설명해 주세요 [`high`, `js`]
- promise에 비해 async/await가 가지는 장점은 무엇인가요? [`high`, `js`, `async`] 
- 순수 함수란 무엇이고 이 함수가 가지는 장점은 무엇인가요? [`high`, `js`] 
- 스코프 체인이란 무엇인가요? [`high`, `js`]
- 애니메니션을 구현할때 requestAnimationFrame이 setTimeout보다 어떤점에서 더 좋은건가요? [`high`, `browser`, `event-loop`]
- cookies vs localStorage vs session storage [`high`, `js`, `network`]
- accessToken을 어떻게 관리하는것이 안전할까요? [`high`, `js`, `network`]
- 무한 스크롤을 구현할때 intersection observer가 scroll event listener보다 더 좋은 이유를 설명해 주세요 [`high`, `js`, `browser`, `event-loop`]
- commonjs vs es6 module [`high` `js`, `module`] 
- 클로저에 대해 설명해 주세요 [`high`, `js`] 
- 렉시컬 환경(Lexical Environment)에 대해 설명해 주세요 [`high`, `js`] 
- javascript가 유동적인 언어인 이유는 무엇인가요? [`high`, `js`] 
- 깊은 복사와 얕은 복사에 대해 설명해 주세요 [`high`, `js`] 
- css 으로 animation을 구현하는것과 js로 animation을 구현하는것의 차이점에 대해 설명해 주세요 [`high`, `js`, `css`] 
- javascript가 객체 지향 언어라고 하는데 그 이유가 무엇일지 이야기 해주세요 [`high`, `js`, `pattern`] 
- primitive data인데 어떻게 내장 함수를 사용할 수 있는걸까요? (`"Hello".toLowerCase()`); [`high`, `js`] 
- type vs interface  [`high`, `ts`]
- MVC pattern에 대해 설명해 주세요  [`high`, `js`, `pattern`]
- Flux pattern에 대해 설명해 주세요  [`high`, `js`, `pattern`]

### Normal

- 함수레벨 스코프 vs 블록레벨 스코프  [`normal`, `js`, `scope`]
- generator에 대해 설명해 주세요  [`normal`, `js`]
- iterable에 대해 설명해 주세요  [`normal`, `js`]
- call vs apply vs bind [`normal`, `js`] 
- 생성자 함수와 일반 함수의 차이점은 무엇인가요? [`normal`, `js`] 
- mutable vs immutable [`normal`, `js`] 
- event delegation에 대해 설명해 주세요 [`normal`, `js`, `pattern`] 
- undefined vs null [`normal`, `js`] 
- symbol은 왜 나왔고 언제 사용하면 좋을지 설명해 주세요 [`normal`, `js`, `why`] 
- falsy한 타입과 truthy한 타입에 대해 설명해 주세요 [`normal`, `js`] 
- hasOwnProperty의 위험성에 대해 설명해 주세요 [`normal`, `js`] 
- primitive type vs object [`normal`, `js`] 
- 일급 함수란 무엇인가요? [`normal`, `js`] 
- 객체 변경을 방지하는 방법에는 어떤것들이 있을까요? [`normal`, `js`] 
- 객체 리터럴로 만든 객체와 생성자 함수로 만든 객체는 어떤 차이점이 있나요? [`normal`, `js`] 
- strict mode로 했을때 어떤 장점이 있나요? [`normal`, `js`] 
- 객체 vs Set vs Map [`normal`, `js`] 
- HTMLCollection vs NodeList [`normal`, `js`, `dom`] 
- innerHTML vs insertAdjacentHTML [`normal`, `js`, `dom`] 
- HTML 어트리뷰트 vs. DOM 프로퍼티 [`normal`, `js`, `DOM`] 
- Event Handler내의 this는 어떤 값을 가지고 있나요? [`normal`, `js`, `event`] 
- setInterval vs recursive setTimeout [`normal`, `js`, `timer`] 
- macro task queue 사용 사례에 대해 설명해 주세요 [`normal`, `browser`, `event-loop`] 
- micro task queue 사용 사례에 대해 설명해 주세요 [`normal`, `browser`, `event-loop`] 
- bubbling vs capturing [`normal`, `js`, `event`] 
- bubbling 특성을 활용한 예제를 소개해 주세요 [`normal`, `js`, `event`] 
- capturing 특성을 활용한 예제를 소개해 주세요 [`normal`, `js`, `event`] 
- Singleton Pattern에 대해 설명해주세요 [`normal`, `js`, `pattern`] 
- Proxy Pattern에 대해 설명해주세요 [`normal`, `js`, `pattern`] 
- Observer Pattern에 대해 설명해주세요 [`normal`, `js`, `pattern`] 
- Factory Pattern에 대해 설명해주세요 [`normal`, `js`, `pattern`] 
- Prototype Pattern에 대해 설명해주세요 [`normal`, `js`, `pattern`] 
- Element vs Node [`normal`, `js`, `dom`] 
- element.onclick(doSomthing) vs element.addEventListener(doSomething) [`normal`, `js`, `event`] 
- debounce vs throttle [`normal`, `js`, `performance`] 
- history api [`normal`, `js`, `browser`] 

## Optimization

### Critical

- Critical Rendering Path 대해 설명해 주세요 [`critical`, `browser`] 
- rendering을 차단하는 리소스는 어떤것들이 있나요? [`critical`, `browser`] 

### High

- preload vs preconnect vs prefetch [`high`, `browser`] 
- page load event에 대해 설명해 주세요 [`high`, `browser`] 
- defer vs async [`high`, `browser`, `html`] 
- async의 단점에 대해 설명해 주세요 [`high`, `browser`, `html`] 
- defer 단점에 대해 설명해 주세요 [`high`, `browser`, `html`] 
- Webpack의 Code Spliting에 대해 설명해 주세요 [`high`, `bundle`, `webpack`, `module`] 
- Incremental Rendering과 SSR(server side rendering)에 대해 설명해 주세요 [`high`, `ssr`] 
- SSR(server side rendering)의 장점은 무엇인가요? [`high`, `ssr`] 
- CSR과 SSR의 차이점에 대해 설명해 주세요 [`high`, `ssr`] 
- 왜 CSS <link>를 <head>에 놓는것이 좋은지 설명해 주세요 [`high`, `browser`, `html`] 

### Normal

- reflow를 발생시키는 style property는 대표적으로 어떤것들이 있을까요? [`normal`, `browser`] 
- repaint를 발생시키는 style property는 대표적으로 어떤것들이 있을까요? [`normal`, `browser`] 
- 번들 사이즈를 줄이려면 어떻게 해야 할까요? [`normal`, `bundle`, `webpack`] 
- tree shaking에 대해 설명해 주세요 [`normal`, `bundle`, `webpack`, `module`] 
- Static/Dynmic Import에 대해 설명해 주세요 [`normal`, `js`, `module`] 

## Network

### Critical

- 주소창에 www.naver.com을 치고 나서 발생하는 일들에 대해 설명해 주세요 [`critical`, `network`, `browser`] 
- RESTfull API에 대해 설명해 주세요 [`critical`, `network`, `paradigm`] 
- Get vs Post vs Put vs Patch vs Delete [`critical`, `network`] 
- CORS에 대해 설명해 주세요 [`critical`, `network`] 

### High

- OSI 7계층에 대해 설명해 주세요 [`high`, `network`] 
- TCP/IP에 대해 설명해 주세요 [`high`, `network`] 
- TCP/IP vs UDP [`high`, `network`] 
- http/1.1 vs http/2 [`high`, `network`] 
- DNS에 대해 설명해 주세요 [`high`, `network`] 
- URL vs URI [`high`, `network`] 
- CDN(Content Delivery Network)에 대해 설명해 주세요 [`high`, `network`] 
- 웹 소켓에 대해 설명해 주세요 [`high`, `network`] 
- http header의 cache-control에 대해 설명해 주세요 [`high`, `network`, `browser`] 
- 사이트를 배포 했는데 사용자 브라우저에 캐쉬가 남아있는 경우 어떻게 해야 할까요? [`high`, `network`, `browser`] 
- http vs https [`high`, `network`, `secure`] 
- XSS(Cross-site scripting)에 대해 설명해 주세요 [`high`, `network`, `secure`] 
- CSRF(Cross-Site Request Fogery)에 대해 설명해 주세요 [`high`, `network`, `secure`] 

### Normal

- GSLB(Global Server Load Balancing)에 대해 설명해 주세요 [`normal`, `network`] 

## React

### Critical

- react가 해결하려는 문제는 무엇인가요? [`critical`, `react`] 
- 컴포넌트란 무엇인가요? [`critical`, `react`] 
- ContextAPI의 문제점은 무엇인가요? [`critical`, `react`, `hook`, `context`] 
- 웹 개발의 시대가 jQuery에서 React나 Vue로 넘어온 이유가 무엇일까요? [`critical`, `react`] 
- React와 Vue는 서로가 어떤게 다르길래, 사용 대상이 나뉘는 걸까요? [`critical`, `react`] 
- 리액트의 재조정(reconciliation)과정에 대해 설명해 주세요 [`critical`, `react`] 

### High

- SPA의 장점에 대해 설명해주세요 [`high`, `react`] 
- Render Phase와 Commit Phase에 대해서 설명해 주세요 [`high`, `react`] 
- Hooks의 장점은 무엇인가요? [`high`, `react`] 
- Class Component vs Function Component [`high`, `react`] 
- CSS in CSS(css, sass, css-module) vs CSS in JS(emotion, styled-component) [`high`, `react`] 
- state vs props [`high`, `react`] 
- useEffect의 dependency를 설정해 주지 않으면 어떤 문제가 발생하나요? (staled state) [`high`, `react`, `hook`] 
- useCallback vs useMemo vs React.memo [`high`, `react`, `hook`] 
- React팀에서 모든 컴포넌트에 React.memo를 기본으로 적용해놓지 않은 이유가 무엇이라 생각하시나요? [`high`, `react`, `hook`] 
- ContextAPI는 언제 사용하면 좋을까요? [`high`, `react`, `hook`, `context`] 
- useEffect vs useLayoutEffect [`high`, `react`, `hook`] 
- useTransition은 어떤 문제를 해결하기 위해 나온 훅인가요? [`high`, `react`, `hook`] 
- Prop drilling을 해결하기 위한 방법에 대해 설명해 주세요 [`high`, `react`, `context`] 
- JSX에서 if-else를 왜 사용할 수 없나요? [`high`, `react`, `jsx`] 
- Class Component에 비해 Hook + Functional Component가 가지는 이점은? [`high`, `react`] 
- useState는 어떻게 이전 상태를 기억하나요? [`high`, `react`, `hook`] 
- 왜 조건문 안에 hook을 쓰면 안될까요? [`high`, `react`, `hook`] 
- 배열을 map돌려서 list를 그릴때 key가 왜 필요한가요? [`high`, `react`, `performance`] 
- index를 key로 쓰면 안되는 이유에 대해 설명해 주세요 [`high`, `react`, `performance`] 
- Controlled Component vs Uncontrolled Component [`high`, `react`] 
- Hook은 Presentational/Container pattern을 대체할 수 있나요? [`high`, `react`, `pattern`] 
- VirtualDOM이 필요한 이유에 대해 설명해 주세요 [`high`, `react`] 
- React18에 본격적으로 적용된 concurrent mode에 대해 설명해 주세요 [`high`, `react`] 
- Fiber에 대해 설명해 주세요 [`high`, `react`] 
- 컴포넌트 분리 기준에 대해 설명해 주세요 [`high`, `react`] 
- 직접 만들어본 Custom Hook에 대해 소개해 주세요 [`high`, `react`] 
- Container/Presentation Pattern에 대해 설명해주세요 [`high`, `react`, `pattern`] 
- Higher-Order Component Pattern에 대해 설명해주세요 [`high`, `react`, `pattern`] 
- Hooks Pattern에 대해 설명해주세요 [`high`, `react`, `pattern`] 
- redux가 context api에 비해 가지는 장점에 대해 설명해 주세요 [`high`, `react`, `redux`] 
- react-query를 왜 쓰셨나요? [`high`, `react`, `react-query`, `why`] 
- react-query의 stale time과 cache time의 차이에 대해 설명해 주세요 [`high`, `react`, `react-query`, `why`] 
- Class Component의 life cycle과 Hook + Function Component의 life cycle의 차이점에 대해 설명해 주세요 [`high`, `react`] 
- Suspense와 Error Boundary를 사용했을때의 장점에 대해 설명해 주세요 [`high`, `react`, `pattern`] 

### Normal

- 같은 값으로 setState해도 re-redering이 될까요? [`normal`, `react`, `hook`] 
- props로 받은 값을 useState에 넣었을때 props가 바뀌면 초기값도 바뀔까요? [`normal`, `react`, `hook`] 
- 상태값을 객체에 다 넣기 vs 쪼개서 다른 상태값으로 관리하기 [`normal`, `react`, `hook`] 
- useCallback은 어떤 용도로 사용하나요? [`normal`, `react`, `hook`] 
- ref는 무엇이고 언제 사용하면 좋을까요? [`normal`, `react`, `hook`] 
- useImperativeHandle는 어떤 용도인가요? [`normal`, `react`, `hook`] 
- Strict Mode가 필요한 이유에 대해 설명해 주세요 [`normal`, `react`] 
- render vs mount [`normal`, `react`] 
- Render Props Pattern에 대해 설명해주세요 [`normal`, `react`, `pattern`] 
- Provider Pattern에 대해 설명해주세요 [`normal`, `react`, `pattern`] 
- Compound Pattern에 대해 설명해주세요 [`normal`, `react`, `pattern`] 

## Computer Science

- Process vs Thread [`critical`, `cs`] 
- 웹서버 vs WAS [`high`, `network`] 

## 기타

- 여러분은 왜 프론트 개발자가 되고 싶나요? [`critical`, `why`] 
- 기억에 남는 Error가 있다면 소개해 주세요 [`high`] 
- 프론트엔드에서 테스팅의 효용성에 대해 어떻게 생각하시나요? [`high`] 
- 좋은 코드란 어떤 코드인가요? [`high`] 
- 협업할때 어려운 점이 있었나요? 있었다면 어떻게 극복했나요? [`high`] 
- 새로운 기술을 습득하기 위해 어떤 방식으로 접근하고 계신가요? [`high`] 
