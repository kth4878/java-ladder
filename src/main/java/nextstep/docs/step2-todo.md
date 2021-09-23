# 2단계 - 사다리(생성)

## 기능 요구 사항
- [x] 사다리 게임에 참여할 사람의 이름을 입력 받는다.
    - 이름은 최소 1글자, 최대 5글자까지 부여할 수 있다.
    - 쉼표(,)를 기준으로 구분한다.
    - 게임 플레이는 최소 2명 이상이 참가해야 한다.
- [x] 사다리의 최대 높이를 입력 받는다.
    - 사다리의 높이는 1 이상이어야 한다.
- [x] 사다리 라인을 구현한다.
    - 라인은 랜덤으로 생성한다.
    - 바로 앞 포인트에 라인이 존재한다면 다음 포인트는 라인이 존재할 수 없다.
- [x] 입력 받은 참가자의 이름을 출력한다.
- [x] 입력 받은 높이에 해당하는 사다리를 출력한다.
    - 사다리 한 라인의 좌표를 갖는 객체를 구현한다.


## 프로그래밍 요구사항
- 자바 8의 스트림과 람다를 적용한다.
- 규칙 6: 모든 엔티티를 작게 유지한다.