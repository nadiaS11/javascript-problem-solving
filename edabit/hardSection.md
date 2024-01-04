***1. Create a function that takes an array of numbers and return "Boom!" if the digit 7 appears in the array. Otherwise, return "there is no 7 in the array.***

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
***2. Return the Next Number from the Integer Passed***

```js client
function addition(num) {
	return num+1
}
```
**3. Return the count of 'true'**

```js client
const countTrue=(arr)=>{
    const trueArr=arr.filter(item => item === true)
    return trueArr.length
}
```
**4. Return the base-2(binary) of a base-10(decimal) number**

```js client
function binary(decimal) {
	return decimal.toString(2);
}
```
