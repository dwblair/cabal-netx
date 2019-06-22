# cabal-netx

<img src="./network.png">

A simple network visualization of [cabal](https://cabal.chat/) peer networks.

## Installation

`npm install`

## Usage

First, the peer sockets server using:

`node node peersocket.js --cabal [cabal key]`

Or use the included script:

```
chmod a+x invoke.sh
./invoke.sh
```

Then, open `_site/index.html` in a browser.

## Credits

[cabal-netx](https://github.com/dwblair/cabal-netx) leverages:

- the awesome [headless.js](https://github.com/cblgh/cabal-crepes/blob/master/headless.js) code in [cabal-crepes](https://github.com/cblgh/cabal-crepes) by [cblgh](https://github.com/cblgh), in order to connect to a cabal;

- the tutorial [here](https://github.com/processing/p5.js/wiki/p5.js,-node.js,-socket.io
) for web-socket code;

- and the fantastic [jsnetworks](https://github.com/fkling/JSNetworkX) library.
