###ß Initialising Minima

Below shows you how to initialise your MiniDapp. This _must_ do this before you do anything else on the Minima blockchain.

```
  Minima.init( function( msg ) {

    console.log("Minima event", msg)

    if ( msg.event == "connected" ) {

      console.log("connected");
    }
  });
```
