---
layout: default
---

# Function pickRandom

Random pick a value from a one dimensional array.
Array element is picked using a random function with uniform distribution.


## Syntax

```js
math.pickRandom(array)
```

### Parameters

Parameter | Type | Description
--------- | ---- | -----------
`array` | Array | A one dimensional array

### Returns

Type | Description
---- | -----------
Number | One of the elements of the provided input array


## Examples

```js
var math = mathjs();

math.pickRandom([3, 6, 12, 2]);       // returns one of the values in the array
```


## See also

[random](random.html),
[randomInt](randomInt.html),
[distribution](distribution.html)


<!-- Note: This file is automatically generated from source code comments. Changes made in this file will be overridden. -->