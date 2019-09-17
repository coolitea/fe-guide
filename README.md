# 프론트엔드 개발 가이드

## 개발도구

- [Visual Studio Code](https://code.visualstudio.com/)
- [크롬](https://www.google.com/intl/ko/chrome/)
  - [Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools/?hl=ko)
  - [React Developer Tools](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi?hl=ko)
  - [Redux DevTools Extension](http://extension.remotedev.io/)

## 설계

- [Clean Architecture](https://blog.coderifleman.com/2017/12/18/the-clean-architecture/) by Robert C. Martin
- [REST API](https://meetup.toast.com/posts/92)
- [BEM](http://getbem.com/)

## 코딩 컨벤션

- **Airbnb** Style Guide
  - [JavaScript](https://github.com/airbnb/javascript) - [번역본](https://github.com/ParkSB/javascript-style-guide)
  - [React/JSX](https://github.com/airbnb/javascript/tree/master/react) - [번역본](https://github.com/apple77y/javascript/tree/master/react)
- **NHN의 FE개발랩** 웹 프론트 개발 가이드
  - [HTML/CSS/Sass](https://ui.toast.com/fe-guide/ko_HTMLCSS)
  - [코딩컨벤션](https://ui.toast.com/fe-guide/ko_CODING-CONVENSION/)
  - [안티 패턴](https://ui.toast.com/fe-guide/ko_ANTI-PATTERN/)
  - [정적 분석](https://ui.toast.com/fe-guide/ko_STATIC-ANALYSIS/)
  - [성능 최적화](https://ui.toast.com/fe-guide/ko_PERFORMANCE/)
  - [디버깅](https://ui.toast.com/fe-guide/ko_DEBUG/)
  - [의존성 관리](https://ui.toast.com/fe-guide/ko_DEPENDENCY-MANAGE/)
  - [번들러](https://ui.toast.com/fe-guide/ko_BUNDLER/)
  - [테스트](https://ui.toast.com/fe-guide/ko_TEST/)

## 개발

- [HTML5](https://ui.toast.com/fe-guide/ko_HTMLCSS)
- ES6 (ES2015)
  - [TypeScript](https://www.typescriptlang.org/docs/)
  - [React](https://reactjs.org/docs/) - [번역본](https://ko.reactjs.org/docs/)
    - [x] [Next.js](https://nextjs.org/docs/)
    - [ ] [Create React App](https://create-react-app.dev/docs/getting-started)
    - [redux](https://redux.js.org/introduction/getting-started)
    - [redux saga](https://mskims.github.io/redux-saga-in-korean/) (한글)
- CSS3
  - [Ant Design](https://ant.design/docs/react/introduce)
  - [styled-components](https://www.styled-components.com/docs)
  - [Sass](https://sass-lang.com/documentation)
- Util
  - [eslint](https://eslint.org/)- JavaScript linter
  - [Prettier](https://prettier.io/) - Code formatter
  - [axios](https://github.com/axios/axios) - HTTP client
  - [winston](https://github.com/winstonjs/winston) - Logger
  - [i18next](https://www.i18next.com/) - 국제화
  - [moment](https://momentjs.com/docs/) - Date
  - [lodash](https://lodash.com/)
- HTTP 프로토콜 - [MDN HTTP 개요](https://developer.mozilla.org/ko/docs/Web/HTTP/Overview)

## 테스트

- [JEST](ksdhj)
- [Enzyme](https://airbnb.io/enzyme/)
- [POSTMAN](https://www.getpostman.com/)

## 소스 제어

- [Git](https://git-scm.com/)
- [Bitbucket](https://bitbucket.org/)

## 종속성 관리

- [ ] [npm](https://www.npmjs.com/)
- [x] [yarn](https://yarnpkg.com/lang/en/)
- [Nexus Repository Manager 3](https://help.sonatype.com/repomanager3)

## 빌드

- [Babel](https://babeljs.io/)
- [Webpack](https://webpack.js.org/)

## CI (지속적 통합)

- [Bamboo](https://www.atlassian.com/ko/software/bamboo)

## 운영

- [Red Hat Enterprise Linux 8](https://www.redhat.com/ko/technologies/linux-platforms/enterprise-linux)
- [PM2](http://pm2.keymetrics.io/)
- [Node.js](https://nodejs.org/) - [번역본](https://nodejs.org/ko/)

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

- [Lighthouse](https://developers.google.com/web/tools/lighthouse/?hl=ko)
- [KOREA HTML5 통합진단](https://www.koreahtml5.kr/front/diagnosis/diagnosticUrl.do)
- [WebPageTest](https://www.webpagetest.org/)
- [PageSpeed Insights 도구](https://developers.google.com/speed/pagespeed/insights/?hl=ko)

## SEO

- [구글 검색엔진 최적화(SEO) 초보자 가이드](https://support.google.com/webmasters/answer/7451184?hl=ko)
- [네이버 웹 표준 최적화 기본 가이드](https://webmastertool.naver.com/guide/basic_optimize.naver#chapter1.1)

## 공개 SW

- [네이버 오픈소스 가이드](https://naver.github.io/OpenSourceGuide/book/)

## [참고] 기술 블로그

- [제로초](https://www.zerocho.com/) - SSR React
  - (도서) [Node.js 교과서](https://thebook.io/006982/)
- [landvibe](https://medium.com/@ljs0705/카카오페이지-웹-react-포팅-후기-76402cc5e031) - 카카오페이지 웹 React 포팅 후기
  - (도서) [실전 리액트 프로그래밍](http://www.kyobobook.co.kr/product/detailViewKor.laf?mallGb=KOR&ejkGb=KOR&linkClass=&barcode=9788966262465#N)  
- [벨로퍼트](https://velog.io/@velopert) - React
  - (도서) [리액트를 다루는 기술](https://thebook.io/006946/)
- [캡틴판교](https://joshua1988.github.io/) - 웹 기초
- [web.dev](https://web.dev/)

## To Do

- 웹서버 캐시
- PWA - [MDN 프로그레시브 웹 앱 소개](https://developer.mozilla.org/ko/docs/Web/Progressive_web_apps/소개)
- 도커
