## level 1. 핸드폰번호 가리기(hiding number)
---

### My Answer
```javascript
function hide_numbers(s){
  var result = "";
  for (var i=0; i<s.length-4; i++) {
    s = s.replace(s[i], "*")
  }
	result = s;
  
  return result;
}


console.log("결과 : " + hide_numbers('01033334444'));
```

---
### Wrong answer notes
> Case 01.  
```javascript
function hide_numbers(s){
  var result = "";

  for (var i=0; i<s.length-4; i++) {
    console.log(s.replace(s[i], "*"));
  }

  result = s;
  
  return result;
}

console.log("결과 : " + hide_numbers('01033334444'));
```
> Result Code
```
*1033334444
0*033334444
*1033334444
010*3334444
010*3334444
010*3334444
010*3334444
결과 : 01033334444
```