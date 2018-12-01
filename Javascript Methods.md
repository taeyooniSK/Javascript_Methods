JavaScript Methods
==================
* * *
  
## 1. String

####1.1 Basic Usages
  * **1.1.1** - *accessing a character*
  * **1.1.2** - *'+' / concat*
####1.2 Properties
  * **1.2.1** - *length*
####1.3 Methods
  * **1.3.1** - *indexOf, lastIndexOf (includes)*
  * **1.3.2** - *split*
  * **1.3.3** - *substring(slice)*
  * **1.3.4** - *toLowerCase / toUpperCase*
  * **1.3.5** - *trim*
  * **1.3.6** - *match*
  * **1.3.7** - *replace*

____________________________________

####1.1.1 Basic Usages - Accessing a Character
* *str[index]*

```
var str = 'CodeStates';
console.log(str[0]);  // 'C'
console.log(str[4]);  // 'S'
console.log(str[10]); // undefined
```

* *Note*: index로 접근은 가능하지만 쓸 수는 없음 (read-only)

```
str[0] = 'G';
console.log(str); // 'CodeStates' not 'GodeStates'
```

####1.1.2 Property
* *length* - 문자열의 전체 길이를 반환

```
var str = 'CodeStates';
console.log(str.length); // 10
```