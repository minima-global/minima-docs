# Initialising Minima

Below shows you how to initialise your MiniDapp. You _must_ get _connected_ before you do anything else on the Minima blockchain.

```js
Minima.init( function( msg ) {
  if ( msg.event == "connected" ) {
    Minima.log("connected");
  }
});
```
