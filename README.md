## Project
-----
SF Bitcoindev build a determinist web wallet forked from Carbon Wallet. Anyone can download and create a browser-only wallet to send and receive bitcoins. 


## Features
-----
- Web based wallet
- BIP 32 Deterministic keys
- Uses Bitcoinjs-lib
- Testnet Switch with seeded bitcoin
- Uses Helloblock.js for testnet faucet


## Installation
-----
`npm install`
`bower install`

## Usage
-----
### Use: Generate Static html
1. grunt
2. open app/app.html

### Develop: Serve html & watch for changes
1. grunt serve
2. goto http://localhost:8282/app.html
3. Modify js/*.js or jade/*.jade and grunt will recreate .min.js and
   .html accordingly

### Use Testnet
1. grunt serve
2. http://127.0.0.1:8282/app.html?testnet=1



## Notes
-----
The following files are not being brought in by bower

    mnemonic.js
    qrcode.js
    electrum.js
    bitcoinjs-min.js

## Security Warnings
This software is alpha software. Please make sure to run only on a clean web browser.


## Authors
-----
[Sidney Zhang](https://github.com/sidazhang)
[Larry Kang](https://github.com/lkang)
[Srinivasan Sriram](https://github.com/ssr1ram)
[Taariq Lewis](https://github.com/taariq)

## Contributing
Feel free to send pull requests to have your project/startup listed here.


## License
This web wallet is free and open-source software released under the MIT license.



