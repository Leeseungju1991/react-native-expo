\# React Native Expo Application



이 프로젝트는 Expo 기반으로 개발한 React Native 모바일 애플리케이션입니다.  

실무에서 사용하는 구조를 고려하여 상태 관리, 화면 구성, 네비게이션, API 계층을 분리하는 방식으로 설계하였습니다.



단순한 화면 구현이 아니라, 유지보수성과 확장성을 고려한 구조 설계를 목표로 개발했습니다.



---



\## 프로젝트 개요



본 애플리케이션은 Redux 기반 상태 관리를 적용하여 전역 상태를 효율적으로 관리하고,  

Selector 패턴을 통해 상태 의존성을 분리하였습니다.  

또한 API 통신 로직을 Service Layer로 분리하여 화면 로직과 네트워크 로직을 명확하게 구분하였습니다.



---



\## 기술 스택



\- React Native

\- Expo

\- Redux

\- React Navigation

\- EAS Build



---



\## 아키텍처 설계 방향



1\. 관심사 분리 (Separation of Concerns)

2\. 화면(Screen)과 비즈니스 로직 분리

3\. 네트워크 계층(Service) 분리

4\. 확장 가능한 폴더 구조 설계

5\. 유지보수를 고려한 상태 관리 구조



---



\## 폴더 구조 설명



\- screens: 화면 단위 컴포넌트

\- components: 재사용 가능한 공통 UI 컴포넌트

\- reducers: Redux 상태 관리 로직

\- selectors: 상태 파생 로직 분리

\- services: API 통신 및 외부 데이터 처리

\- config: 테마 및 환경 설정

\- utils: 공통 유틸 함수



---



\## 실행 방법



프로젝트 실행은 아래 명령어로 가능합니다.



npm install  

npx expo start



---



\## 향후 개선 계획



\- TypeScript 적용을 통한 타입 안정성 확보

\- 테스트 코드(Jest, React Native Testing Library) 도입

\- ESLint 및 Prettier 설정 강화

\- CI/CD 자동화 구성



---



\## 개발자



Seungju Lee  

GitHub: https://github.com/Leeseungju1991

