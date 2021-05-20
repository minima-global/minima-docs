# file.coopy

Copy a file.

```js
Minima.file.copy('myFile.txt', 'myNewFile.txt', function(result) {
    if ( result.exists ) {
        Minima.log('Copied ' + JSON.stringify(result));
    } else {
    Minima.log('Copy failed ' + JSON.stringify(result));
    }
});
```
