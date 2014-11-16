---
layout: default
---

<h1 id="function-dot">Function dot <a href="#function-dot" title="Permalink">#</a></h1>

Calculate the dot product of two vectors. The dot product of
`A = [a1, a2, a3, ..., an]` and `B = [b1, b2, b3, ..., bn]` is defined as:

   dot(A, B) = a1 * b1 + a2 * b2 + a3 * b3 + ... + an * bn


<h2 id="syntax">Syntax <a href="#syntax" title="Permalink">#</a></h2>

```js
math.dot(x, y)
```

<h3 id="parameters">Parameters <a href="#parameters" title="Permalink">#</a></h3>

Parameter | Type | Description
--------- | ---- | -----------
`x` | Array &#124; Matrix | First vector
`y` | Array &#124; Matrix | Second vector

<h3 id="returns">Returns <a href="#returns" title="Permalink">#</a></h3>

Type | Description
---- | -----------
Number | Returns the dot product of `x` and `y`


<h2 id="examples">Examples <a href="#examples" title="Permalink">#</a></h2>

```js
math.dot([2, 4, 1], [2, 2, 3]);       // returns Number 15
math.multiply([2, 4, 1], [2, 2, 3]);  // returns Number 15
```


<h2 id="see-also">See also <a href="#see-also" title="Permalink">#</a></h2>

[multiply](multiply.html),
[cross](cross.html)


<!-- Note: This file is automatically generated from source code comments. Changes made in this file will be overridden. -->