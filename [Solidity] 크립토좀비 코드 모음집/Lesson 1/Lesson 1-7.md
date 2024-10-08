# Lesson 1-7 : 구조체와 배열 활용하기

<br>

- array.push()는 무언가를 배열의 끝에 추가해서 모든 원소가 순서를 유지하도록 함

  ```solidity
  uint[] numbers;
  numbers.push(5);
  numbers.push(10);
  numbers.push(15);
  // numbers 배열은 [5, 10, 15]과 같다.
  ```

<br>

### 문제

- 함수에 코드를 넣어 새로운 Zombie를 생성하여 zombies 배열에 추가하도록 한다. 새로운 좀비를 위한 

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

