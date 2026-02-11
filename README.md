# JavaScript
lets start with new things 

JavaScript is a programming language (Dynamically typed)
. To print something at console this syntex is used -- console.log("good day everyone") 
. Now we are studing about various key things, in javascript.

Variables :
to start with, variables are the basic elements to start JS, to initiate with.

let 
var
const

. variable names are case senitive.
. only letters, digits, (_) and $ is allowed in it.
. no digit can be the 1st character of a variable name.
. reserved words cannot be used as variable name.

. list of some keywords

break
case
catch
class
const
continue
debugger
default
delete
do
else
export
extends
finally
for
function
if
import
in
instanceof
new
return
super
switch
this
throw
try
typeof
var
void
while
with
yield

Data Types:
lets see what are the data types in JS

.Primitive(7)
Number
String 
Boolean 
Undefined
Null
BigInt
Symbol

.Non_Primitive
Object

Operators and Conditional Statements:
??

.Arithmetic Operators: mathematic calculation

+, -, *, /
Modulus %
Exponentiation **
Increment ++
Decrement --

.Assignment Operations: 
=, +=, -=, *=, %=, **=

.comparison operations:
==, ===, !=, !==
<, <=, >, >=

.logical operations
AND &&, 
OR ||, 
NOT !

.conditional statements: to implement some condition in the code
if 
if-else
else-if

.ternary operations: condition ? trueOutput : falseOutput ;

// ALERT ("HELLO !") -- ONE TIME POP UP .
// PROMPT ("ENTER YOUR NAME !") -- TEMP WAY TO TAKE INPUT FROM USERS.

// SWITCH : ----
const expr = "Papa";
switch (expr) {

case "Mama":
      console.log("mama is here");
      break;
case "Didi":
case "Papa":
      console.log("papa, didi is here");
      break;
default:
      console.log("No one is here");

Loops 
// never create a infinite loop 

.for loop

for ( let count = 1; count <= 5; count++){
console.log("Apna college");
}

.while loop

i = 1;  //initialation
while(i<=5){
console.log(Apna College);
i++;
}

.do while loop

.for of

let str = "GautamJangir";
for(let i of str){
console.log(i);
}

.for in   // returns keys

let student = {
name : "gautam jangir",
age : 21,
cgpa : 7.01 };

for(let i in student){
console.log(i);
}

#Game 
// Guess the correct number
let gameNum = 24;
let userNum = prompt("Guess a Num:");

while(userNum!=gameNum){
    if(userNum > gameNum){
     userNum =prompt("Guess something smaller");
    }else if(userNum<gameNum) {
     userNum = prompt("Guess something bigger");
    }
}
console.log("Congratulation, you enter the right number");


String Methods
// while see tomorrow, and done till 5 feb as per schedule      

you aree given an integer array nums of length n. An array is trionic, if there exist indices 0<p<q<n-1 such that , 
. nums[0.....p] is strictly increasing 
. nums[p....q] is strictly decreasing
. nums[q....n-1] is strictly increasing 
return true, if nums is trionic/otherwise false
[0....p][p....q][q......n-1]


var isTrionic = function(nums)
const n = nums.length;
for ( let p=1; p<n-2; p++1){
for ( let q=p+1; q<n-1; q++){
 let valid = true;
 for (let i=0; i<p; i++){
 if(nums[i] >= nums[i+1]){
  valid = false;
  
      
