## IoT & Blockchain Workshop

Buyamón, Puerto Rico, March 17 2018 ([EventBrite][event-brite])

* [IoT Workshop GitHub][iot-github]
* [Engine-4][engine-4]
* [Obsidis Consortia][obsidis-consortia]

[iot-github]: https://github.com/j0x0j/ethereum-iot-workshop
[engine-4]: https://engine-4.com
[obsidis-consortia]: http://obsidisconsortia.org
[event-brite]: https://www.eventbrite.com/e/43175658557

### Setup

* [Raspberry Pi Setup](raspberry-pi)

### Interesting Projects

* [Gitcoin][gitcoin] - Funded GitHub bounties w/ETH
* [Web3][web3] - Ethereum JS API
* [Mastering Ethereum][mastering-ethereum] - Mastering Ethereum Book
* [The Evolution of Trust][evolution-of-trust] - The Evolution of Trust

### SSH to rpi

```plain
ssh pi@<ip>
password: raspberry
```

### Sync geth on rpi to Rinkeby network

```bash
geth --syncmode "light" --rinkeby
```

[evolution-of-trust]: http://ncase.me/trust
[gitcoin]: https://gitcoin.co
[mastering-ethereum]: https://github.com/ethereumbook/ethereumbook
[web3]: https://github.com/ethereum/web3.js
