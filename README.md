# cabal-netx

<img src="./network.png">

A simple network visualization of cabal peer networks.

`npm install`

Run the peer sockets server using:

`node node peersocket.js --cabal [cabal key]`

Or use the included script:

```
chmod a+x invoke.sh
./invoke.sh
```



 that leverages the awesome [headless.js](https://github.com/cblgh/cabal-crepes/blob/master/headless.js) code in [cabal-crepes](https://github.com/cblgh/cabal-crepes) by [cblgh](https://github.com/cblgh). 

This code is based on web socket code adapted from the tutorial [here](https://github.com/processing/p5.js/wiki/p5.js,-node.js,-socket.io
)
https://github.com/processing/p5.js/wiki/p5.js,-node.js,-socket.io

using https://github.com/fkling/JSNetworkX

The headless module from https://github.com/cblgh/cabal-crepes



