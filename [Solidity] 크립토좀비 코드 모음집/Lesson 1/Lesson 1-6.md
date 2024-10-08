# Lesson 1-6 : 함수 선언

<br>

- 솔리디티는 함수 선언을 다음 예시와 같이 한다.

  ```solidity
  function eatHamburgers(string _name, uint _amount) {
  
  }
  ```


- 이 함수는 "eatHamburgers"라는 함수로 string형인 _name과 uint형인 _amount를 인자로 받고 있다.

- eatHamburgers함수를 호출할 때는 다음과 같이 호출할 수 있다.

  ```solidity
  eatHamburgers("vitalik", 100);
  ```

<br>

### 문제

- createZombie라는 함수를 생성, 이 함수는 _name(string형), _dna(uint형)을 인자로 받아야 함

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

    Zombie[] public zombies;

    // 답
	function createZombie(string _name, uint _dna) {
	}
}
```

