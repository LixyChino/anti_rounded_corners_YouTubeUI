<h1>Anti_Rounded_Corners_YouTubeUI</h1>
<p>このCSSファイルは、2022年10月ごろから導入されてしまったYouTubeの角丸UIを以前のカクカクUIに戻すCSSファイルです。</p>
<p>このCSSファイルは、<a href=https://m.youtube.com>モバイルブラウザ版YouTube(m.youtube.com)</a>を対象に作成されています。<a href=https://www.youtube.com>PCブラウザ版YouTube(www.youtube.com)</a>では使えないのでご注意ください。</p>
<p>開発/動作検証環境(故に動作確認済み環境)は以下の通りです。</p>
<ul>
  <li>ブラウザ:Firefox Beta 124.0b5</li>
  <li>拡張機能(カスタムCSSを読みこむのに必要)：Stylus</li>
  <p>(v1.4までは開発にStylebotを使用)</p>
  <li>スマホ：Galaxy S22</li>
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
    <img src=bin/ytui_back_demo1.png alt="適用前後比較" width=500px>
  <h3>高評価ボタンや低評価ボタンを以前のスタイルに近い状態に！！</h3>
    <p>高評価ボタンや低評価ボタンが以前の大きくて押しやすいボタンになります！！</p>
    <small><small><p>※v1.5から実装しています。</p></small></small>
    <img src=bin/ytui_back_demo4.png alt="ボタン" width=500px>
  <h3>チャンネル登録者数の表記が現行の簡略化されすぎた表記から以前のある程度の簡略化まで変更</h3>
    <p>現行の表記は数字(チャンネルによっては万などの表記もある)のみですが、このCSSを適用すると以前の「チャンネル登録者数○○人」という表記が復活します！！</p>
    <img src=bin/ytui_back_demo2.png alt="登録者数" width=500px>
    <small><small><p>※登録者数が1万人以上のチャンネルにおいて、登録者数自体が1人単位で見えるようになるものではありません。</p></small></small>
    <small><small><p>※v1.3から実装しています。</p></small></small>
  <h3>概要欄に素早くアクセス！！</h3>
    <p>タイトルをタップした後さらにもう1回タップしなきゃいけないのは意味不明！！ということでタイトルをタップしたらその時点で概要欄がすべて見えるように改良しました！！</p>
    <img src=bin/ytui_back_demo3.png alt="概要欄" width=500px>
    <small><small><p>※v1.5から実装しています。</p></small></small>
<h2>導入方法</h2>
  <p>0.あらかじめFirefox BetaにStylusとTampermonkeyをインストールします。</p>
  <ol>
    <li>「Releases」から最新のファイルをダウンロードする。</li>
    <li>ファイルエディターからでもなんでもいいのでダウンロードしたzipファイルを解凍する。</li>
    <li>解凍したら「anti_rounded_corners_YouTubeUI_v1.x」というtxtファイルができます。</li>
    <li>「anti_rounded_corners_YouTubeUI_v1.x」というtxtファイルの中にcssが入っているので、内容をすべて選択し、クリップボードにコピーする。</li>
    <li>Firefox Betaを開いて、右上の点３つ→「アドオン」→「Stylus」→「管理」→「スタイルを新規作成」の順にタップする。(この段階でデスクトップサイトを有効化しておいてください。そうしないと「スタイルに追加」が上手く押せないんですよね)</li>
    <li>「インポート」をタップして、「Mozilla形式のコードを貼り付ける」というものが出たら、そこに先ほどコピーしたcssをペーストする。</li>
    <li>「スタイルに追加」をタップして、左上の「保存」をタップする。</li>
    <li><a href=https://greasyfork.org/en/scripts/436115-return-youtube-dislike/code>こちらのリンク</a>からReturn YouTube Dislike(Tampermonkey版)のインストール画面へ行く。</li>
    <li>「Install this sctipt」をタップする。</li>
    <li>「インストール」をタップする。</li>
  </ol>
    <p>以上で導入は終了です。お疲れさまでした。</p>
  <h2>更新方法</h2>
      <p>本CSSには自動アップデート機能はございませんので手動でのアップデートをお願いします。</p>
      <ol>
        <li>「Releases」から最新のファイルをダウンロードする。</li>
        <li>ファイルエディターからでもなんでもいいのでダウンロードしたzipファイルを解凍する。</li>
        <li>解凍したら「uBlock」フォルダと「anti_rounded_corners_YouTubeUI_v1.x」というtxtファイルができます。</li>
        <li>「anti_rounded_corners_YouTubeUI_v1.x」というtxtファイルの中にcssが入っているので、内容をすべて選択し、クリップボードにコピーする。</li>
        <li>Firefox Betaを開いて、「Stylus」→ 右上の点３つ→「アドオン」→「Stylus」→「管理」→Anti_Rounded_Corners_YouTubeUIを記載したスタイルの名前をタップします(この段階でデスクトップサイトを有効化しておいてください。)。</li>
          <img src=bin/css_apply_1.jpg width=500px>
        <li>「インポート」をタップします。</li>
          <img src=bin/css_apply_2.jpg width=500px>
        <li>するとこのような入力画面が表示されます。ここに先ほどコピーしたCSSファイルの内容を貼り付けてください。</li>
          <img src=bin/css_apply_3.jpg width=500px>
        <li>完了したら「スタイルを上書き」をタップしてください。</li>
          <img src=bin/css_apply_4.jpg width=500px>
        <li>最後に「保存」をタップして完了です！！</li>
      </ol>
  <h2>注意点</h2>
  <ul>
    <li>通知バーはモバイルブラウザ版YouTubeの仕様上見ることが出来ません。</li>
    <li>全画面表示にするとブラウザを再起動するまでホームの下のタブが消えます。</li>
    <li>事前にアンビエントモード(シネマティックライティング)をオフにしておく必要があります。(遅くてもuBlock Originにマイルールを追加する前までには)</li>
   <li>素人が自分用に作ったものなのでバグ多めです。たまに修正しますが、完全に直せるわけではないのでご了承ください。</li>
    <li>まともな仕上がりになっているのはv1.5以降です。それ以前は実質ベータ版だとお考え下さい(v0.xとかじゃないけど)。</li>
    <li>現時点ではダークモード以外には対応していません。ライトモードを使用している方ごめんなさい。</li>
    <li>仕様上、2本以上の広告が流れる際の「1/2」などの表示には対応していません。ご了承ください。</li>
    <li>このカスタムCSSは日本語版向けに制作されています。他の言語には対応していません。ごめんなさい。This CSS file is only available in Japanese.</li>
    <li>低評価の表示にはAnarios & JRWR様が制作した「Return YouTube Dislike」を使用しています。</li>
    <li>もしかしたら環境によっては動かないかもしれません。ゆるして</li>
  </ul><br>
<h2>バージョン1.19以前の導入方法</h2>
  <p>バージョン1.20以降では要素のブロックに「display:none;」を使用していますが、バージョン1.19以前の場合uBlock Originを使用して要素をブロックしていました。<br>その為最新バージョンのインストール工程に加えてuBlock Originのセットアップ工程も必要です。</p>
  <p>0.あらかじめFirefox BetaにStylusとuBlock OriginとTampermonkeyをインストールします。</p>
  <ol>
    <li>「Releases」から最新のファイルをダウンロードする。</li>
    <li>ファイルエディターからでもなんでもいいのでダウンロードしたzipファイルを解凍する。</li>
    <li>解凍したら「uBlock」フォルダと「anti_rounded_corners_YouTubeUI_v1.x」というtxtファイルができます。</li>
    <li>「anti_rounded_corners_YouTubeUI_v1.x」というtxtファイルの中にcssが入っているので、内容をすべて選択し、クリップボードにコピーする。</li>
    <li>Firefox Betaを開いて、右上の点３つ→「アドオン」→「Stylus」→「管理」→「スタイルを新規作成」の順にタップする。(この段階でデスクトップサイトを有効化しておいてください。そうしないと「スタイルに追加」が上手く押せないんですよね)</li>
    <li>「インポート」をタップして、「Mozilla形式のコードを貼り付ける」というものが出たら、そこに先ほどコピーしたcssをペーストする。</li>
    <li>「スタイルに追加」をタップして、左上の「保存」をタップする。</li>
    <li>右上の点３つ→「アドオン」→「uBlock Origin」→「ダッシュボードを開く」をタップ</li>
    <li>上の「マイフィルター」をタップする。</li>
    <li><img src=bin/ublock_demo_1.jpg alt="インポート" width=50px>このアイコンをタップする。</li>
    <li>「ublock_arcytui_v1.x」という名前のtxtファイルを選択する。</li>
    <li>マイルールが追加されたのを確認したら左上のチェックボタンをタップする。</li>
    <li><a href=https://greasyfork.org/en/scripts/436115-return-youtube-dislike/code>こちらのリンク</a>からReturn YouTube Dislike(Tampermonkey版)のインストール画面へ行く。</li>
    <li>「Install this sctipt」をタップする。</li>
    <li>「インストール」をタップする。</li>
  </ol>
    <p>以上で導入は終了です。お疲れさまでした。</p>
<h2>uBlock Originを使用しているバージョンの注意点</h2>
  <ul>
    <li>uBlock Originの「フィルターリスト」の以下の項目(主に広告ブロッカー)は必ず無効にしてください。 </li>
    <li>uBlock filters - Ads</li>
    <li>AdGuard - Ads</li>
    <li>AdGuard - Mobile Ads</li>
    <li>EasyList</li>
    <li>AdGuard Tracking Protection</li>
    <li>AdGuard URL Tracking Protection</li>
    <li>Peter Lowe's Ad and tracking server list</li>
    <li>jp: AdGuard Japanese</li>
    <p>これら以外にも広告ブロッカーだと思うものは無効にしておくことを推奨します。なぜなら、YouTubeは広告ブロッカーを使用していると再生をブロックしてくるからです。(モバイルブラウザ版はやったことないのでわからないけど少なくともPCブラウザ版では摘発されました)</p>
  </ul>
