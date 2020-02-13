# isogram

### Code For Isogram
```
isogram (str) {
  var arr = str.toLowerCase().split("")
  var inArr = []
  for(var i =0; i<arr.length; i++){
   if (!inArr[arr[i]]) {
    inArr[arr[i]] = arr[i];
   } else {
    return false;
   }
  }
  return true;
}
```
