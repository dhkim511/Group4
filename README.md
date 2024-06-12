# 토이 프로젝트 I

## 프로젝트 정의

부트캠프 수강생과 관리자가 출결, 휴가, 공가 신청 및 문서 발급 신청/처리를 더 간편하게 하기 위한 플랫폼

- **수강생 인트라넷**: 출결 정정 요청, 외출/조퇴 신청, 휴가 및 공가 신청, 문서 발급 요청 등을 포함합니다.
- **관리자 인트라넷**: 수강생의 출결 정정 요청, 외출/조퇴 신청, 휴가 및 공가 신청, 문서 발급 요청을 관리하고 승인/거절 처리하는 기능을 포함합니다

## 설치

페스트넷 인트라넷 플랫폼은 서버와 클라이언트 시스템으로 구성되며 Javascript 와 Nodejs 기반으로 구성되어있습니다.

프로젝트 저장소를 다음 설명에 따라 개발자 컴퓨터에 복사하고 설치 명령을 입력하여 설치를 할 수 있습니다.

```jsx
git clone https://github.com/dhkim511/Group4.git
cd fastnetProject
npm install
```

- [Git - Downloads](https://git-scm.com/downloads)
- [Node.js — Download Node.js®](https://git-scm.com/downloads)

## 실행

개발자 로컬 환경에서 개발 모드로 실행하기 위해선 프로젝트 루트디렉토리에서 다음의 명령을 실행하세요

```jsx
npm run dev
```

## 배포

## 문서

프로젝트 설계 문서는 design 디렉토리에 마크다운 파일로 기록되어있습니다. 각각의 설계 문서는 다음과 같습니다.

- 요구사항 정의서
  - 제품이 제공해야되는 기능 요구 정의서입니다.
  - 요구사항 정의서에 기술된 기능은 최소 기능 요구사항이며 추상적일 수 있으며 기능의 구체화는 제품 구현 단계에서 이루어집니다.
- 프로젝트 설계서
  - 요구사항 정의서를 기반으로 프로젝트를 설계합니다.
- 기능 정의서
  - 사용자 스토리 기반으로 세부 기능을 정의합니다.
