# [Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array)

## Properties

### [length](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/length)

[🍐, 🍏, 🍓, 🍌, 🍇].length = 5

## Methods

### [from](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/from)

Array.from('🍐🍏🍓🍌🍇') = [🍐, 🍏, 🍓, 🍌, 🍇]

### [isArray](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/isArray)

Array.isArray([🍐, 🍏, 🍓, 🍌, 🍇]) = ✔

### [concat](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/concat)

[🐮, 🐷].concat([🍓, 🍏, 🍌]) = [🐮, 🐷, 🍓, 🍏, 🍌]

### [copyWithin](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/copyWithin)

[🍐, 🍏, 🍓, 🍌, 🍇].copyWithin(2)       = [🍐, 🍏, 🍐, 🍏, 🍓]  
[🍐, 🍏, 🍓, 🍌, 🍇].copyWithin(1, 3)    = [🍌, 🍓, 🍌, 🍇, 🍇]  
[🍐, 🍏, 🍓, 🍌, 🍇].copyWithin(0, 3, 4) = [🍌, 🍏, 🍓, 🍌, 🍇]

### [every](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/every)

[🍌, 🍌, 🍌, 🍌, 🍌].every(vegetable => 🍌) = ✔  
[🥔, 🥕, 🍓, 🍏, 🍌].every(vegetable => 🍌) = ✘

### [fill](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/fill)

[🥔, 🥕, 🍐, 🍏, 🍓].fill(🍌, 2, 4) = [🥔, 🥕, 🍌, 🍌, 🍓]  
[🥔, 🥕, 🍐, 🍏, 🍓].fill(🍌, 1)    = [🥔, 🍌, 🍌, 🍌, 🍌]  
[🥔, 🥕, 🍐, 🍏, 🍓].fill(🍌)       = [🍌, 🍌, 🍌, 🍌, 🍌]

### [filter](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter)

[🍕, 🍝, 🌭, 🍔, 🍟].filter(ingredient => 🇮🇹) = [🍕, 🍝]

### [find](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/find)

[🥒, 🥔, 🥕, 🍓, 🍏].find(vegetable => fruit) = 🍓  
[🥒, 🥔, 🥕, 🍓, 🍏].find(vegetable => cloth) = undefined

### [findIndex](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/findIndex)

[🥒, 🥔, 🥕, 🍓, 🍏].findIndex(vegetable => 🍓)    =  3  
[🥒, 🥔, 🥕, 🍓, 🍏].findIndex(vegetable => cloth) = -1

### ⚠ [flat](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/flat)

### ⚠ [flatMap](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/flatMap)

### [forEach](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/forEach)

[🎂].forEach(🍰 => console.log(🍰))

### [includes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/includes)

[🐱, 🐶, 🦇, 🐷, 🐮].includes(🐷) = ✔  
[🐱, 🐶, 🦇, 🐷, 🐮].includes(🐔) = ✘

### [indexOf](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/indexOf)

[🐜, 🐪, 🦇, 🦆, 🦇].indexOf(🦇)    =  2  
[🐜, 🐪, 🦇, 🦆, 🦇].indexOf(🦇, 2) =  4  
[🐜, 🐪, 🦇, 🦆, 🦇].indexOf(🐔)    = -1

### [join](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/join)

[🌬, 🔥, 🌧].join()   = 🌬,🔥,🌧  
[🌬, 🔥, 🌧].join(🐔) = 🌬🐔🔥🐔🌧

### [lastIndexOf](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/lastIndexOf)

[🐜, 🐪, 🦇, 🦆, 🦇].lastIndexOf(🦇)    =  4  
[🐜, 🐪, 🦇, 🦆, 🦇].lastIndexOf(🐪)    =  1  
[🐜, 🐪, 🦇, 🦆, 🦇].lastIndexOf(🐔)    = -1  
[🐜, 🐪, 🦇, 🦆, 🦇].lastIndexOf(🦇, 3) =  4

### [map](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map)

[🌽, 🐷, 🐔, 🦐, 🌾].map(sourceMaterial => 🍳) = [🍿, 🥓, 🍗, 🍤, 🍚]

### [pop](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/pop)

[🥔, 🥕, 🍐, 🍏, 🍓].pop() = [🥔, 🥕, 🍐, 🍏]

### [push](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/push)

[🐷, 🐐, 🐑].push([🐮, 🐔]) = [🐷, 🐐, 🐑, 🐮, 🐔]

### [reduce](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/Reduce)

[🐮, 🐷].reduce((accumulator, ingredient) => 🔪, initialValue) = 🍖

### [reverse](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/reverse)

[🥔, 🥕, 🍐, 🍏, 🍓].reverse() = [🍓, 🍏, 🍐, 🥕, 🥔]

### [shift](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/shift)

[🐷, 🐐, 🐑, 🐮, 🐔].shift() = [🐐, 🐑, 🐮, 🐔]  
[].shift() = undefined

### [slice](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/slice)

[🐜, 🦇, 🐪, 🦆, 🐘].slice()      = [🐜, 🦇, 🐪, 🦆, 🐘]  
[🐜, 🦇, 🐪, 🦆, 🐘].slice(2)     = [🐪, 🦆, 🐘]  
[🐜, 🦇, 🐪, 🦆, 🐘].slice(0, -2) = [🐜, 🦇, 🐪]  
[🐜, 🦇, 🐪, 🦆, 🐘].slice(-2)    = [🦆, 🐘]

### [some](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/some)

[🥒, 🥔, 🥕, 🍓, 🍏].some(vegetable => fruit) = true  
[🥒, 🥔, 🥕, 🍄, 🥗].some(vegetable => fruit) = false

### [sort](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/sort)

[1, 30, 4, 21].sort() = [1, 21, 30, 4]

### [splice](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/splice)

[🥒, 🥕, 🍄, 🥗].splice(1, 0, 🥔) = [🥒, 🥔, 🥕, 🍄, 🥗]  
[🥒, 🥕, 🍄, 🥗].splice(3, 1, 🥔) = [🥒, 🥕, 🍄, 🥔]

### [toString](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/toString)

[🥒, 🥔, 🥕, 🍄, 🥗].toString() = '🥒, 🥔, 🥕, 🍄, 🥗'

### [unshift](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/unshift)

[🐷, 🐐, 🐑].unshift(🐮, 🐔) = [🐮, 🐔, 🐷, 🐐, 🐑]
