# 구현할 기능
- 랜덤 숫자 생성
  - 1 ~ 9인 서로 다른 임의의 3자리 정수를 생성하여 반환한다.
- 입력
  - 게임중
    - 플레이어는 1 ~ 9 까지의 서로다른 숫자 3자리를 입력한다.
    - 3자리가 아닌 수가 입력되거나, 각 자리에 0또는 문자가 들어올 경우 IllegalArgumentException을 발생시킨다.
  - 게임종료후
    - "1"을 입력받으면 게임을 다시 시작한다.
    - "2"를 입력받으면 게임을 완전히 종료한다.
- 숫자 비교
  - 사용자의 입력과 랜덤생성된 숫자를 비교하여 같은 수가 같은 자리에 있으면 스트라이크, 다른 자리에 있으면 볼 이라 하여 스트라이크와 볼의 개수를 반환한다.
- 힌트 생성
  - 숫자 비교에서 반환받은 스트라이크와 볼의 개수를 통해 힌트를 생성한다.
  - 스트라이크가 3개면 게임을 종료한다.

