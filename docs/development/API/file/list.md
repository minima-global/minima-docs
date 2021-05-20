# file.list

List the files in a directory

```js
Minima.file.list('myFile.txt', function(result) {
    if ( result.exists ) {
        Minima.log('List ' + JSON.stringify(result));
    } else {
        Minima.log('List failed ' + JSON.stringify(result));
    }
});
```
