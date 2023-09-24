# FileCoinRepo
FileCoinを調査するためのリポジトリです。

## Filecoin用のboxの始め方

```bash
truffle unbox filecoin
```

## Running Filecoin Ganache

```bash
npx ganache filecoin
```

うまくいけば下記のように出力される。

```bash
Lotus RPC listening on 127.0.0.1:7777
IPFS  RPC listening on 127.0.0.1:5001
```

### Filecoin Network用のブロックチェーンエクスプローラー起動

```bash
cd filecoin-network-inspector && yarn && yarn start
```

[http://localhost:3000](http://localhost:3000)にアクセス

### 参考文献
1. [hardhat starter kit](https://github.com/mashharuki/fevm-hardhat-kit)
2. [チートシート](https://github.com/filecoin-project/awesome-filecoin/blob/main/fvm.md)
3. [Truffle filecoin Box](https://trufflesuite.com/boxes/filecoin/)
4. [filecoin_nft_starter_demo](https://filecoin-nft-starter.vercel.app/)
5. [filecoin_nft_starter](https://github.com/DeveloperAlly/filecoin_nft_starter)