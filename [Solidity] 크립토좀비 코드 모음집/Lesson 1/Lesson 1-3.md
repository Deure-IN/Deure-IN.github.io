# Lesson 1-3 : 수학 연산

<br>

- 덧셈: x + y

- 뺄셈: x - y

- 곱셈: x * y

- 나눗셈: x / y

- 나머지: x % y(13 % 5 = 3)

- 지수: x ** y  또는  x^y

  <br>

### 문제

- dnaModulus라는 uint형 변수를 생성하고 10의 dnaDigits승을 배정

<br>

### 해설

```solidity
pragma solidity ^0.4.19;

contract ZombieFactory {

    uint dnaDigits = 16;
    uint dnaModulus = 10^dnaDigits;

}
```

