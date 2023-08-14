# 第１章　Dockerとは？
- アプリケーションやOSの開発・配備を行うための`コンテナ`を利用した基盤ソフトウェア
- Docker自体は`コンテナ`を稼働させるエンジンとなるソフトウェアであるため”コンテナエンジン”と呼ばれる
- `Dockerイメージ`を利用することで多様な開発環境や本番の実行環境を容易に構築できる
- `Dockerイメージ`を世界中で共有し、Webサービスを提供する`DockerHub`と呼ばれるレジストリ（保管庫）サービスが利用できる
<dl>
  <dt>コンテナ</dt>
  <dd>ホストOS上で独立したプロセスとして実行されるアプリケーション環境</dd>
  <dd>OSの基本コマンドやアプリケーションの実行バイナリ、ライブラリなどの実行環境全体を
  <br>パッケージ化し、それらをOSの分離された空間で実行する技術</dd>
</dl>

![Alt text](https://image.itmedia.co.jp/ait/articles/1609/01/wi-dockerforwindows02.png)

<dl>
  <dt>Dockerイメージ</dt>
  <dd>コンテナの生成に必要なファイルシステム</dd>
  <dd>実行ファイル、ライブラリ、コンテナの実行の際に起動させたいコマンドなどが含まれる</dd>
  <dd>１つのイメージから、大量のコンテナを素早く起動でき、かつ容易にスケールできる</dd>
</dl>

![Alt text](https://www.kagoya.jp/howto/wp-content/uploads/differencedockerimg.png.webp)

<dl>
  <dt>DockerHub</dt>
  <dd>アプリケーションやサービスコンテナの構築と配信を行う、Dockerイメージのパブリッククラウドサービス</dd>
  <dd>手元にあるDockerイメージをDockerHubにアップロードすることも可能</dd>
</dl>

![Alt text](https://image.itmedia.co.jp/ait/articles/1408/26/docker4_fig1.jpg)

## ソフトウェア開発におけるメリット
- アプリケーション単位での分離、開発環境の作成と廃棄を容易に行える
⇨インターネットで提供されるサービスの迅速な開発や柔軟な対応が行える

## 運用管理上のメリット
- アプリケーションの開発と実環境への素早い展開と運用の両立が可能となる
