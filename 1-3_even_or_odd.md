## level 1. 짝수와 홀수(Even or Odd)
---

### My Answer
```javascript
function evenOrOdd(num) {
  var result = (num % 2 === 0) ? "Even" : "Odd";
  return result;
}


console.log("결과 : " + evenOrOdd(2));
console.log("결과 : " + evenOrOdd(3));
```

---
### Wrong answer notes
> Case 01. return을 해주지 않음.
```javascript
function evenOrOdd(num) {
  var result = ''
  result = (num % 2 == 0) ? "Even" : "Odd";
}
```