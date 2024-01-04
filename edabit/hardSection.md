**_ Create a function that takes an array of numbers and return "Boom!" if the digit 7 appears in the array. Otherwise, return "there is no 7 in the array". _**

```js client
const sevenBoom = (arr) => {
  const myArr = [...arr];
  const find7 = myArr.find((item) => item.toString().includes("7"));
  console.log(find7);
  if (find7) {
    return "Boom!";
  } else {
    return "there is no 7 in the array";
  }
};
sevenBoom([2, 6, 7, 9, 3]); //"Boom!"
sevenBoom([33, 68, 400, 5]); //"there is no 7 in the array"
sevenBoom([86, 48, 100, 66]); // "there is no 7 in the array"
sevenBoom([76, 55, 44, 32]); // "Boom!"
sevenBoom([35, 4, 9, 37]); //"Boom!"
```
