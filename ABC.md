# 🍓 Team1-Strawberry-FE

<br>

## 프로젝트 소개

- 현대자동차그룹 소프티어 부트캠프 4기 프로젝트입니다.
- 기획, 디자인 팀원과 상의한 산출물을 기반으로 개발하며, 사용자 경험 향상을 위해 끊임없이 개선점을 찾아가며 완성도 높은 결과를 목표로 하고있습니다.

<br>

## 프론트 팀원 구성

<div align="center">

| 김지성 | 마경미 |
| --- | --- |
| [<img src="https://avatars.githubusercontent.com/u/122510664?v=4" height=150 width=150> <br/> @JSK0406](https://github.com/JSK0406) | [<img src="https://avatars.githubusercontent.com/u/62610032?v=4" height=150 width=150> <br/> @akrudal](https://github.com/akrudal) |


</div>

<br>

## 프로젝트 구현 예정 기능

### 1. 랜딩 페이지

- 유저가 페이지에 처음 접속했을 때 볼 수 있는 페이지입니다.
- 신차에 대한 간략한 소개와 진행하는 이벤트의 설명을 확인할 수 있습니다.

### 2. 신차 소개 페이지

- 신차에 대한 상세한 설명을 볼 수 있는 페이지입니다.
- 각종 디자인 요소들과, 스크롤 이벤트, 캐러셀, 모달, 선택한 옵션의 차량 렌더링 등을 통해 사용자 경험 향상을 위합니다.

### 3. 선착순 퀴즈 이벤트 페이지

- 선착순으로 퀴즈를 맞추는 이벤트를 진행하는 페이지입니다.
- 소개 페이지와 진행 페이지로 나뉩니다.
- 이벤트 진행 페이지에서 퀴즈를 진행한 후 바로 결과를 확인할 수 있습니다.

### 4. 드로잉 이벤트 페이지

- 신차의 주요 특징을 드로잉 게임을 통해 고객에게 알릴 수 있는 페이지입니다.
- 소개 페이지, 진행 페이지, 결과 페이지로 나뉩니다.
- 소개 페이지에서 점수 랭킹과 자신의 점수를 확인할 수 있습니다.
- Canvas API를 사용하여 3단계의 드로잉 게임을 구현할 예정입니다.
- 사용자는 게임 진행 후 결과를 확인하고 이를 링크 공유할 수 있습니다.

### 5. 기대평 페이지

- 신차에 대한 기대평을 작성할 수 있는 페이지입니다.
- 고객은 기대평을 작성하거나 타인의 댓글을 확인할 수 있습니다.
- 지정한 단어를 사용하면 경고창이 뜨는 비속어 필터 기능을 추가할 예정입니다.

<br>

<br>

## 개발 환경

- Front : HTML, CSS, Javascript,  React, styled-components, Context API
- 버전 및 이슈관리 : Github, Github Issues
- 협업 툴 : Notion
- 서비스 배포 환경 : AWS EC2

<br>

## 프로젝트 구조

```
─ src
  ├─ assets
  │  └─ images
  ├─ App.tsx
  ├─ main.tsx
  ├─ core
  │  ├─ contexts
  │  ├─ design_system
  │  └─ utils
  ├─ layout
  │  ├─ DefaultLayout.tsx
  │  ├─ HeaderLayout.tsx
  │  └─ components
  ├─ pages
  │  ├─ common
  │  │  ├─ components
  │  │  ├─ contexts
  │  │  ├─ hooks
  │  │  └─ services
  │  ├─ drawing
  │  │  ├─ components
  │  │  ├─ contexts
  │  │  ├─ hooks
  │  │  └─ services
  │  ├─ expectation
  │  │  ├─ components
  │  │  ├─ contexts
  │  │  ├─ hooks
  │  │  └─ services
  │  ├─ introduce
  │  │  ├─ components
  │  │  ├─ contexts
  │  │  ├─ hooks
  │  │  └─ services
  │  ├─ login
  │  │  ├─ components
  │  │  ├─ contexts
  │  │  ├─ hooks
  │  │  └─ services
  │  ├─ newCar
  │  │  ├─ components
  │  │  ├─ contexts
  │  │  ├─ hooks
  │  │  └─ services
  │  └─ quiz
  │     ├─ components
  │     ├─ contexts
  │     ├─ hooks
  │     └─ services
  └─ router
```
