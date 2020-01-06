# 03 테스트 더블

## 3.1 테스트 더블의 위력

어떤 코드가 올바른 동작을 수행하는지 검증하려 할 때, 주변 코드를 모두 교체하여
테스트 환경 전반을 통제할 수 있다면 좋다. 이렇게 **테스트 대상 코드와 협력 객체를 잘 분리** 하면 된다.

테스트 더블을 이용하면 테스트 대상 코드를 주변으로부터 쉽게 떼어낼 수 있다

테스트 더블의 효과
- 테스트 대상 코드를 격리한다
- 테스트 속도를 개선한다
- 예측 불가능한 실행 요소를 제거한다
- 특수한 상황을 시뮬레이션 한다
- 감춰진 정보를 얻어낸다


## 3.1.1 테스트 대상 코드를 격리한다

테스트 대상 코드를 격리한다? 두가지로 나누어 생각한다

- 테스트 대상 코드
- 테스트 대상 코드와 상호작용하는 코드
