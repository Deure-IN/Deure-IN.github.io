# Lesson 1-5 : 배열

<br>



- **배열**은 어떤 것의 모음집이 필요할 때 사용할 수 있음

- 배열은 **정적 배열**과 **동적 배열**이 있음

  - **정적 배열**은 원소의 개수를 고정하는 배열
  - **동적 배열**은 고정된 크기가 없고 계속 크기가 커질 수 있음
  
  ```solidity
  // 2개의 원소를 담을 수 있는 고정 길이의 배열
  uint[2] fixedArray;
  // 5개의 스트링을 담을 수 있는 고정 길이의 배열
  string[5] stringArray;
  // 동적 배열은 고정된 크기가 없으며 계속 크기가 커질 수 있다:
  uint[] dynamicArray;
  ```

<br>

### 문제

- Zombie 구조체의 public 배열을 생성하고 이름을 zombies로 만들어라

<br>

### 해설

```solidity
pragma solidity ^0.4.19;

contract ZombieFactory {

    uint dnaDigits = 16;
    uint dnaModulus = 10 ** dnaDigits;

    struct Zombie {
        string name;
        uint dna;
    }
    
	// 답
    Zombie[] public zombies;

}
```

