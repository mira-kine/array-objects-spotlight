# Array methods

## Lecture

### Arrays

- arrays aren't copys, they are references
- you should not change your state, they should be immutable
- arrays and objects are mutable however
- you can modify arrays -> it did not create a new array, it modified the original array

* primitives create a copy of that primitive
* you can use spread operator to contain the same values but be technically different objects instead of modifiying the original array. For example!

```
let a= [1, 2, 3];
let b = [...a];
a.push(4);
console.log(`a: ${a}, b: ${b}`);
what will come out is a: 1, 2, 3, 4, b: 1, 2, 3
```

- know the difference between assigning values to a new object array vs referencing
- you ALWAYS want to be creating a new state, rather than updating the new object

### Snapshot

- rendering what you will be seeing from the component
- pass in props that you will be using for that component so you can see if it works

* when running the test
  - npm i
  - npm run test:watch

### Destructuring
