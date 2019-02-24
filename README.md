# JavaScript-
To get hands-on with JavaScript (basics and some advanced)

In this repo, we will see basic programs in Javascript and some advanced concepts related to scopes and closures too. 

IIFE - Immediately invoked function expression --> In this we can see that an anonymous funciton is declared and because it has to be executed and without a name is difficult we tend to exectute the funciton immediately after it has been declared by putting them in parenthesis. ( insert your function complete declartion)();
## here's the code:

```
(function ()
{
var a=10;
var b=10;
console.log(a+b);
}) ();
```

```
var a =10;
console.log(a);
var b= "Hello world";
console.log(b);
var c = true;
console.log(c);
a = "Hello world"; /*called loosely typed script is JavaScript*/ 
console.log(a);
var a;
console.log(a); /*for undefined*/
var z=null;
console.log(typeof z ); 
/*--- > It returns an object, this is 
a bug that cannot be fixed as it might 
break the code that is depenednt on it. */


var myObj = {
  "myprop": "Hello World"
}
var myObj2;
myObj2=myObj;
console.log(myObj2.myprop);

if (myObj===myObj2){
console.log("are equal");
}

var person = {
  'firstName': 'ramya' ,
  'lastName': 'KOya',
  'age':'23'
}
person.age= undefined;
delete person.age;
console.log(person.age);
console.log(person);

var arr1 = [1,2,3];
console.log(arr1[4]);
console.log(arr1[1]+arr1[2]);
arr1[3]="Java";
console.log(arr1);
delete arr1[4];

arr1.Length


```
