# Lesson 1-2 : 상태 변수 & 정수

<br>

- **상태 변수**는 컨트랙트 저장소에 영구적으로 저장됨.(블록체인에 기록되는 것)

- **uint**은 부호 없는 정수로 값이 음수가 아니어야 한다는 의미

  <br>

### 문제

- dnaDigits라는 uint를 선언하고 16이라는 값을 배정

<br>

### 해설

```solidity
pragma solidity ^0.4.19;

contract ZombieFactory {

    uint dnaDigits = 16;

}

```

