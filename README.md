# テストネットICBファセット用コントラクト

オレオレテストネットコントラクトなので、公式ではありません。

いったんRinkebyやRopstenでデプロイしてます

ICBに関しては下記(公式)

[https://icb.jcam.co.jp/](https://icb.jcam.co.jp/)

# 使い方

1..env.sampleを.envに変更して、mnemonicやエンドポイントを設定

2.ローカルのノード（Ganache等）やRinkebyやRopstenのInfura等を用意

3.パッケージをインストール

```
npm install
```

4.デプロイ
```
truffle migrate (--network rinkeby)
```


# (オレオレ)テストネットICBコントラクト情報

Rinkeby : 0x5446E3481e3fe4b3082067145A47d7a0F09d5E1A ([Etherscan](https://rinkeby.etherscan.io/address/0x5446E3481e3fe4b3082067145A47d7a0F09d5E1A))

Ropsten : 0x7725419506d38F1c0f6Bee88960385b0b50586f7([Etherscan](https://ropsten.etherscan.io/address/0x7725419506d38F1c0f6Bee88960385b0b50586f7))

