## level 1. 핸드폰번호 가리기(hiding number)
---
> My Answer
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