# 風量計算 PWA

## iPadへの追加
1. このフォルダ一式をHTTPSで公開します。
2. iPadのSafariで公開URLを開きます。
3. 共有 →「ホーム画面に追加」。
4. 「風量計算」をタップしてアプリとして起動します。

## 重要
PWAはSafariのファイル表示（file://）ではなく、HTTPSで配信される必要があります。
GitHub PagesなどのHTTPSホスティングに置けば利用できます。

アプリ本体は index.html、manifest.webmanifest、sw.js、アイコン2個です。
