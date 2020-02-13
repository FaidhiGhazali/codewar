# isogram

### Code For Isogram
```
isogram (str) {
  let arr = str.toLowerCase().split("")
  let inArr = []
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
