# Array

- Built in datastructure
- Collection values
- Zero-indexed
- Can contain mix of values (heterogenious elements)
- Resizable

---

## Adding Elements into Array

- we use push (array.push(element)) method to add an element at the END of an array

- we use array.unshift(element) method to add the elements at the beginning of an array

- To remove elements at the end, we use array.pop() method
- To remove elements at beginning, we use array.shift()

---

## Print array elements

- we use for-of loop

```js
    const arr = [1, 2, 'JS','ES6', true]
    for(const item of arr) {
        console.log(item)
    }
```
