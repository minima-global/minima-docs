# file.delete

Delete a file.

```js
Minima.file.delete('myFile.txt', function(result) {
    if ( result.exists ) {
        Minima.log('Deleted ' + JSON.stringify(result));
    } else {
        Minima.log('Delete failed ' + JSON.stringify(result));
    }
});
```
