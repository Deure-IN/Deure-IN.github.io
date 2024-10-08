# Lesson 1-4 : 구조체

<br>

- **구조체**는 복잡한 자료형을 필요로 할 때 사용

- **자료형 string**은 임의의 길이를 가진 UTF-8 데이터를 위해 활용됨 

  <br>


### 문제

- Zombie라는 struct를 생성
- Zombie 구조체는 name(string형)과 dna(uint형)라는 2가지 특성을 가짐

<br>

### 해설

```solidity
pragma solidity ^0.4.19;

contract ZombieFactory {

    uint dnaDigits = 16;
    uint dnaModulus = 10 ** dnaDigits;

	// 답
	struct Zombie {
    	string name;
    	uint dna;
	}
}
```

