# 코드와 프로그래밍

어떤 언어를 사용하더라도 코드는 기계가 이해하고 실행할 정도로 엄밀하고, 정확하고, 상세하고 정형화되어야한다.

## 코드

- 요구 사항을 표현하고 상세히 하는 수단
- 정밀성이 필요하다.

## 프로그래밍

- 기계가 실행할 정도로 상세하게 요구사항을 명시하는 작업



# 좋은 코드와 나쁜 코드

## 나쁜 코드

### 어떤 코드가 나쁜 코드일까?

- 분당 WTF를 많이 할 수록 나쁜 코드
  - 좋은 코드는 그 반대!

### 나쁜 코드의 특성

- 팀의 생산성 저하
  - 확장성이 떨어지고, 나쁜 코드에 억지로 기능을 추가하다보면 더 리팩토링하기 어려워진다.
- 개발 속도 저하
  - 코드 해석이 어려워서, 코드에 대한 이해도가 낮은 신규 개발자가 오면 유지보수가 힘들다 → 나쁜 코드가 더 생산되기 딱 좋은 환경

### 왜 나쁜 코드를 짤까?

일정이 촉박 → 일단 기능이 돌아감 → 나중에 고치자 → 시간이 나지 않는다 → 레거시가 된다....

> 나중은 결코 오지 않는다! "르블랑의 법칙"

- 일정이 촉박해도, 코드 퀄리티에 대한 책임은 온전히 개발자에게 있다.
- 나쁜 코드를 그대로 방치한다면, 전문가 답지 못하다.
- 깨진 유리창의 법칙
  - 유리창이 깨져있으면 창문이 더 깨져도 사람들은 더 이상 신경쓰지 않는다.

## 좋은 코드

### 개발자들마다 정의 내리는 좋은 코드란?

| 이름                | 정의                                                         | 키워드                                         |
| ------------------- | ------------------------------------------------------------ | ---------------------------------------------- |
| 비야네 스트롭스트룹 | 보기에 즐거운 코드 세세한 사항까지 꼼꼼하게 처리한 코드      | 효율성, 리소스, 꼼꼼한 오류처리, 가독성        |
| 그래디 부치         | 잘 쓴 문장 처럼 잘 읽히는 코드                               | 가독성, 명확함                                 |
| 데이브 토마스       | 잘 읽히는 것도 중요하지만, 다른 사람들이 잘 고칠 수 있는 코드 | 가독성, 유지보수, 테스트 코드                  |
| 마이클 패더스       | 주의 깊게 짰다는 인상을 주는 코드                            | 꼼꼼한 오류처리, 주의                          |
| 론 제프리스         | 중복 줄이기 표현력 높이기 초반부터 간단한 추상화 고려하기    | 중복 없음, 테스트 코드, 명확함, 효율성, 추상화 |
| 워드 커닝햄         | 읽으면서 놀랄일이 없는 코드                                  | 명확함, 단순함, 가독성                         |



### 보이스카우트 규칙

- 코드는 시간이 지나도 깨끗하게 유지되어야한다.
- 코드를 짤 때마다 조금씩 깔끔하게 짜려고 노력하면, 한꺼번에 시간과 노력을 투자할 필요가 없다.

> 캠프장은 처음 왔을 때 보다 더 깨끗하게 해놓고 떠나라.

### 좋은 코드를 짜려면?

- 이 책에 나온 이야기들을 체화시키도록 연습하자!