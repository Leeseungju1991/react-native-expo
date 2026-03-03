\# React Native Expo Project Analysis



\## 1. 프로젝트 개요



Expo 기반 React Native 애플리케이션.

Redux 기반 상태관리 구조를 사용하며,

navigation / service / reducer / selector 계층이 명확히 분리되어 있음.



EAS 설정이 포함되어 있어 배포를 고려한 구조로 판단됨.



---



\## 2. 아키텍처 분석



\### 구조



app/

\- components/

\- config/

\- navigation/

\- reducers/

\- screens/

\- selectors/

\- services/

\- utils/



\### 특징



\- Redux 기반 상태 관리

\- selector 분리 구조

\- network 서비스 계층 분리

\- 테마/타이포그래피 설정 존재



중급 이상 구조 설계가 적용되어 있음.



---



\## 3. 장점



\- 폴더 분리 명확

\- 관심사 분리 잘 되어 있음

\- API 계층 분리

\- EAS 배포 구조 포함



---



\## 4. 기술 부채 및 개선 필요 사항



1\. \_\_MACOSX 불필요 폴더 제거 필요

2\. TypeScript 미적용

3\. 테스트 코드 부재

4\. ESLint / Prettier 설정 확인 필요

5\. package.json 다중 존재 → 구조 점검 필요



---



\## 5. 개선 제안



P0

\- 불필요 폴더 정리



P1

\- ESLint + Prettier 설정

\- 환경변수 분리 (.env)



P2

\- TypeScript 마이그레이션

\- 테스트 코드 도입



---



\## 6. 향후 방향



\- 유지보수성 향상을 위한 타입 시스템 도입

\- 코드 품질 자동화 도구 적용

\- 성능 최적화 (FlatList 최적화 등)

