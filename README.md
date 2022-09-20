# samples

EV3の動作確認用のサンプルです。

## サンプルアーカイブを展開する

* `samples.zip` をEV3RTをインストールしたディレクトリの中の `hrp3\sdk\` で展開する。
* `workspace` の並びに、下記のディレクトリ構成が得られる。

``` shell
├─ workspace
└─ samples
　　　├── sample00
　　　├── sample01
　　　├── sample02
　　　└── util
```

## sample00をビルドする

* MSYS2 のターミナルを起動して、EV3RTの中の `samples` ワークスペースへ移動する。
* 下記のようにしてsample00をビルドする。

``` shell
make app=sample00
```

* `samples` ディレクトリに `app` ファイルができる。
* 自分のファイルだとわかるよう、転送の前に `kubo-samp00` のように自分の名前とプログラムの名前がわかるようにしておくと、他の人に上書きされないで済む。

## sample00を転送して、実行する

* TOPPERSの「サンプルアプリケーションのビルドと実行」を参照して、動的ローディング形式用の実行ファイルの転送方法を使って `app` ファイルを転送する。
* 転送できたら、実行する。


## sample01, sample02も試す

実施手順は同じ。
