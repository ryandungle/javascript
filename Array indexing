function getIndexToIns(arr, num) {
  // Find my place in this sorted array.
  arr.sort(function(a, b){return a - b});
  for(let i =0; i< arr.length-1; i++){
    if(num<arr[i]){
      return i;
    }
    if(num === arr[i]  && num<arr[i+1]){
      console.log(arr);
      return i;
    };
    if(num > arr[i]  && num<arr[i+1]){
      console.log(arr);
      return i+1;
    }
  }

  return arr.length;
}
console.log(getIndexToIns([10, 20, 30, 40, 50], 35));
getIndexToIns([10, 20, 30, 40, 50], 35);
