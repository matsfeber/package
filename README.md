# package exercise

A package to censor cursewords 

### install 

Install the package with this code 

```sh
npm install ./censor
```

### use

To use the package always require it first with

```js
var censor = require ('censor');
```

### functions

This fucntion gets a string(cursewords) and changes them. You have 3 different functions.

1. Change the vowels of string with a asteriks or an other specified character.
```js
censor.vowel('fuck') 
 ```
 This would change **fuck** to **f*ck** 
 
 ```js
censor.vowel('fuck',@) 
 ```
 This would change **fuck** to **f@ck** 
 
 2. Change every letter of the string except for the first and last with an asteriks or an other specified character.
 
  ```js
censor.inner('fuck',%) 
 ```
This would change **fuck** to **f%%k** 

3. Change every letter into grawlix (typographic symbols).

```js
censor.grawlix('fuck') 
 ```
This would change **fuck** to **@&!@** 
