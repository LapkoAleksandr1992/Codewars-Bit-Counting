# Codewars-Bit-Counting


var countBits = function(n) {
  let count=0
    let b=n.toString(2) 
    for(let i=0;i<b.length;i++) {
      if(b[i]==1) {
        count+=1
      }
    }
  return count
};
