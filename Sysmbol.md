Symbol新类型
===========

## 知识点

* ES6增加了Symbol新的原始类型

## 实战演习

~~~js
let str1 = String("HelloWorld");
let str2 = String("HelloWorld");
console.log(str1 == str2); //true
console.log(str1 === str2); //true

let s1 = Symbol("mySymbol");
let s2 = Symbol("mySymbol");
console.log(typeof s1); //结果:symbol
console.log(s1.toString()); //结果:Symbol(mySymbol)
console.log(s1 == s2); //结果:false
console.log(s1 === s2);//结果:false
~~~
