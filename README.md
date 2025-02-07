I was unable to retrieve the main code file `index.js` from your repository. However, I can help you draft an initial README based on the information I have.

## README.md

### Introduction
```
# HashMap
A project in which I create my own personal hashmap in JavaScript.

This project aims to implement a custom HashMap data structure from scratch. The HashMap is designed to efficiently store key-value pairs and allow for fast retrievals and updates.
```

### Code Breakdown
```
## Code Breakdown

### The Main File
The main file of this project is `index.js`. This file contains the implementation of the HashMap class and its associated methods.

### HashMap Class
The `HashMap` class is the core of this project. It includes the following methods:
- `set(key, value)`: Adds a key-value pair to the HashMap.
- `get(key)`: Retrieves the value associated with the given key.
- `delete(key)`: Removes the key-value pair from the HashMap.
- `has(key)`: Checks if the HashMap contains the given key.
- `clear()`: Clears all key-value pairs from the HashMap.
- `size()`: Returns the number of key-value pairs currently in the HashMap.

### Example Usage
Here's a brief example of how to use the HashMap class:

```javascript
const hashMap = new HashMap();

hashMap.set('name', 'John Doe');
console.log(hashMap.get('name')); // Output: John Doe

hashMap.set('age', 30);
console.log(hashMap.size()); // Output: 2

hashMap.delete('name');
console.log(hashMap.has('name')); // Output: false

hashMap.clear();
console.log(hashMap.size()); // Output: 0
```
```

You can refine and expand this README based on the actual implementation details of your `index.js` file.
