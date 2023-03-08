# for loop basic pratice question

## for loop 

1. write a program to print this pattern. 


    \* \
    \* \* \
    \* \* \* \
    \* \* \* \* \
    \* \* \* \* \*  


```javascript

let n = 5;
let string = "";
for (let i = 1; i <= n; i++) {
  for (let j = 1; j <=i; j++) {
    string += "*";
  }
  string += "\n";
}
console.log(string);
```

2. write a program to print the square?

```javascript
let n=5;
let string=""
for(let i<1; i<=n; i++>){
  for(let i<1; i<=n; i++){
    string+="*"
  }
  string+="\n"
}
console.log(string)
```

3. write a program to print the this pattern?
``` javascript 
n = 5;
let string = "";
for (let i = 0; i <=n; i++) {
  for (let j = 0; j<=n-i; j++) {
    string += "*";
  }
  string += "\n";
}
console.log(string);

```

4. Write a program to print this pattern :-
\1
\1\2
\1\2\3
\1\2\3\4
\1\2\3\4\5

```javascript
n = 5;
let string = "";
for (let i = 1; i <=n; i++) {
  for (let j = 1; j<=i; j++) {
    string += j;
  }
  string += "\n";
}
console.log(string);
```



