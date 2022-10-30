# Useful Regex
If `t` is the text to process...
```js
t.replaceAll('\n',' ').match(/(\w+ )?\d+:\d+(-\d+)?/g)
```
