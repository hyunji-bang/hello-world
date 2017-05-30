## level 1. 평균값 구하기(Average)
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
function average(array){
  for( var i in array ) {
    //console.log(array[i]);
    var sum = 0;
    sum += array[0];
    console.log(sum);
  }

  return 0;
}

var testArray = [5,3,4] 
console.log("평균값 : " + average(testArray));
```
> Result Code
```
평균값 : 0
```