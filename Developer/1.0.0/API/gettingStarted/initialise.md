## Initialising Minima

### Example

```
  Minima.init( function( msg ) {

    console.log("Minima event", msg)

    if ( msg.event == "connected" ) {

      console.log("connected");
    }
  });
```
