# wioSwitch

## Description

[Wio Node](https://www.seeedstudio.com/Wio-Node-p-2637.html)と[Grove - Relay](https://www.seeedstudio.com/Grove---Relay-p-769.html)を組み合わせて，PCやiPad，iPhoneなどのブラウザ上からコントロールするためのHTMLファイル．

[BDアダプタ](https://www.ablenetinc.com/battery-device-adapter-aa-aaa-size)とwioSwitchを組み合わせるとPCやiPad，iPhoneから電池式のおもちゃのon/offができるようになります．

インターネットを介して繋がっているので，Bluetoothのようなペアリングは不要で電源を入れればすぐに使えるようになります．

***DEMO:***

## Requirement

- [Wio Node](http://ssci.to/2799)
- [Grove - Relay](http://ssci.to/807)
- 3.5mmモノラルピンプラグがついた電線 [たとえばこんなやつ](http://www.marutsu.co.jp/pc/i/107911/)
- Webブラウザ

## Usage

1. Wio Nodeをセットアップする．セットアップ方法は設定用のアプリ（[iOS用](http://apple.co/2iu6mop)，[Android用](http://bit.ly/2iu3KqZ)）がわかりやすく指示してくれるので，それにしたがって行いましょう．英文ですが公式サイトにも[セットアップ手順](http://wiki.seeed.cc/Wio_Node/)があります．

2. Groove Relayを1つだけつなぐ場合，PORT0と基板に刻印されている方に繋いでおきましょう．

3. 設定用のアプリで自分のWio Nodeのアクセストークンを調べます．（「View API」から調べられます）

4. Groove Relayを1つだけつなぐならwio_1.htmlを，2つならwio_2.htmlを編集して使用します．

5. img要素のsrc属性を適当な画像のURLに差し替えます．「PORT0 用の画像」のようなコメントがついています．

6. 各PORT用の単語を適当なものに書き換えます．「PORT0 用の文字列」のようなコメントがついています．

7. [ACCESS_TOKEN]の部分を3で調べておいた32桁のアクセストークンに書き換えます．

8. できあがったHTMLファイルをブラウザで開いて使用します．（適当なサーバにおけば，iPadやiPhoneのようなデバイスからでも使えます）

## Author

[@YamaguchiToshi](https://twitter.com/YamaguchiToshi)

## License

MIT
