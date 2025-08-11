# Javascript Complete Guide Documentation


## 1. Prerequisities 

### Difference between let, var, const


> 1. var
- Reassignment is possible
- var name can be used in multiple positions
- function scoped (can be used anywhere inside the function)


2. Let 
- Reassignment is not allowed
- cannot use same name once used


3. Const
- constant variable value
- cannot be changes 


let a =30;
a = 34;


let a = 23; // not allowed


const b =23;
b = 45; // not possible

var a = 22;
a = 34;

var a = 21;  // only allowed in var 

function abc() {
    if(true){
        var a =34;  // this a can be used everywhere within the function

    }
}

TDZ - Temporal Death Zone 
console.log(a)
var a = 34; // error - undefined 
let a = 34; // error -  Uncaught ReferenceError: Cannot access 'a' before initialization
   
- complier knows that 'a' will be present in further code but cannot access 
- code will execute line wise

TDZ - js knows that variables exists but cannot access it 


> 2.  Hoisting 

- 


