# JavaScript coding challenges Beginners

## 1. Even or Odd

Create a function that takes an integer as an argument and returns "Even" for even numbers or "Odd" for odd numbers.

```js
function evenOrOdd(number) {
  // Your solution
}
```

<details><summary>Solution</summary>

```js
function evenOrOdd(number) {
  let result;

  if(number % 2 === 0){
    return result = "Even";
  }else{
    return result = "Odd";
  }
};

### Test Results:
### Sample tests

2 is even
7 is odd
-42 is even
-7 is odd
0 is even

```

## </details>

**[⬆ Back to Top](#JavaScript-coding-challenges-Beginners)**

## 2. Print planets using Switch statement

Create a function thats print the "8 name of the planets" in order to its distance from the sun and they are; Mercury, Venus, Earth, Mars, Jupiter, Saturn, Uranus, and Neptune using "Switch statement".

```js
function getPlanetName(id) {
  // Your Solution
}
```

<details><summary>Solution</summary>

```js
function getPlanetName(id){
  let name;

  switch(id){
   case 1:
      return name ="Mercury";
      break;
   case 2:
      return name ="Venus";
      break;
   case 3:
      return name="Earth";
      break;
   case 4:
      return name ="Mars";
      break;
   case 5:
      return name ="Jupiter";
      break;
   case 6:
      return name="Saturn";
      break;
   case 7:
      return name="Uranus";
      break;
   case 8:
      return name="Neptune";
      break;
  }
  return name;
}

### Test Results:
### Sample tests

3 --> "Earth"

```

</details>

---

**[⬆ Back to Top](#JavaScript-coding-challenges-Beginners)**

## 3.Reversed Strings

Create a function that reverse a string "world" => "dlrow".

```js
function solution(str) {
  // Your Solution
}
```

<details><summary>Solution</summary>

```js
function solution(str) {
  return str.split("").reverse().join("");
}

solution("world");
```

</details>

---

**[⬆ Back to Top](#JavaScript-coding-challenges-Beginners)**

## 4.Vowel Count

Create a function that return the number (count) of vowels in the given string.We will consider a, e, i, o, u as vowels for this Kata (but not y).
The input string will only consist of lower case letters and/or spaces.

```js
function getCount(str) {
  // Your Solution
}
```

<details><summary>Solution</summary>

```js
function getCount(str) {
  let vowel = 0;

  const strArr = str.split("");

  for (let i = 0; i < strArr.length; i++) {
    switch (strArr[i]) {
      case "a":
        vowel++;
        break;
      case "e":
        vowel++;
        break;
      case "i":
        vowel++;
        break;
      case "o":
        vowel++;
        break;
      case "u":
        vowel++;
    }
  }
  return vowel;
}
```

</details>

---

**[⬆ Back to Top](#JavaScript-coding-challenges-Beginners)**

## 5. Sum of positive

Create a function that you get an array of numbers, return the sum of all of the positives ones.

Example [1,-4,7,12] => 1 + 7 + 12 = 20

Note: if there is nothing to sum, the sum is default to 0.

```js
function positiveSum(arr) {
  // Your Solution
}
```

<details><summary>Solution</summary>

```js
function positiveSum(arr) {
  let positiveNum = 0;

  for (let i = 0; i < arr.length; i++) {
    if (arr[i] > 0) {
      positiveNum += arr[i];
    }
  }
  return positiveNum;
}
```

</details>

---

**[⬆ Back to Top](#JavaScript-coding-challenges-Beginners)**

## 6.
