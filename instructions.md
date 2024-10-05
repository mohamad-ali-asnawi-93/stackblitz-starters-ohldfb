# Creating a statement  

  What if we want to say:
  ```
  My full name is Haris Samingan
  ```
  How do we do this?

  With template literal string, we can!
  ```js
  const first_name = 'Charlie'
  const last_name = 'Poof'
  console.log(`My full name is ${first_name} ${last_name}`)
  ```
  Which will print:
  ```
  My full name is Charlie Poof
  ```
  
  ## Exercise

1. Declare a constant variable, `name_first`, and assign the string value `'Kopee'` to it.
2. Declare a constant variable, `name_last`, and assign the string value `'Dis' `to it.
3. Use the `console.log()` function to print a string that combines `name_first` and `name_last` using template literals. The string should read: "People call me Kopee Dis".


Console:

```
People call me Kopee Dis
```

Do your best!

<details>
<summary>Answer</summary>

```javascript
const name_first = 'Kopee';
const name_last = 'Dis';
console.log(`People call me ${name_first} ${name_last}`);
```
</details>

