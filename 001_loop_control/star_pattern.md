# for loop basic pratice question

1. write a program to print this pattern.                
```javascript
  let n = 5; // row or column count
// defining an empty string
let string = "";

for(let i = 0; i < n; i++) { 
  for(let j = 0; j < n; j++) { 
    string += "*";
  }
  
  string += "\n";
}
console.log(string);

```