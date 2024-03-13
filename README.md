<h1>Anti_Rounded_Corners_YouTubeUI</h1>
<p>このCSSファイルは、2022年10月ごろから導入されてしまったYouTubeの角丸UIをカクカクに戻すCSSファイルです。</p>
<p>このCSSファイルは、<a href=https://m.youtube.com>モバイルブラウザ版YouTube</a>を対象に作成されています。<a href=https://www.youtube.com>PCブラウザ版YouTube</a>では使えないのでご注意ください。</p>
<p>開発/動作検証環境(故に動作確認済み環境)は以下の通りです。</p>
<ul>
  <li>ブラウザ:Firefox Beta 124.0b5</li>
  <li>拡張機能(カスタムCSSを読みこむのに必要)：Stylus</li>
</ul>
<p>その他使用している(というか必要な)拡張機能</p>
<ul>
  <li>uBlock Origin(要素のブロック用に使用。)</li>
  <li>Tampermonkey(低評価数を表示するために使用。)</li>
</ul>

<h2>機能紹介</h2>
  <h3>YouTubeの角丸UIを抹消！！</h3>
    <p>このCSSを適用すると、モダンな角丸UIを以前のカクカクしたUIに戻すことが出来ます！！</p>
    <small><small><p>※バージョン16.10のYouTubeアプリ辺りをイメージして作成しています。</p></small></small>
    <img src=bin/ytui_back_demo1.png alt=適用前後比較 width=500px>
  <h3>高評価ボタンや低評価ボタンを以前のスタイルに近い状態に！！</h3>
    <p>高評価ボタンや低評価ボタンが以前の大きくて押しやすいボタンになります！！</p>
    <img src=bin/ytui_back_demo4.png alt=ボタン width=500px>
  <h3>チャンネル登録者数の表記が現行の簡略化されすぎた表記から以前のある程度の簡略化まで変更</h3>
    <p>現行の表記は数字(チャンネルによっては万などの表記もある)のみですが、このCSSを適用すると以前の「チャンネル登録者数○○人」という表記が復活します！！</p>
    <img src=bin/ytui_back_demo2.png alt=登録者数 width=500px>
    <small><small><p>※登録者数自体が１人単位で見えるようになるものではありません。</p></small></small>
  <h3>概要欄に素早くアクセス！！</h3>
    <p>タイトルをタップした後さらにもう１回タップしなきゃいけないのは意味不明！！ということでタイトルをタップしたらその時点で概要欄がすべて見えるように改良しました！！</p>
    <img src=bin/ytui_back_demo3.png alt=概要欄 width=500px>
