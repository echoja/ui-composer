# ui-composer
UI 레이아웃 구성에 관한 일반화된 모델 구축

## 목표

전문가가 아닌 일반 사용자들이 콘텐츠를 구성하고자 할 때 동작하는 방식의 토대를 정의하고자 함. 이 모델을 통해 아래와 같은 결과물을 **쉽고 빠르게** 만들 수 있어야 함.

<img src="https://github.com/echoja/ui-composer/assets/73801151/1bf0fd75-8ee3-4717-b0c9-8442aba8d88e" alt="img" width="300"></img>

홍보용 포스터

---

<img src="https://github.com/echoja/ui-composer/assets/73801151/5440d4b8-cb6f-4145-9899-d6c9cf3e4449" alt="img" width="300"></img>

웹 홍보용 콘텐츠

---

<img src="https://github.com/echoja/ui-composer/assets/73801151/17612ecc-7f45-4793-86e5-32bdf3d23af4" alt="img" width="300"></img>

웹 배너

---

<img src="https://github.com/echoja/ui-composer/assets/73801151/eb1978ba-84c9-48ea-b242-c3abe3f75c2b" alt="img" width="300"></img>

웹 팝업

---
  
이 결과물을 만들기 위해 아래 요구사항을 충족해야 함.

- 콘텐츠를 봤을 때 직관적인 느낌으로서의 구조와 콘텐츠를 만들어가는 과정이 일치해야 함. (멘탈 모델과 최대한 유사)
  - 5살 아동에게 위 콘텐츠를 배껴서 그려라고 할 때 어떤 과정으로 그릴지를 계속해서 상상하자
- 모든 콘텐츠는 컨테이너의 가로/세로 사이즈가 변동될 때 적절하게 배치되거나 크기가 조절되어야 함 (반응형)
  - 예: X 버튼은 전체 컨테이너의 우상단에 고정되어야 함. 
- 웹 상에서 잘 노출되어야 함.
- 각각의 요소는 인터랙티브할 수 있어야 함.
- "적당히"를 표현할 수 있는 수단 마련하기. 예를 들어 웹 배너는 화면이 좌우로 늘어날 때 콘텐츠는 가운데에 고정되어 있어야 하는데, 이를 쉽게 표현하기가 힘듬

## 컨테이너

- Row
- Column
- Stack


## 흠터레스팅 🤔

- rust 로 만들어볼까?
- 다른 레이아웃 시스템을 배껴오자.
