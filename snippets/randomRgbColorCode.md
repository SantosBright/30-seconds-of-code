---
title: randomRgbColorCode
tags: array,color,rgb,intermediate
---

Generates a random rgb color code.

-   Use `Math.random()` to generate decimal numbers from `0` - `256`.
-   Use Math.floor() to get the largest integer less than or equal to the decimal numbers
-   Return a concatinated of the values in rgb color code format.

```js
const randomRgbColorCode = () => {
    let r = Math.floor(Math.random() * 256);
    let g = Math.floor(Math.random() * 256);
    let b = Math.floor(Math.random() * 256);
    return `rgb(${r}, ${g}, ${b})`;
};
```

```js
const randomColor = randomRgbColorCode();
console.log(randomColor); // rgb(20, 200, 97)
```
