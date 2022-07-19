# Day-04

JSON with proper order

 var obj1 = {name: "person",age:5}
    
var obj2 = {age:5 ,name: "person"};
  
a=JSON.stringify(obj1)
b=JSON.stringify(obj2)
console.log(a,b)
