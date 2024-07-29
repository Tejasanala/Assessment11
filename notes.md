# reduce

can go from array to any datatype.

reduce(takes function as argument)

```js
.reduce((acc,curr)=>acc+curr,0)
```

2nd argument is initial value of accumulater.

> final value will be the accumulator value.

what map did, reduce can also do.

```js
const sum=[1,7,3,10,5].reduce((acc,curr)=> acc.concat(curr\*2),[])
```

```js
const sum = [1, 7, 3, 10, 5].reduce((acc, curr) => acc.concat(curr2), []);
```

## Mutable methods

push : Adds one or more elements to the end of an array.

```js
const fruits = ["Apple", "Banana", "Cherry"];
const newLength = fruits.push("Date", "Elderberry");
console.log(newLength); // Output: 5
console.log(fruits); // Output: ['Apple', 'Banana', 'Cherry', 'Date', 'Elderberry']
```

pop : Removes the last element from an array.

> If the array is empty when pop() is called, it returns undefined.

```js

```

shift: Removes the first element from an array.

unshift : Adds one or more elements to the beginning of an array.

sort : Sorts the elements of an array in place and returns the sorted array.

reverse : Reverses the order of the elements of an array in place.

## Immutable methods:

concat(): Returns a new array combining the array on which it is called with other arrays and/or values.

> a3=a1.concat(a2)

filter() :Returns a new array containing elements that pass a test specified

map() : Returns a new array with the results of calling a provided function on every element in the calling array.

slice() : Returns a shallow copy of a portion of an array into a new array object.

every() : Tests whether all elements in the array pass the test implemented by the provided function

```js
const numbers = [1, 2, 3, 4, 5];
const allGreaterThanZero = numbers.every((num) => num > 0);
console.log(allGreaterThanZero); // Output: true
```

some() :Tests whether at least one element in the array passes the test implemented by the provided function.

```js
const numbers = [1, 2, 3, 4, 5];
const someGreaterThanThree = numbers.some((num) => num > 3);
console.log(someGreaterThanThree); // Output: true
```

List of array methods :

           immutable     mutable (modify the orginal array)   return type

concat ✅ ❌ array

slice ✅ ❌ array

filter ✅ ❌ array

map ✅ ❌ array

reduce ✅ ❌

forEach ✅ ❌

every ✅ ❌ boolean

some ✅ ❌ boolean

push ❌ ✅ number(it returns the length of array)

pop ❌ ✅ any(the element removed from the end of the array)

shift ❌ ✅ any(the element removed from the begining of the array)

unshift ❌ ✅ number(it returns the length of array)

splice ❌ ✅ Array(an array containing the elements removed from the original array)

sort ❌ ✅ array

reverse ❌ ✅ array

---

# METHODS

Array Methods

---

<v-clicks>

## Mutable methods

`push` : Adds one or more elements to the end of an array.

```js
const fruits = ["Apple", "Banana", "Cherry"];
const newLength = fruits.push("Date", "Elderberry");
console.log(newLength); // Output: 5
console.log(fruits); // Output: ['Apple', 'Banana', 'Cherry', 'Date', 'Elderberry']
```

`pop` : Removes the last element from an array.

> If the array is empty when pop() is called, it returns undefined.

`shift`: Removes the first element from an array.
</v-clicks>

---

## layout: center

<v-clicks>

`unshift` : Adds one or more elements to the beginning of an array.

`reverse` : Reverses the order of the elements of an array in place.

</v-clicks>

---

<v-clicks>

## Immutable methods:

`concat()`: Returns a new array combining the array on which it is called with other arrays and/or values.

```js
> a3=a1.concat(a2)
```

`filter()` :Returns a new array containing elements that pass a test specified

`map()` : Returns a new array with the results of calling a provided function on every element in the calling array.

`slice()` : Returns a shallow copy of a portion of an array into a new array object.

</v-clicks>

---

<v-clicks>

`every()` : Tests whether all elements in the array pass the test implemented by the provided function

```js
const numbers = [1, 2, 3, 4, 5];
const allGreaterThanZero = numbers.every((num) => num > 0);
console.log(allGreaterThanZero); // Output: true
```

`some()` :Tests whether at least one element in the array passes the test implemented by the provided function.

```js
const numbers = [1, 2, 3, 4, 5];
const someGreaterThanThree = numbers.some((num) => num > 3);
console.log(someGreaterThanThree); // Output: true
```

</v-clicks>

---

List of Mutable array methods :

             immutable     mutable (modify the orginal array)        return type

concat ✅ ❌ array

slice ✅ ❌ array

filter ✅ ❌ array

map ✅ ❌ array

reduce ✅ ❌ any

every ✅ ❌ boolean

some ✅ ❌ boolean

---

List of IMMutable array methods :

push ❌ ✅ number(it returns the length of array)

pop ❌ ✅ any(the element removed from the end of the array)

shift ❌ ✅ any(the element removed from the begining of the array)

unshift ❌ ✅ number(it returns the length of array)

splice ❌ ✅ Array(the elements removed from the original array)

sort ❌ ✅ array

reverse ❌ ✅ array

</v-clicks
