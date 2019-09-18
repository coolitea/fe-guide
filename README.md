# 프론트엔드 개발 가이드

## 개발도구

- [x] [Visual Studio Code](https://code.visualstudio.com/)
- [x] [크롬](https://www.google.com/intl/ko/chrome/)
- 크롬 확장 프로그램
  - [x] [Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools/?hl=ko)
  - [x] [React Developer Tools](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi?hl=ko)
  - [x] [Redux DevTools Extension](http://extension.remotedev.io/)

## 설계

- [x] [Clean Architecture](https://blog.coderifleman.com/2017/12/18/the-clean-architecture/) by Robert C. Martin
- [x] [REST API](https://meetup.toast.com/posts/92)
- [x] [BEM](http://getbem.com/)

## 코딩 컨벤션

- **Airbnb** Style Guide
  - [x] [JavaScript](https://github.com/airbnb/javascript) - [번역본](https://github.com/ParkSB/javascript-style-guide)
  - [x] [React/JSX](https://github.com/airbnb/javascript/tree/master/react) - [번역본](https://github.com/apple77y/javascript/tree/master/react)
- **NHN의 FE개발랩** 웹 프론트 개발 가이드
  - [x] [HTML/CSS/Sass](https://ui.toast.com/fe-guide/ko_HTMLCSS)
  - [x] [코딩컨벤션](https://ui.toast.com/fe-guide/ko_CODING-CONVENSION/)
  - [x] [안티 패턴](https://ui.toast.com/fe-guide/ko_ANTI-PATTERN/)
  - [x] [정적 분석](https://ui.toast.com/fe-guide/ko_STATIC-ANALYSIS/)
  - [x] [성능 최적화](https://ui.toast.com/fe-guide/ko_PERFORMANCE/)
  - [x] [디버깅](https://ui.toast.com/fe-guide/ko_DEBUG/)
  - [x] [의존성 관리](https://ui.toast.com/fe-guide/ko_DEPENDENCY-MANAGE/)
  - [x] [번들러](https://ui.toast.com/fe-guide/ko_BUNDLER/)
  - [x] [테스트](https://ui.toast.com/fe-guide/ko_TEST/)

## 개발

- [x] [HTML5](https://ui.toast.com/fe-guide/ko_HTMLCSS)
- ES6+ (ES2015+)
  - 표준 [ECMA-262](https://www.ecma-international.org/publications/standards/Ecma-262.htm) - ECMAScript
    - JavaScript는 ECMAScript 사양을 준수하는 범용 스크립팅 언어
  - [x] [TypeScript](https://www.typescriptlang.org/docs/)
  - [x] [React](https://reactjs.org/docs/) - [번역본](https://ko.reactjs.org/docs/)
    - React 프레임워크
      - [x] [next.js](https://nextjs.org/docs/)
      - [ ] [Create React App](https://create-react-app.dev/docs/getting-started)
    - [x] [react-redux](https://react-redux.js.org/) - React 상태 컨테이너
      - [Redux](https://lunit.gitbook.io/redux-in-korean/) (한글)
    - [x] [redux-saga](https://mskims.github.io/redux-saga-in-korean/) (한글)
- CSS3
  - [x] [Ant Design](https://ant.design/docs/react/introduce) - React UI 컴포넌트 라이브러리
  - [x] [styled-components](https://www.styled-components.com/docs) - CSS-in-JS 라이브러리
  - [x] [Sass(Syntactically Awesome Style Sheets)](https://sass-lang.com/documentation) - CSS pre-processor. CSS의 한계와 단점을 보완하여 보다 가독성이 높고 코드의 재사용에 유리한 CSS를 생성하기 위한 CSS의 확장(extension)
- JavaScript 라이브러리
  - [x] [eslint](https://eslint.org/)- 린터(JavaScript linter)
  - [x] [prettier](https://prettier.io/) - 코드 포맷터
  - [x] [axios](https://github.com/axios/axios) - HTTP 클라이언트
  - [x] [winston](https://github.com/winstonjs/winston) - 로그(Logger)
  - [x] [i18next](https://www.i18next.com/) - 국제화 라이브러리
  - [x] [moment](https://momentjs.com/docs/) - 날짜 관련 라이브러리
  - [x] [lodash](https://lodash.com/) - JavaScript 유틸리티 라이브러리
- [x] HTTP 프로토콜 - [MDN HTTP 개요](https://developer.mozilla.org/ko/docs/Web/HTTP/Overview)

## 테스트

- [x] [JEST](ksdhj) - JavaScript 단위 테스트
- [x] [Enzyme](https://airbnb.io/enzyme/) - React 컴포넌트 테스트
- [x] [POSTMAN](https://www.getpostman.com/) - API를 테스트

## 소스 제어

- [x] [Git](https://git-scm.com/) - 분산 버전 관리 시스템
- [x] [Bitbucket](https://bitbucket.org/) - Git 저장소. Git을 프로젝트 기반으로 체계적으로 관리하고 Bitbucket 서버에 웹으로 접근하여 코드의 커밋 히스토리, Pull Request, Fork 등을 쉽고 편하게 수행할 수 있게 지원하는 제품

## 종속성 관리

- [x] Node.js 패키지 매니저
  - [ ] [npm](https://www.npmjs.com/) - Node.js의 기본 패키지 매니저
  - [x] [yarn](https://yarnpkg.com/lang/en/) - JavaScript의 새로운 패키지 매니저
- [x] [Nexus Repository Manager 3](https://help.sonatype.com/repomanager3) - 회사 내 Maven, NPM 저장소로 이용

## 빌드

- [x] [Babel](https://babeljs.io/) - ECMAScript 2015+ (ES6+) 로 작성된 코드를 함수적으로 동일한 ES5 코드로 변환해 주는 JavaScript 컴파일러. Internet Explorer 등 다양한 브라우저 종류로 발생하는 호환성(Cross Browser) 문제 해결을 위해 사용.
- [x] [Webpack](https://webpack.js.org/) - JavaScript 모듈 번들러
  - 모듈 번들러란 여러개의 나누어져 있는 파일들을 하나의 파일로 만들어주는 라이브러리
  - 모듈 번들러는 JavaScript 코드들을 압축하고 최적화 할 수 있기 때문에 로딩 속도를 높일 수 있음

## CI (지속적 통합)

- [x] [Bamboo](https://www.atlassian.com/ko/software/bamboo) - 자동화된 빌드, 테스트 및 릴리즈를 함께 단일 워크플로우에 연결하는 지속적 통합 및 배포 도구

## 운영

- [x] [Red Hat Enterprise Linux 8](https://www.redhat.com/ko/technologies/linux-platforms/enterprise-linux)
- [x] [PM2](http://pm2.keymetrics.io/) - Node.js 프로세스 관리자
- [x] [Node.js](https://nodejs.org/) - [번역본](https://nodejs.org/ko/) - V8 (JavaScript 엔진)으로 빌드 된 이벤트 기반 JavaScript 런타임

## 상용 솔루션 (기능별 제품)

- Git 코드 관리 - [아틀라시안](https://www.atlassian.com/ko) **Bitbucket**
- CI (지속적 통합) - **Bamboo**
- 웹브라우저 인증서 (범용네트워크암호/인증)
  - [라온시큐어](https://www.raonsecure.com/) **Key# Biz** v2.0
- 트랜잭션보안 및 바이러스보호 SW
  - [라온시큐어](https://www.raonsecure.com/) **TouchEn Transkey** v4.6 - (PC) 가상키패드/Server
  - [라온시큐어](https://www.raonsecure.com/) **TouchEn mTranskey** v4.6 - 모바일 키보드보안(Web용)
- 출력물(보고서) - [포시에스](http://www.forcs.com/) **OZ Report**
- Extended Validation (EV) SSL 인증서
  - [ ] [Sectigo](https://sectigo.com/)
  - [x] [DigiCert](https://www.digicert.com/) - crowdnet, lei-k
  - [ ] [GlobalSign](https://www.globalsign.com/) - e-safe, dacc
  - [ ] [Thawte](https://www.thawte.com/) - safeplus
  - [ ] [GeoTrust](https://www.geotrust.com/) - ksd, evote, nanum
  - [ ] [Let’s Encrypt](https://letsencrypt.org/) (무료)
- 통합 서버보안 솔루션 - [sga](http://www.sgasol.kr/kr/01_product/product01.php) **RadCastle**
- 쉘 모니터(ShellMonitor) - [umv기술](http://www.umv.co.kr/kor/product/product0101.php) **WSS**(Web Server Safeguard)
- Linux 백업 - [Acronis](https://www.acronis.com/ko-kr/business/backup/linux-server/) **Backup**

## 성능

- [x] [Lighthouse](https://developers.google.com/web/tools/lighthouse/?hl=ko)
- [x] [KOREA HTML5 통합진단](https://www.koreahtml5.kr/front/diagnosis/diagnosticUrl.do)
- [x] [WebPageTest](https://www.webpagetest.org/)
- [x] [PageSpeed Insights 도구](https://developers.google.com/speed/pagespeed/insights/?hl=ko)

## SEO

- [x] [구글 검색엔진 최적화(SEO) 초보자 가이드](https://support.google.com/webmasters/answer/7451184?hl=ko)
- [x] [네이버 웹 표준 최적화 기본 가이드](https://webmastertool.naver.com/guide/basic_optimize.naver#chapter1.1)

## 공개 SW

- [x] [네이버 오픈소스 가이드](https://naver.github.io/OpenSourceGuide/book/)

## [참고] 기술 블로그

- [제로초](https://www.zerocho.com/)
  - [x] (강의) [React로 NodeBird SNS 만들기](https://www.inflearn.com/course/react_nodebird/dashboard) - Next.js
  - [ ] (도서) [Node.js 교과서](https://thebook.io/006982/)
- landvibe - [카카오페이지 웹 React 포팅 후기](https://medium.com/@ljs0705/카카오페이지-웹-react-포팅-후기-76402cc5e031) - Next.js
  - [x] (도서) [실전 리액트 프로그래밍 - 리액트 훅부터 Next.js까지](http://www.kyobobook.co.kr/product/detailViewKor.laf?mallGb=KOR&ejkGb=KOR&linkClass=&barcode=9788966262465#N)
- [벨로퍼트](https://velog.io/@velopert)
  - [ ] (도서) [리액트를 다루는 기술](https://thebook.io/006946/) - Create React App
- [캡틴판교](https://joshua1988.github.io/) - 웹 기초
- [web.dev](https://web.dev/)

## To Do

- [ ] 웹서버 캐시 처리
- [ ] PWA - [MDN 프로그레시브 웹 앱 소개](https://developer.mozilla.org/ko/docs/Web/Progressive_web_apps/소개)
- [ ] [Docker](https://www.docker.com/)
