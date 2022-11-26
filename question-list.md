# 태그 리스트
- `browser`, `dom`, `event-loop`, `storage`,
- `js`, `callback`, `promise`, `async`, `prototype`, `execution-context`, `error-handling`, `this`, `scope`, `class`, `event`, `data-type`, `immutable`
- `html`, `defer`, `async`, `ts`
- `react`, `jsx`, `hook`, `context-api`, `ref`, `redux`, `react-query`, `recoil`, `suspense`
- `network`, `secure`
- `performance`, `optimization`, `ssr`
- `pattern`, `paradigm`
- `module`, `bundle`, `webpack`, `babel`, `swc`
- `css`, `scss`, `emotion`, `styled-component`
- `cs`
- `data-structure`, `algorithm`
- `critical`, `high`, `normal`, `low` (중요도)
- `why`, `history`
- `test`, `clean-code`
- `teamplay`, `experience`, `personality`, `study`, `self-introduce`

# 질문 리스트

## JS/TS

### Critical

- prototype의 장점이 무엇이길래 javascript에서 채택했을까요? 그렇다면 prototype은 무엇인가요? [`critical`, `js`, `prototype`, `why`]
    - [4기 동키콩](https://github.com/woowacourse-study/2022-woowahan-bansanghwe/discussions/61)
    - [4기 무비](https://github.com/woowacourse-study/2022-woowahan-bansanghwe/discussions/87)
- 최근 js의 동향에 대해 설명해 주세요 [`critical`, `js`]
- javascript의 문제점으로 무엇이 있고, 왜 그게 문제점일까요? [`critical`, `js`, `why`]
- 왜 typescript가 각광받고, js에선 ts를 표준으로 합치려 할까요? (벌써 Stage 1;;) [`critical`, `ts`, `why`]
- javascript 태동기에 목표는 무엇이고, 지금과 어떤게 달라졌나요? [`critical`, `js`]
- ECMAScript에서 해결하려는 문제는 무엇이고, 앞으로의 과제는 무엇일까요? [`critical`, `js`]
- 브라우저가 동시성 문제를 어떻게 해결했는지 설명해 주세요 [`critical`, `browser`, `event-loop`] 
    - [4기 자스민](https://github.com/woowacourse-study/2022-woowahan-bansanghwe/discussions/64)
- 명령형(Imperative) 프로그래밍 vs 선언형(Declarative) 프로그래밍 [`critical`, `js`, `paradigm`] 
    - [4기 병민](https://github.com/woowacourse-study/2022-woowahan-bansanghwe/discussions/74)
- 최근에 개발중 했던 추상화에 대해 소개해 주세요 [`critical`, `js`] 
- Event Loop에 대해 설명해주세요 [`critical`, `js`, `event-loop`]
    - [4기 병민](https://github.com/woowacourse-study/2022-woowahan-bansanghwe/discussions/90)
- javascript에서 비동기는 어떻게 처리되나요? [`critical`, `js`, `event-loop`]
- 비동기란 무엇인가요? [`critical`, `js`, `async`]
- prototype의 장점은 무엇인가요? [`critical`, `js`, `prototype`]
- 프로토타입과 실행 컨텍스트를 포함해서 자바스크립트의 작동방식에 대해 설명해주세요 [`critical`, `js`, `prototype`, `execution-context`]
- Javascript는 싱글 스레드 언어인데 어떻게 비동기로 동작하나요?

### High

- callback, promise, async/await [`high`, `js`]
    - [4기 앨버](https://github.com/woowacourse-study/2022-woowahan-bansanghwe/discussions/88)
- var vs let vs const [`high`, `js`]
    - [4기 밧드](https://github.com/woowacourse-study/2022-woowahan-bansanghwe/discussions/98)
- javascript에서 변수를 선언하는 방식에 대해 설명해주세요 [`high`, `js`]
- javascript의 data type에 대해 설명해주세요 [`high`, `js`, `data-type`]
- callback vs promise [`high`, `js`, `async`] 
	- [4기 병민](https://github.com/woowacourse-study/2022-woowahan-bansanghwe/discussions/113)
- 실행 컨텍스트에 대해 설명해 주세요 [`high`, `js`, `execution-context`] 
    - [4기 우디](https://github.com/woowacourse-study/2022-woowahan-bansanghwe/discussions/89)
- 실행 컨텍스트가 없는 다른 언어가 있을까요? [`high`, `js`, `execution-context`] 
- 일반 함수와 화살표 함수의 차이점은 무엇일까요? [`high`, `js`, `function`] 
- this에 대해서 설명해 주세요 [`high`, `js`, `this`]
    - [4기 밧드](https://github.com/woowacourse-study/2022-woowahan-bansanghwe/discussions/83)
- this가 결정되는 방식에 대해 설명해 주세요 [`high`, `js`, `this`]
- promise에 비해 async/await가 가지는 장점은 무엇인가요? [`high`, `js`, `async`] 
- 순수 함수란 무엇이고 이 함수가 가지는 장점은 무엇인가요? [`high`, `js`] 
- 스코프 체인이란 무엇인가요? [`high`, `js`]
    - [4기 우디](https://github.com/woowacourse-study/2022-woowahan-bansanghwe/discussions/79)
- 애니메니션을 구현할때 requestAnimationFrame이 setTimeout보다 어떤점에서 더 좋은건가요? [`high`, `browser`, `event-loop`]
- cookies vs localStorage vs session storage [`high`, `js`, `network`]
    - [4기 민초](https://github.com/woowacourse-study/2022-woowahan-bansanghwe/discussions/104)
- 로컬 스토리지, 세션 스토리지 같은 웹 스토리지가 있는데 쿠키를 왜 사용하는걸까?
- indexDB에 대해 설명해 주세요
- accessToken을 어떻게 관리하는것이 안전할까요? [`high`, `js`, `network`]
- 무한 스크롤을 구현할때 intersection observer가 scroll event listener보다 더 좋은 이유를 설명해 주세요 [`high`, `js`, `browser`, `event-loop`]
- commonjs vs es6 module (+모듈의 역사) [`high` `js`, `module`] 
    - [4기 자스민](https://github.com/woowacourse-study/2022-woowahan-bansanghwe/discussions/82)
- 클로저에 대해 설명해 주세요 [`high`, `js`, `closure`]
- 클로저의 단점 대해 설명해 주세요 [`high`, `js`, `closure`]
- 다른 라이브러리에서 클로저를 어떤 식으로 사용할 것 같나요? [`high`, `js`, `closure`]
- 렉시컬 환경(Lexical Environment)에 대해 설명해 주세요 [`high`, `js`] 
    - [4기 병민](https://github.com/woowacourse-study/2022-woowahan-bansanghwe/discussions/73)
- 렉시컬 스코프(Lexical Scope)란 무엇인가요? [`high`, `js`, `scope`]
- javascript가 유동적인 언어인 이유는 무엇인가요? [`high`, `js`] 
- 깊은 복사와 얕은 복사에 대해 설명해 주세요 [`high`, `js`]
    - [4기 밧드](https://github.com/woowacourse-study/2022-woowahan-bansanghwe/discussions/86)
- css 으로 animation을 구현하는것과 js로 animation을 구현하는것의 차이점에 대해 설명해 주세요 [`high`, `js`, `css`] 
- javascript가 객체 지향 언어라고 하는데 그 이유가 무엇일지 이야기 해주세요 [`high`, `js`, `pattern`] 
- primitive data인데 어떻게 내장 함수를 사용할 수 있는걸까요? (`"Hello".toLowerCase()`); [`high`, `js`] 
- type vs interface  [`high`, `ts`]
- MVC pattern에 대해 설명해 주세요  [`high`, `js`, `pattern`]
- Flux pattern에 대해 설명해 주세요  [`high`, `js`, `pattern`]
- javascript에서 함수란? [`high`, `js`]
    - [4기 자스밍](https://github.com/woowacourse-study/2022-woowahan-bansanghwe/discussions)
- 구조적 서브 타이핑이란?  [`high`, `ts`]
    - [4기 앨버](https://github.com/woowacourse-study/2022-woowahan-bansanghwe/discussions/114)
- 클래스에서 함수를 맴버 변수로 두었을 때랑 메서드로 두었을 때 어떤 차이가 있을까요? [`high`, `js`, `class`]
- 왜 클래스를 사용하셨나요? [`high`, `js`, `class`]
- 클래스의 단점은 무엇일까요? [`high`, `js`, `class`]
- 클래스 상속의 단점은 무엇일까요? [`high`, `js`, `class`]
- fetch vs xmlhttpsrequest [`high`, `js`, `async`]
- DOM이란 무엇인가요? [`high`, `js`, `dom`]
- DOM의 구성 요소는 무엇이 있을까요? [`high`, `js`, `dom`]
- javascript에서 에러 핸들링을 어떻게 하나요? [`high`, `js`, `error-handling`]
- 프로토타입 체인 탐색에서는 링크를 타고 넘어가는 비용이 발생하는데 이 단점에 대해서 생각해 보셨나요? [`high`, `js`, `prototype`]
- 프로토타입을 왜 클래스로 안 만들고 객체로 만들었을까요? [`high`, `js`, `prototype`]
- 호이스팅이란 무엇인가요? [`high`, `js`, `hoisting`]
- 호이스팅이 되는 이유는 무엇인가요? [`high`, `js`, `hoisting`]
- 실행컨텍스트 지식을 아는게, 실무에서 어떻게 도움이 될까요? [`high`, `js`, `execution-context`, `experience`]
- 자바스크립트의 불변성에 대해 설명해주세요 [`high`, `js`, `immutable`]
- 불변성을 지켰을때 얻는 효과가 무엇인가요? [`high`, `js`, `immutable`]
- 불변적인 데이터와 가변적인 데이터를 언제 사용하나요? [`high`, `js`, `immutable`]
- javascript의 장점과 단점은 뭐라고 생각하나요?
- 자바스크립트에서 은닉화를 어떻게 하나요?
- 타입스크립트에서 건전성에 대해 설명해주세요
- 덕타이핑에 대해 소개해 주세요
- 구조적 타이핑에 대해 소개해 주세요
- 구조적 타이핑과 비교할 수 있는 다른 타이핑 방식에 대해 소개해주세요
- 구조적타이핑과 구조적이지 않은 타이핑의 차이점은 뭘까요?
- 구조적 타이핑의 장점은 뭘까요?
- 타입스크립트 infer에 대해 설명해주세요
- 타입스크립트를 모르는 사람에게 타입스크립트를 설명해주세요
- 타입스크립트가 런타임에서 더 안전한 환경을 만들어준다했는데, 타입스크립트가 어떻게 이렇게 해주나요?
- 타입가드 말고 런타임에서 타입 에러를 방지할 수 있는 방법은 없나요?
- generic에 대해 설명해주세요
- generic을 사용해야할 때와 사용하지 않아도 될 때는 언제인지
- generic대신 유니온을 사용하면 되지 않나요?
- 함수 오버로딩과 오버라이딩의 차이점에 대해 설명해주세요
- 인터페이스에서 똑같은 이름으로 타입 선언하면 어떻게 되나요?
- 컴파일 타임에 타입 체크를 어떻게 하는지 어떤 방식으로 하는지. 그 용어를 뭐라고 하는지 정확하게 말해주세요
- 타입 단언을 설명해주세요. 그리고 타입 단언의 단점 에 대해 설명해주세요
- 타입 단언 사용해본 예시 알려주세요
- 타입스크립트 관련 기억에 남는 경험에 대해 소개해주세요
- 타입스크립트의 문제점에 대해 설명해주세요
- 프로토타입으로 메모리를 아낄 수 있다면 다른 언어에서는 왜 이렇게 하지 않았을까요? [`critical`, `js`, `prototype`]
- setTimeout에 2분이라는 시간을 지정했다고 했는데 그것이 꼭 보장 되는 시간인 건지?
- CommonJS vs ESModule vs UMD vs AMD
- TreeShaking에 대해 설명해 주세요

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
- WeakMap vs Map
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
- blocking vs non-blocking vs sync vs async [`high`, `js`, `async`]
- ECMA 스크립트에서 객체 변경도를 낮출 수 있는 방법들이 제안된걸로 아는데 뭐가 있을까요?
- 직접 API 캐시를 구현했는데, 캐시되지 않은 요청이 동시에 중복으로 발생하는 것을 방지하려면 어떻게 해야 할까요?
- 자바스크립트를 공부하기 시작할 때 무엇을 이해하는 게 중요하다고 생각하나요?
- fetch api를 사용해 axios interceptor를 구현하려면 어떻게 해야 할까요?
- Promise를 직접 구현하려면 어떻게 해야 할까요?

## Optimization

### Critical

- Critical Rendering Path 대해 설명해 주세요 [`critical`, `browser`] 
    - [4기 병민](https://github.com/woowacourse-study/2022-woowahan-bansanghwe/discussions/60)
- rendering을 차단하는 리소스는 어떤것들이 있나요? [`critical`, `browser`] 
    - [4기 앨버](https://github.com/woowacourse-study/2022-woowahan-bansanghwe/discussions/65)
- 프로젝트에서 성능 어떻게 개선했는지 설명해주세요
- 웹 성능 어떻게 진단했나요?

### High

- preload vs preconnect vs prefetch [`high`, `browser`] 
- page load event에 대해 설명해 주세요 [`high`, `browser`] 
- defer vs async [`high`, `browser`, `html`] 
- async의 단점에 대해 설명해 주세요 [`high`, `browser`, `html`] 
- defer 단점에 대해 설명해 주세요 [`high`, `browser`, `html`] 
- Webpack의 Code Spliting에 대해 설명해 주세요 [`high`, `bundle`, `webpack`, `module`] 
    - [4기 민초](https://github.com/woowacourse-study/2022-woowahan-bansanghwe/discussions/72)
- Incremental Rendering과 SSR(server side rendering)에 대해 설명해 주세요 [`high`, `ssr`] 
- SSR(server side rendering)의 장점은 무엇인가요? [`high`, `ssr`] 
- CSR과 SSR의 차이점에 대해 설명해 주세요 [`high`, `ssr`] 
- 왜 CSS <link>를 <head>에 놓는것이 좋은지 설명해 주세요 [`high`, `browser`, `html`] 
- 왜 javascript는 기본적으로 parsing을 차단하는 방식으로 동작할까요?
- reflow와 쌓임맥락을 엮어서 설명해주세요
- 폰트 깜빡임 어떻게 줄일 수 있을까요
- 폰트 로드하는 방식에 대해 소개해주세요
- 서비스를 만들었다. 어떤 페이지의 속도가 느리다는 피드백이 왔다. 이럴 때 프론트엔드 개발자로서 고려해볼만한 점은 무엇인가?
- TTI는 어떤 기준으로 측정되나요?
- TTFB란 무엇인가요?
- FCP vs LCP

### Normal
- reflow, repaint에 대해 설명해주세요
- reflow를 발생시키는 style property는 대표적으로 어떤것들이 있을까요? [`normal`, `browser`] 
- repaint를 발생시키는 style property는 대표적으로 어떤것들이 있을까요? [`normal`, `browser`] 
- 번들 사이즈를 줄이려면 어떻게 해야 할까요? [`normal`, `bundle`, `webpack`] 
- tree shaking에 대해 설명해 주세요 [`normal`, `bundle`, `webpack`, `module`] 
    - [4기 무비](https://github.com/woowacourse-study/2022-woowahan-bansanghwe/discussions/75)
- Static/Dynmic Import에 대해 설명해 주세요 [`normal`, `js`, `module`] 
- reflow를 막는 방법은 뭐가 있을까요?

## Network

### Critical

- 주소창에 www.naver.com을 치고 나서 발생하는 일들에 대해 설명해 주세요 [`critical`, `network`, `browser`] 
    - [4기 우디](https://github.com/woowacourse-study/2022-woowahan-bansanghwe/discussions/63)
- RESTfull API에 대해 설명해 주세요 [`critical`, `network`, `paradigm`] 
- Get vs Post vs Put vs Patch vs Delete [`critical`, `network`] 
- CORS에 대해 설명해 주세요 [`critical`, `network`] 
    - [4기 병민](https://github.com/woowacourse-study/2022-woowahan-bansanghwe/discussions/18)
    - [4기 앨버](https://github.com/woowacourse-study/2022-woowahan-bansanghwe/discussions/71)
- CORS를 우회하는 방법에 대해 설명해 주세요
- CORS가 없어지면 무슨 문제가 발생할까요?
- preflight없는 요청도 있나요?
- HTTP 캐싱에 대해 설명해 주세요 [`critical`, `network`, `cache`]
    - [4기 밧드](https://github.com/woowacourse-study/2022-woowahan-bansanghwe/discussions/67)
- no-cache vs no-store
- cache-control안에 무엇이 들어갈 수 있을까요?
- max-age vs s-maxage


### High

- OSI 7계층에 대해 설명해 주세요 [`high`, `network`] 
- TCP/IP에 대해 설명해 주세요 [`high`, `network`] 
    - [4기 민초](https://github.com/woowacourse-study/2022-woowahan-bansanghwe/discussions/66)
- TCP/IP vs UDP [`high`, `network`] 
- http/1.1 vs http/2 [`high`, `network`] 
- DNS에 대해 설명해 주세요 [`high`, `network`] 
- URL vs URI [`high`, `network`] 
- CDN(Content Delivery Network)에 대해 설명해 주세요 [`high`, `network`] 
    - [4기 동키콩](https://github.com/woowacourse-study/2022-woowahan-bansanghwe/discussions/84)
- 웹 소켓에 대해 설명해 주세요 [`high`, `network`] 
- http header의 cache-control에 대해 설명해 주세요 [`high`, `network`, `browser`] 
    - [4기 동키콩](https://github.com/woowacourse-study/2022-woowahan-bansanghwe/discussions/77)
- 사이트를 배포 했는데 사용자 브라우저에 캐쉬가 남아있는 경우 어떻게 해야 할까요? [`high`, `network`, `browser`] 
- http vs https [`high`, `network`, `secure`] 
- XSS(Cross-site scripting)에 대해 설명해 주세요 [`high`, `network`, `secure`] 
- CSRF(Cross-Site Request Fogery)에 대해 설명해 주세요 [`high`, `network`, `secure`] 
- CSRF를 어떻게 방지할 수 있을까요?

### Normal

- GSLB(Global Server Load Balancing)에 대해 설명해 주세요 [`normal`, `network`] 

## React

### Critical

- react가 해결하려는 문제는 무엇인가요? [`critical`, `react`] 
- 컴포넌트란 무엇인가요? [`critical`, `react`]
	- [4기 우디](https://github.com/woowacourse-study/2022-woowahan-bansanghwe/discussions/116)
- ContextAPI의 문제점은 무엇인가요? [`critical`, `react`, `hook`, `context`] 
- 웹 개발의 시대가 jQuery에서 React나 Vue로 넘어온 이유가 무엇일까요? [`critical`, `react`] 
- React와 Vue는 서로가 어떤게 다르길래, 사용 대상이 나뉘는 걸까요? [`critical`, `react`] 
- 리액트의 재조정(reconciliation)과정에 대해 설명해 주세요 [`critical`, `react`] 
- 리액트란?
	- [4기 자스민](https://github.com/woowacourse-study/2022-woowahan-bansanghwe/discussions/117)
- 컴포넌트 분리 기준에 대해 설명해 주세요
- hook 분리 기준에 대해 설명해 주세요

### High

- SPA의 장점에 대해 설명해주세요 [`high`, `react`] 
- Render Phase와 Commit Phase에 대해서 설명해 주세요 [`high`, `react`] 
    - [4기 민초](https://github.com/woowacourse-study/2022-woowahan-bansanghwe/discussions)
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
	- [4기 밧드](https://github.com/woowacourse-study/2022-woowahan-bansanghwe/discussions/115)
- JSX에서 if-else를 왜 사용할 수 없나요? [`high`, `react`, `jsx`] 
- Class Component에 비해 Hook + Functional Component가 가지는 이점은? [`high`, `react`] 
- useState는 어떻게 이전 상태를 기억하나요? [`high`, `react`, `hook`] 
- 왜 조건문 안에 hook을 쓰면 안될까요? [`high`, `react`, `hook`] 
- 배열을 map돌려서 list를 그릴때 key가 왜 필요한가요? [`high`, `react`, `performance`] 
- index를 key로 쓰면 안되는 이유에 대해 설명해 주세요 [`high`, `react`, `performance`] 
- Controlled Component vs Uncontrolled Component [`high`, `react`] 
- Hook은 Presentational/Container pattern을 대체할 수 있나요? [`high`, `react`, `pattern`] 
- Container/Presentational Component가 해결하려고 하는 문제는 무엇인가요?
- VirtualDOM이 필요한 이유에 대해 설명해 주세요 [`high`, `react`] 
    - [4기 무비](https://github.com/woowacourse-study/2022-woowahan-bansanghwe/discussions/68)
- VirtualDOM이 효율적이라는데 왜 그런걸까요?
- sevelt는 virtualDOM을 안쓰는데 왜 빠를까요?
- 최근에 real-dom에 직접 접근하는 라이브러리들이 많이 나오고 있는데 virtual dom의 단점은 무엇일까요?
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
- React의 Single Source Of Truth에 대해 설명해 주세요 [`high`, `react`] 
- SSR vs CSR vs SSG
- CSR에서 발생 가능한 병목 현상은 무엇인가요?
- CRA를 사용하지 않고 웹팩 기반으로 구현한 이유가 있나요?
- 웹팩은 무엇이고 왜 사용해야 하나요?
- 웹팩에서 할 수 있는 최적화에 대해 설명해 주세요
- 상태 변화를 어떻게 감지하나요?
- 리액트에서 말하는 렌더링이란 무엇인가요?
- React는 memoize한 것에 대한 메모리 관리를 어떻게 할까요?
- ReactNode를 re-mount시키는 방법에 대해 소개해 주세요
- 리액트에서 state변경에 따라 리렌더링을 하는데, 리렌더링을 리액트는 어떻게 판단하나요?(구체적으로 객체나, 컴포넌트 등이 변경됐다는 것을 어떻게 알까요)
- useRef의 내부 동작원리에 대해 설명해주세요
- 리액트에서 이벤트는 어떻게 처리되나요? (이벤트 위임)
- recoil은 어떤 장점이 있나요?
- jotai와 recoil은 어떤 차이가 있나요?
- Context API는 상태 관리 툴인가요?
- 프로젝트 코드를 봤는데 상태 관리 라이브러리를 사용하지 않고 Context API를 많이 썼다. 왜 그랬나?
- Context API를 쓸 때 주의할 점은 무엇인가?
- 다른 상태 관리 라이브러리 사용해본 경험은 있나요?
- api통신을 컴포넌트에서 하지 않고 페이지에서 하게 된 이유는 무엇인가요?
- 페이지에서 api통신하면 어떤 단점이 있는가?
- React에서 컴포넌트를 만드는 방법에 대해 설명해주세요
- class 컴포넌트 vs function 컴포넌트
- Suspense가 waterfall을 만든다고 했는데, suspense를 어떻게 구현해서 그런 현상이 발생했는가?
- react-query의 invalidateQuries 대해 소개해 주세요
- 왜 react-query의 useMutation은 key로 관리하지 않을까요?
- 왜 react-query를 도입했나요?
- react-query와 redux를 함께 쓰는 것이 적합하다고 생각하나요?
- 가장 자신있는 hook에 대해 소개해 주세요
- useMemo, useCallback을 항상 사용하면 좋은 건가요?
- 왜 emotion 을 선택하셨나요?
- emotion의 단점은 무엇인가요?
- css-in-js의 단점은 무엇인가요?
- 리액트에서 "불변성"을 지키는 것이 왜 중요한가요?
- 리액트에서 state는 Immutable합니다. 리액트에서 왜 Immutable한 개념을 사용하는 것인지, 그리고 Immutable을 채택하지 않은 다른 프레임워크가 있는지, 그리고 Immutable을 적용하지 않았을 때 생길 수 있는 문제점은 무엇인지 설명해주세요.
- 리액트의 불변성이 사라지면 어떻게 되나요?
- 리액트의 불변성을 지킬려면 어떻게 해야할까요?
- 에러 처리 구조를 어떻게 개선하셨나요?
- 전역적인 에러는 어떻게 처리하셨나요?
- class 컴포넌트를 리스트로 돌릴 때는 어떻게 되나요?
- vue, angular 대신 리액트 사용한 이유가 있나요?
- vue에서도 virtual dom 사용하고 있는데, 리액트만의 장점은 없나요?
- 10,000개의 리스트를 렌더링할때 최적화 하려면 어떻게 해야 할까요?
- date picker 를 만든다고 하면, 어떤 식으로 만들 것인가?
- CDD(Component Driven Development)의 단점은?
- ReactElement vs Component

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
- diffing 알고리즘이 어떻게 동작하나요?

## Computer Science

- Process vs Thread [`critical`, `cs`] 
- 웹서버 vs WAS [`high`, `network`] 

## Styling
- CSS의 쌓임 맥락에 대해 설명해 주세요
- 스타일의 연산자 우선순위에 대해서 설명해줘라
- css-in-css vs css-in-js

## Security / Auth
- jwt를 사용한 이유에 대해 설명해 주세요
- OAuth는 어떻게 작동하나요?
- OAuth1.0 vs OAuth2.0

## 기타

- 여러분은 왜 프론트 개발자가 되고 싶나요? [`critical`, `why`] 
- 기억에 남는 Error가 있다면 소개해 주세요 [`high`, `experience`] 
- 프론트엔드에서 테스팅의 효용성에 대해 어떻게 생각하시나요? [`high`, `test`] 
- 좋은 코드란 어떤 코드인가요? [`high`, `clean-code`] 
- 협업할때 어려운 점이 있었나요? 있었다면 어떻게 극복했나요? [`high`, `teamplay`, `experience`] 
- 새로운 기술을 습득하기 위해 어떤 방식으로 접근하고 계신가요? [`high`, `study`] 
- 개발경험을 통해 자기소개 해주세요 [`critical`, `experience`, `self-introduce`]
- 프로젝트 경험과 함께 자신을 소개해주세요 [`critical`, `experience`, `self-introduce`]
- 팀내 문제 발생시 대처 방법 [`critical`, `teamplay`]
- 팀에 불화가 있는 팀원이 있는데, 말을 못하는 상황이라면 어떻게 해결하실 건가요? [`critical`, `teamplay`]
- 코드 컨벤션을 지키지 않는 팀원이 있다. 해당 팀원은 개발을 엄청 잘한다. 어떻게 대처할 것이냐? [`critical`, `teamplay`]
- 팀원과 의견안맞을때 어떻게 해결하나요? [`critical`, `teamplay`]
- 상사에게 의견을 물어서 어떠한 문제를 해결한 경험이 있나요? [`critical`]
- 교육 기간동안 어떤 방식으로 성장을 이루었나요? [`critical`, `study`]
- 교육 기간동안 기술적으로 어떤 역량이 많이 성장했나요? [`critical`]
- 본인의 장/단점에 대해 소개해주세요 [`critical`]
- 프론트엔드 개발자로 면접자분의 장점은 무엇인가요?
- 백엔드가 5명이고 프론트가 2명인데, 반대로 프론트가 5명이고 백엔드가 2명이면 어떻게 일하시겠어요?
- 교육 프로그램에 참여한 이유는?
- 가장 자신있는 JS에 대해 소개해 주세요
- java와 node가 request를 어떻게 처리하는지 비교해주세요
- 가장 최근에 읽은 기술서적은 무엇인가요?
- 응집도, 결합도 어떤 것을 높이고 낮춰야할까요?
- 요즘 기술적으로 고민하는 부분은?
- 최신 기술은 어떤 방식으로 습득하나요?
- 프론트엔드 개발자로서 가장 부족한 부분은?
- 에러 처리 관련해서 기억에 남는 경험을 소개해 주세요
- 함수형 프로그래밍과 선언적 프로그래밍의 차이에 대해 말씀해주세요
- 만약에 보여줄 것이 정말 많아진다면 무한 스크롤 어떻게 구현하실건가요
- 우리앱을 사용해보면서 불편했고, 개선하고 싶은 부분은 어디가 있었나?
- 아토믹 디자인 패턴으로 '상품 리스트' 페이지를 어떻게 작성할지 말씀해주세요
- ul와 ol은 어떤 의미이며 기능적으로 어떻게 다른지?
- 효율적인 개발을 위한 규칙에 대해 소개해주세요
- 소프트웨어 공학의 원칙 중 잘 설명할 수 있는 것을 설명해주어라
- 왜 캡슐화가 필요한가요?
- HTML, CSS, JS등의 굉장히 많은 파일을 작성하는데 코드를 작성할 때 본인만의 규칙이 있는가? 중요시 여기는 부분이 있나요?
- 마지막으로 최근에 감명깊게 본 코드가 있다면 설명해줘라
- 가장 자신있는 디자인 패턴에 대해 소개해주세요
- 개발을 앞으로 하다보면 어려운 개념을 생기는데, 이것을 어떤 방식으로 접근하는지?
- 노드 에서 비동기처리는 어떻게 동작하나요?
- 브라우저의 비동기 처리와 노드의 비동기 처리가 다른 이유는 무엇일까요?
- 웹소켓 사용했는데 WS, WSS 차이에 대해 설명해주세요
- 코드리뷰 경험 얘기가 나와서 그런데, 가장 인상깊었던 코드리뷰는?
- 크로스브라우징 해결 경험 공유해주세요.
- 자료구조에서 ‘스택’ 이 있는데, 이 스택을 실제 프로덕션에서 사용한다고 했을 때, 어떤 기능을 구현 할 때 사용할 수 있을까요?
- 면접 준비하면서 공부했던 것중에, 이거 말하면 나 진짜 붙는다 하는거 자유롭게 말해주세요.
- 브라우저에 720px의 height가 보이지만 실제로는 12만px이고 노드가 2400만개가 있다고 가정해봅시다. 이 때 보이지 않는 부분들은 브라우저가 알아서 최적화를 해줍니다. 이 과정이 어떤 것인지 설명해주세요.
