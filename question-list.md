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
- `上`, `中`, `下` (중요도)
- `why`, `history`

# 질문 리스트

## JS/TS

### 上

- [`上`, `js`, `prototype`, `why`] prototype의 장점이 무엇이길래 javascript에서 채택했을까요? 그렇다면 prototype은 무엇인가요?
- [`上`, `js`] 최근 js의 동향에 대해 설명해 주세요
- [`上`, `js`, `why`] javascript의 문제점으로 무엇이 있고, 왜 그게 문제점일까요?
- [`上`, `ts`, `why`] 왜 typescript가 각광받고, js에선 ts를 표준으로 합치려 할까요? (벌써 Stage 1;;)
- [`上`, `js`] javascript 태동기에 목표는 무엇이고, 지금과 어떤게 달라졌나요?
- [`上`, `js`] ECMAScript에서 해결하려는 문제는 무엇이고, 앞으로의 과제는 무엇일까요?
- [`上`, `browser`, `event-loop`] 브라우저가 동시성 문제를 어떻게 해결했는지 설명해 주세요
- [`上`, `js`, `paradigm`] 명령형(Imperative) 프로그래밍 vs 선언형(Declarative) 프로그래밍
- [`上`, `js`] 최근에 개발중 했던 추상화에 대해 소개해 주세요

### 中

- [`中`, `js`] var vs let vs const
- [`中`, `js`, `async`] callback vs promise
- [`中`, `js`, `execution-context`] 실행 컨텍스트에 대해 설명해 주세요
- [`中`, `js`, `execution-context`] 실행 컨텍스트가 없는 다른 언어가 있을까요?
- [`中`, `js`] 일반 함수와 화살표 함수의 차이점은 무엇일까요?
- [`中`, `js`] this에 대해서 설명해 주세요
- [`中`, `js`, `async`] promise에 비해 async/await가 가지는 장점은 무엇인가요?
- [`中`, `js`] 순수 함수란 무엇이고 이 함수가 가지는 장점은 무엇인가요?
- [`中`, `js`] 스코프 체인이란 무엇인가요?
- [`中`, `browser`, `event-loop`] 애니메니션을 구현할때 requestAnimationFrame이 setTimeout보다 어떤점에서 더 좋은건가요?
- [`中`, `js`, `network`] cookies vs localStorage vs session storage
- [`中`, `js`, `network`] accessToken을 어떻게 관리하는것이 안전할까요?
- [`中`, `js`, `browser`, `event-loop`] 무한 스크롤을 구현할때 intersection observer가 scroll event listener보다 더 좋은 이유를 설명해 주세요
- [`中` `js`, `module`] commonjs vs es6 module
- [`中`, `js`] 클로저에 대해 설명해 주세요
- [`中`, `js`] 렉시컬 환경(Lexical Environment)에 대해 설명해 주세요
- [`中`, `js`] javascript가 유동적인 언어인 이유는 무엇인가요?
- [`中`, `js`] 깊은 복사와 얕은 복사에 대해 설명해 주세요
- [`中`, `js`, `css`] css 으로 animation을 구현하는것과 js로 animation을 구현하는것의 차이점에 대해 설명해 주세요
- [`中`, `js`, `pattern`] javascript가 객체 지향 언어라고 하는데 그 이유가 무엇일지 이야기 해주세요
- [`中`, `js`] primitive data인데 어떻게 내장 함수를 사용할 수 있는걸까요? (`"Hello".toLowerCase()`);
- [`中`, `ts`] type vs interface
- [`中`, `js`, `pattern`] MVC pattern에 대해 설명해 주세요
- [`中`, `js`, `pattern`] Flux pattern에 대해 설명해 주세요

### 下

- [`下`, `js`, `scope`] 함수레벨 스코프 vs 블록레벨 스코프
- [`下`, `js`] generator에 대해 설명해 주세요
- [`下`, `js`] iterable에 대해 설명해 주세요
- [`下`, `js`] call vs apply vs bind
- [`下`, `js`] 생성자 함수와 일반 함수의 차이점은 무엇인가요?
- [`下`, `js`] mutable vs immutable
- [`下`, `js`, `pattern`] event delegation에 대해 설명해 주세요
- [`下`, `js`] undefined vs null
- [`下`, `js`, `why`] symbol은 왜 나왔고 언제 사용하면 좋을지 설명해 주세요
- [`下`, `js`] falsy한 타입과 truthy한 타입에 대해 설명해 주세요
- [`下`, `js`] hasOwnProperty의 위험성에 대해 설명해 주세요
- [`下`, `js`] primitive type vs object
- [`下`, `js`] 일급 함수란 무엇인가요?
- [`下`, `js`] 객체 변경을 방지하는 방법에는 어떤것들이 있을까요?
- [`下`, `js`] 객체 리터럴로 만든 객체와 생성자 함수로 만든 객체는 어떤 차이점이 있나요?
- [`下`, `js`] strict mode로 했을때 어떤 장점이 있나요?
- [`下`, `js`] 객체 vs Set vs Map
- [`下`, `js`, `DOM`] HTMLCollection vs NodeList
- [`下`, `js`, `DOM`] innerHTML vs insertAdjacentHTML
- [`下`, `js`, `DOM`] HTML 어트리뷰트 vs. DOM 프로퍼티
- [`下`, `js`, `event`] Event Handler내의 this는 어떤 값을 가지고 있나요?
- [`下`, `js`, `timer`] setInterval vs recursive setTimeout
- [`下`, `browser`, `event-loop`] macro task queue 사용 사례에 대해 설명해 주세요
- [`下`, `browser`, `event-loop`] micro task queue 사용 사례에 대해 설명해 주세요
- [`下`, `js`, `event`] bubbling vs capturing
- [`下`, `js`, `event`] bubbling 특성을 활용한 예제를 소개해 주세요
- [`下`, `js`, `event`] capturing 특성을 활용한 예제를 소개해 주세요
- [`下`, `js`] Element vs Node
- [`下`, `js`, `event`] `element.onclick(doSomthing)` vs `element.addEventListener(doSomething)`
- [`下`, `js`, `performance`, `timer`] debounce vs throttle
- [`下`, `js`, `browser`] history api
- [`下`, `js`, `pattern`] Singleton Pattern에 대해 설명해주세요
- [`下`, `js`, `pattern`] Proxy Pattern에 대해 설명해주세요
- [`下`, `js`, `pattern`] Observer Pattern에 대해 설명해주세요
- [`下`, `js`, `pattern`] Factory Pattern에 대해 설명해주세요
- [`下`, `js`, `pattern`] Prototype Pattern에 대해 설명해주세요

## Optimization

### 上

- [`上`, `browser`] Critical Rendering Path 대해 설명해 주세요
- [`上`, `browser`] rendering을 차단하는 리소스는 어떤것들이 있나요?

### 中

- [`中`, `browser`] preload vs preconnect vs prefetch
- [`中`, `browser`] page load event에 대해 설명해 주세요
- [`中`, `browser`, `html`] defer vs async
- [`中`, `browser`, `html`] async의 단점에 대해 설명해 주세요
- [`中`, `browser`, `html`] defer 단점에 대해 설명해 주세요
- [`中`, `bundle`, `webpack`, `module`] Webpack의 Code Spliting에 대해 설명해 주세요
- [`中`, `ssr`] Incremental Rendering과 SSR(server side rendering)에 대해 설명해 주세요
- [`中`, `ssr`] SSR(server side rendering)의 장점은 무엇인가요?
- [`中`, `ssr`] CSR과 SSR의 차이점에 대해 설명해 주세요
- [`中`, `browser`, `html`] 왜 CSS <link>를 <head>에 놓는것이 좋은지 설명해 주세요

### 下
- [`下`, `browser`] reflow를 발생시키는 style property는 대표적으로 어떤것들이 있을까요?
- [`下`, `browser`] repaint를 발생시키는 style property는 대표적으로 어떤것들이 있을까요?
- [`下`, `bundle`, `webpack`] 번들 사이즈를 줄이려면 어떻게 해야 할까요?
- [`下`, `bundle`, `webpack`, `module`] tree shaking에 대해 설명해 주세요
- [`下`, `js`, `module`] Static/Dynmic Import에 대해 설명해 주세요

## Network

### 上

- [`上`, `network`, `browser`] 주소창에 www.naver.com을 치고 나서 발생하는 일들에 대해 설명해 주세요
- [`上`, `network`, `paradigm`] RESTfull API에 대해 설명해 주세요
- [`上`, `network`] Get vs Post vs Put vs Patch vs Delete
- [`上`, `network`] CORS에 대해 설명해 주세요

### 中

- [`中`, `network`] OSI 7계층에 대해 설명해 주세요
- [`中`, `network`] TCP/IP에 대해 설명해 주세요
- [`中`, `network`] TCP/IP vs UDP
- [`中`, `network`] http/1.1 vs http/2
- [`中`, `network`] DNS에 대해 설명해 주세요
- [`中`, `network`] URL vs URI
- [`中`, `network`] CDN(Content Delivery Network)에 대해 설명해 주세요
- [`中`, `network`] 웹 소켓에 대해 설명해 주세요
- [`中`, `network`, `browser`] http header의 cache-control에 대해 설명해 주세요
- [`中`, `network`, `browser`] 사이트를 배포 했는데 사용자 브라우저에 캐쉬가 남아있는 경우 어떻게 해야 할까요?
- [`中`, `network`, `secure`] http vs https
- [`中`, `network`, `secure`] XSS에 대해 설명해 주세요


### 下

- [`下`, `network`] GSLB(Global Server Load Balancing)에 대해 설명해 주세요

## React

### 上

- [`上`, `react`] react가 해결하려는 문제는 무엇인가요?
- [`上`, `react`] 컴포넌트란 무엇인가요?
- [`上`, `react`, `hook`, `context`] ContextAPI의 문제점은 무엇인가요?
- [`上`, `react`] 웹 개발의 시대가 jQuery에서 React나 Vue로 넘어온 이유가 무엇일까요?
- [`上`, `react`] React와 Vue는 서로가 어떤게 다르길래, 사용 대상이 나뉘는 걸까요?
- [`上`, `react`] 리액트의 재조정(reconciliation)과정에 대해 설명해 주세요

### 中
- [`中`, `react`] SPA의 장점에 대해 설명해주세요
- [`中`, `react`] Render Phase와 Commit Phase에 대해서 설명해 주세요
- [`中`, `react`] Hooks의 장점은 무엇인가요?
- [`中`, `react`] Class Component vs Function Component
- [`中`, `react`] CSS in CSS(css, sass, css-module) vs CSS in JS(emotion, styled-component)
- [`中`, `react`] state vs props
- [`中`, `react`, `hook`] useEffect의 dependency를 설정해 주지 않으면 어떤 문제가 발생하나요? (staled state)
- [`中`, `react`, `hook`] useCallback vs useMemo vs React.memo
- [`中`, `react`, `hook`] React팀에서 모든 컴포넌트에 React.memo를 기본으로 적용해놓지 않은 이유가 무엇이라 생각하시나요?
- [`中`, `react`, `hook`, `context`] ContextAPI는 언제 사용하면 좋을까요?
- [`中`, `react`, `hook`] useEffect vs useLayoutEffect
- [`中`, `react`, `hook`] useTransition은 어떤 문제를 해결하기 위해 나온 훅인가요?
- [`中`, `react`, `context`] Prop drilling을 해결하기 위한 방법에 대해 설명해 주세요
- [`中`, `react`, `jsx`] JSX에서 if-else를 왜 사용할 수 없나요?
- [`中`, `react`] Class Component에 비해 Hook + Functional Component가 가지는 이점은?
- [`中`, `react`, `hook`] useState는 어떻게 이전 상태를 기억하나요?
- [`中`, `react`, `hook`] 왜 조건문 안에 hook을 쓰면 안될까요?
- [`中`, `react`, `performance`] 배열을 map돌려서 list를 그릴때 key가 왜 필요한가요?
- [`中`, `react`, `performance`] index를 key로 쓰면 안되는 이유에 대해 설명해 주세요
- [`中`, `react`] Controlled Component vs Uncontrolled Component
- [`中`, `react`, `pattern`] Hook은 Presentational/Container pattern을 대체할 수 있나요?
- [`中`, `react`] VirtualDOM이 필요한 이유에 대해 설명해 주세요
- [`中`, `react`] React18에 본격적으로 적용된 concurrent mode에 대해 설명해 주세요
- [`中`, `react`] Fiber에 대해 설명해 주세요
- [`中`, `react`] 컴포넌트 분리 기준에 대해 설명해 주세요
- [`中`, `react`] 직접 만들어본 Custom Hook에 대해 소개해 주세요
- [`中`, `react`, `pattern`] Container/Presentation Pattern에 대해 설명해주세요
- [`中`, `react`, `pattern`] Higher-Order Component Pattern에 대해 설명해주세요
- [`中`, `react`, `pattern`] Hooks Pattern에 대해 설명해주세요
- [`中`, `react`, `redux`] redux가 context api에 비해 가지는 장점에 대해 설명해 주세요
- [`中`, `react`, `why`] react-query를 왜 쓰셨나요?
- [`中`, `react`], `why`, `react-query`] react-query의 stale time과 cache time의 차이에 대해 설명해 주세요
- [`中`, `react`] Class Component의 life cycle과 Hook + Function Component의 life cycle의 차이점에 대해 설명해 주세요
- [`中`, `react`, `pattern`] Suspense와 Error Boundary를 사용했을때의 장점에 대해 설명해 주세요

### 下

- [`下`, `react`, `hook`] 같은 값으로 setState해도 re-redering이 될까요?
- [`下`, `react`, `hook`] props로 받은 값을 useState에 넣었을때 props가 바뀌면 초기값도 바뀔까요?
- [`下`, `react`, `hook`] 상태값을 객체에 다 넣기 vs 쪼개서 다른 상태값으로 관리하기
- [`下`, `react`, `hook`] useCallback은 어떤 용도로 사용하나요?
- [`下`, `react`, `hook`] ref는 무엇이고 언제 사용하면 좋을까요?
- [`下`, `react`, `hook`] useImperativeHandle는 어떤 용도인가요?
- [`下`, `react`] Strict Mode가 필요한 이유에 대해 설명해 주세요
- [`下`, `react`] render vs mount
- [`下`, `react`, `pattern`] Render Props Pattern에 대해 설명해주세요
- [`下`, `react`, `pattern`] Provider Pattern에 대해 설명해주세요
- [`下`, `react`, `pattern`] Compound Pattern에 대해 설명해주세요

## Computer Science

- [`上`, `cs`] Process vs Thread
- [`中`, `network`] 웹서버 vs WAS

## 기타
- [`上`, `why`] 여러분은 왜 프론트 개발자가 되고 싶나요?
- [`中`] 기억에 남는 Error가 있다면 소개해 주세요
- [`中`] 프론트엔드에서 테스팅의 효용성에 대해 어떻게 생각하시나요?
- [`中`] 좋은 코드란 어떤 코드인가요?
- [`中`] 협업할때 어려운 점이 있었나요? 있었다면 어떻게 극복했나요?
- [`中`] 새로운 기술을 습득하기 위해 어떤 방식으로 접근하고 계신가요?
