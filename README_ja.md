# MaterialFox-Plus
***Firefox用のマテリアルデザインにインスパイアされたuserChrome.cssテーマ***

![Preview](https://user-images.githubusercontent.com/5405629/45172944-21d91900-b24a-11e8-8bc5-03814121b0de.png)
このテーマは、血と汗とコーヒーによって支えられています。もし気に入っていただけたなら、継続的な開発をサポートするために、ぜひ支援をご検討ください。

[![Buy fork source a coffee](https://typeling1578.github.io/MaterialFox-Plus/68747470733a2f2f73766773686172652e636f6d2f692f3859642e737667.svg)](https://www.buymeacoffee.com/n4ho5QX2l)

## 説明
Google の Material Design と最新の Google Chrome UI にインスパイアされたこのテーマは、Firefox を Material スタイルの Web ブラウザに変身させます。目的は、ブラウザをできるだけ Google Chrome に近いスタイルにすることです。

このテーマは userChrome.css であり、手動で Firefox のプロファイルに追加する必要があります。このテーマは特定のブラウザスタイルをオーバーライドします。現在のところ、メイン UI のみが影響を受けます。(設定ページなどは影響を受けません) 将来的には、より多くの UI の要素がスタイル化されるかもしれませんが、Mozilla がブラウザのコードを更新するため、より広い範囲を維持することは難しくなり、維持できなくなった場合、一部の UI スタイルを削除またはやり直す可能性があります。

## 対応バージョン
Firefoxの最新版か91ESRで動作します。

## インストール
1. chrome フォルダと user.js ファイルを Firefox のプロファイルディレクトリにコピーします。プロファイルディレクトリは、about:supportまたはabout:profilesにアクセスして確認してください。
2. よりChromeに近い使い方をしたい場合は、[おすすめの設定](#おすすめの設定)を参照してください。
3. Firefoxを再起動します。

### おすすめの設定
Chromeの切り抜きタブの動作を再現する。
* [about:config] ``browser.tabs.tabClipWidth`` を ``83`` に設定します (デフォルトは ``140``)

Chrome の HTTP での "安全ではありません" テキストを表示する。
* [about:config] ``security.insecure_connection_text.enabled`` を ``true`` に設定します。

## 注意
* Linuxは正式にはサポートされなくなりましたが、試してみることはできます。Linuxに取り組みたい場合は、気軽にプルリクを送ってください。
* 一部のカスタマイズ設定は動作しないかもしれません（コンパクトやタッチの密度など）
* カスタムテーマによっては、アドレスバーと衝突する可能性があります。
* 透明度を使用した一部のテーマが動作しない場合があります。
