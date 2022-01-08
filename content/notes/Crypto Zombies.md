---
title: "Crypto Zombies"
---

- A **contract** is the fundamental building block of etherium applications - all variables and functions belong to one.

*Empty contract*

```
contract HelloWorld {

}
```

**State variables** are permanently stored in contract storage. This means they're written to the Ethereum blockchain. Think of them like writing to a DB.

**Structs** allow you to create more complicated data types that have multiple properties.

```js
struct Person { 
	uint age; 
	string name; 
}
```