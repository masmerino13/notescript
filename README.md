# notescript

## Array to Object with ES6

```
const arrayList = [1, 3, 6, 8];

const objectList = arrayList.reduce((obj, i) => {
 obj[i] = true;
 return obj;
}, {});
```
