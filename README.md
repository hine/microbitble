# Web Bluetooth APIでMac上のChromeとmicro:bitをBLE接続するデモ

## これは何?

詳しくはQiitaのエントリーを御覧ください。
https://qiita.com/yokmama/items/5522fabfb5b9623278e2

## 使い方

1. 上記Qiitaエントリーを参考に、micro:bitにファームウェアを書き込む
1. ダウンロードする

    ```
    git clone https://github.com/hine/microbitble.git
    ```
    もしくは[]ダウンロードリンク](https://github.com/hine/microbitble/archive/master.zip)でZIPファイルをダウンロードして展開する。

1. index.htmlをchromeで開く
1. micro:bitの電源を入れる
1. Mac上のchrome上の画面で「CONNECT」ボタンをクリックし、接続するmicro:bitを選択すると接続されます。
1. 接続後はmicro:bitを動かすと加速度センサーの値が変化し、画面上のAccel_x〜zの値が変化します。
1. micro:bitのA/Bボタンを押すとAlertダイアログで押したボタンを表示します。
1. 「DISCONNECT」ボタンで切断します。

## で、これどうすればいいの？！

assets/js/microbitble.jsがmicro:bitと接続するサンプルコードになっています。これを参考に是非色々なWebアプリケーションを作ってください！
