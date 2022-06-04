<h1>Pick <img src="https://img.shields.io/badge/-easy-7aad0c" alt="easy"/> <img src="https://img.shields.io/badge/-%23union-999" alt="#union"/> <img src="https://img.shields.io/badge/-%23built--in-999" alt="#built-in"/></h1>

```ts
type MyPick<T, K extends keyof T> = {
  [Key in K]: T[Key]
}
```
