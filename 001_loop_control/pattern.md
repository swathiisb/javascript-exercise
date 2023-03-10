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

write a program to display this pattern:-
  
 <img width="350"  height="250" alt="Screenshot 2023-03-06 060708" src="https://user-images.githubusercontent.com/90920262/224251788-d6f3dccc-94ca-459d-a210-3eca886b9e41.png">


``` javascript
let n=5
string=""
for(let i=1; i<=n; i++){
  for(let j=0; j<n-i; j++){
    string+=" "
  }
  for(let k=0; k<i; k++){
    string+="*"
  }
 string+="\n"
}
console.log(string)
```




