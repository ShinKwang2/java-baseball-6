# [숫자 야구 게임] - 3개자리

## 개요
컴퓨터의 3자리의 임의의 숫자를 빠르게 맞춰라

## 기능 구현 사항

### 게임 시작시
* 게임 시작 멘트
* ~~게임 시작시 3자리 랜덤 숫자 생성~~
  * 팩토리로 만들어보자.
* 3자리 랜덤 숫자 저장

### 게임 중간
* 에러
  * ~~숫자 외에 다른 것을 입력하면 -> 에러~~
  * 중복된 숫자를 입력하면 -> 에러
  * 3개보다 적거나 3개를 초과하는 숫자를 입력하면 -> 에러

* 정상
  ~~* 번호는 있지만, 자리 수가 다르면 : 볼~~
  ~~* 번호와 자리 수 모두 같다면 : 스트라이크~~
  ~~* 아무것도 없으면 : 낫싱~~

### 게임 종료시
* 재시작/종료를 구분하는 1과 2 중 하나의 수
* 만약 다른 것을 누른다면 -> ?



너무다 스태틱으로 하는 것 아닌가?
Application에는 어디까지 집어넣어야 하는가?
View를 매번 만들 필요가 있을까?