# P2P Messenger Progressive Web Application (PWA)

A messaging application client for P2P Blockchain. See P2P Project at [P2P.im](https://P2P.im).

P2P is a decentralized anonymous messenger based on the blockchain system. It’s independent of any governments or corporations, and even developers due to the distributed network infrastructure that contains an open-source code.

The P2P blockchain system belongs to its users. Nobody can control, block, deactivate, restrict or censor accounts. Users take full responsibility for their content, messages, media, and goals and intentions of using the messenger.

Privacy is the main concept of P2P: neither phone numbers nor emails are required. Apps have no access to the contact list or geotags, IPs are hidden from chatters and paranoids can use [Tor app](http://P2P6457join2rxdkr2y7iqatar7n4n72lordxeknj435i4cjhpyd.onion).

All the messages are encrypted with the Diffie-Hellman Curve25519, Salsa20, Poly1305 algorithms and signed by SHA-256 + Ed25519 EdDSA. Private keys are never transferred to the network. The sequence of messages and their authenticity is guaranteed by the blockchain.

P2P includes crypto wallets for P2P (ADM), Bitcoin (BTC), Ethereum (ETH), Lisk (LSK), Dogecoin (DOGE) and Dash (DASH). Private keys for the wallets are derived from an P2P passphrase. You can export the keys and use them in other wallets.

This application deployed at [msg.P2P.im](https://msg.P2P.im) and [available as standalone apps](https://P2P.im/#adm-apps) for macOS, Windows and Linux. Feel free to run your own messenger using this code and Build Setup.

## Project setup

```
yarn install
```

Note: Lisk libraries may ask for specific Node.js version, you can ignore this with `yarn install --ignore-engines`.

### Compiles and hot-reloads for development

```
yarn run serve
```

### Compiles and hot-reloads self-signed https-server for development

```
yarn run https
```

### Compiles and minifies for production

```
yarn run build
```

### Lints and fixes files

```
yarn run lint
```

### Run electron version

```
yarn run electron:serve
```

### Build electron version

```
yarn run electron:build
```

[Download pre-build apps](https://P2P.im/#adm-apps) for macOS, Windows and Linux.

#### Note for Windows users

To build on Windows you must install build tools for windows, it is easier to do this with [windows-build-tools](https://github.com/felixrieseberg/windows-build-tools) npm package.

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
