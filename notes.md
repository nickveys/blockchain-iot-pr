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
