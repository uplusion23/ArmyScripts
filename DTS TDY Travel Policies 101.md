Open chrome developer tools (or the equivalent), and enter the following code. The correct answer will be highlighted in red.

```javascript
setInterval(() => {
  let correct = document.querySelectorAll('input.true');
  if (correct.length > 0) {
    correct[0].setAttribute('style', 'border: 1px solid red');
  } else {
    correct = document.querySelector('img.true');
    correct.setAttribute('style', 'border: 1px solid red');
  }
}, 500);
```
