# IntelliJのインストール(Windows)

## 前提条件



## インストール

1. https://www.jetbrains.com/idea/#chooseYourEdition のDOWNLOADボタンから、**Community** のバージョンを選んでダウンロードしてください。
1. ダウンロードできたインストーラーを起動して、表示される手順に従ってインストールを進めてください。よくわからない項目はそのままYESを選択してください。

IntelliJを日本語化したい場合は、[IntelliJ IDEA 日本語化 | Qiita](http://qiita.com/makoto2468/items/6abf614b82cab865b745)が参考になります。

## プラグインの設定

1. IntelliJを起動し、Configure > Settings を選択します。
![プラグイン設定1](image/plugin_setteing1.png)

1. Settingsウィンドウが表示されるので、左のバーからPluginsを選択し、 `Browse repositories...` ボタンを押下します。
![プラグイン設定2](image/plugin_setteing2.png)

1. 検索バーに `Lombok` と入力し、Lombok Pluginを選択します。
右側に表示されるInstallボタンを押下してください。
検索結果が表示されない場合はプロキシの問題である可能性があります。
プロキシの設定([Windowsマシン](proxyForWin.md) / [Macマシン](proxyForMac.md))を参照してください。
![プラグイン設定3](image/plugin_setteing3.png)

1. 同様に、検索バーに`Jackson`と入力し、Jackson Generator Pluginを選択します。
右側に表示されるInstallボタンを押下し、**IntelliJを再起動**してください。


![プラグイン設定4](image/plugin_setteing4.png)
