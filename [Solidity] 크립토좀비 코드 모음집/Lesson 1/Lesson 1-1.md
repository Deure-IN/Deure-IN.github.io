# Lesson 1-1 : Contract

<br>

- **Version Pragma**는 해당 코드가 이용해야 하는 솔리디티 버전을 선언하는 것

  새로운 컴파일러 버전이 나와도 기존 코드가 깨지지 않도록 예방하는 것

  Pragma 선언 방법 :  pragma solidity ^"version";

- **Contract**는 이더리움 app의 기본적인 구성 요소

  모든 변수와 함수는 contract에 속함

<br>

### 문제

1.  솔리디티 버전 0.4.19를 쓸 수 있도록 설정

2.  ZombieFactory라는 빈 contract 생성

   <br>

### 해설

```solidity
pragma solidity ^0.4.19;  // "^"표시는 0.4.19버전 이상부터 쓸 수 있다는 뜻

contract ZombieFactory{

}

```

