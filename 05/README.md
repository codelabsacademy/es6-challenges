### Challenge 5

Use the destructuring syntax and the rest operator to define variables out of the object above: **title**, **salary** and an object **details** containing the job details namely format and experience

- Desired outcome:
```js
const job = {
  salary: 4000,
  format: "Full-Time",
  title: "Developer",
  experience: 4,
};

console.log(title) // 'Developer'
console.log(salary) // 4000
console.log(details) // {format: 'Full-Time', experience: 4}
```