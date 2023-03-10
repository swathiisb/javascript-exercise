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
    *
   **
  ***
 ****
*****
 

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

5. write a program to print the half diamond?


\*
\*\*
\*\*\*
\*\*\*\*
\*\*\*\*\*
\*\*\*\*
\*\*\*
\*\*
\*


```javascript
let n=5;
string=""

for(let i=1; i<=n; i++ ){
  for(let k=1; k<=i; k++){
    string+="*"
  }
  string+="\n"
}

for(let i=1; i<=n; i++ ){
  for(let j=1; j<=n-i; j++){
    string+="*"
  }
  string+="\n"
}
console.log(string)



