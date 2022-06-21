#JS
__________________________
## Arrow function
```js
const myName = () => {
     return;
    }

const myName2 = argument => {
     return;
    }

const multiply = number => number * 2;

```

## Spread operator ...

```js
const newArray = [...oldArray, 1, 2];

const newObject = {...oldObject, newProp: 5}
```

## Rest operator ...
Pass that many argumnents to function as you want

 ```js
 function sortArgs(...args) {
     return args.sort()
 }
 ```

```js
const filter = (...args) => {

    return args.filter(el => el == '1');
```

# Descructuring ...

```js
[a,b] = ['Hello', 'Max']
console.log(a)
console.log(b)

{name} = {name: 'Max', age: 28}
```

```js
const numbers = [1, 2, 3]
[num1, num2] = numbers
console.log(num1, num2)
```

## Functions


`map()`  => https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map

`find()`  => https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/find

`findIndex()`  => https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/findIndex

`filter()`  => https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter

`reduce()`  => https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/Reduce?v=b

`concat()`  => https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/concat?v=b

`slice()`  => https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/slice

`splice()`  => https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/splice



## Imports and exports
In React projects (and actually in all modern JavaScript
projects), you split your code across multiple JavaScript
files - so-called modules. You do this, to keep each file/
module focused and manageable.
To still access functionality in another file, you need `export`
(to make it available) and `import` (to get
access) statements.
You got two different types of
exports: default (unnamed) and named exports:

default => ` export default ...;`

named => `export const someData = ...;`

You can import default exports like this:

`import someNameOfYourChoice from './path/to/
file.js';`

Surprisingly, someNameOfYourChoice is totally up to you.
Named exports have to be imported by their name:

`import { someData } from './path/to/file.js';`

A file can only contain one default and an unlimited amount
of named exports. You can also mix the one default with
any amount of named exports in one and the same file.
When importing named exports, you can also import all
named exports at once with the following syntax:

`import * as upToYou from './path/to/file.js';`

upToYou is - well - up to you and simply bundles all
exported variables/functions in one JavaScript object. For
example, if you `export const someData = ... (/path/
to/file.js )` you can access it on upToYou like
this: `upToYou.someData`.

__________

# React

```js

```

