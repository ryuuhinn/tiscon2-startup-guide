# Javaのインストール(Windows)

[JDK8(Java8)のインストール方法](http://javaworld.helpfulness.jp/post-24/)を参考に、**JDK8のインストール**及び**環境変数の設定**を行って下さい。

> **注意**
> * 下記サイトに記載されたjdkのバージョンは最新ではありません(jdk-8u5)。作業時の最新バージョンをダウンロードしてください。
> * 環境変数のパス設定には、自身がインストールした先のパスを設定してください。
> * コマンドプロンプトの開き方が分からない方は、[コマンドプロンプトの起動方法 | Windowsマシンの開発TIPS](tipsForWin.md#コマンドプロンプトの起動方法)を読んでみてください。
> * [環境変数の修正時は、必ず **追記** してください！](tipsForWin.md#環境変数pathの編集)

手順を終えたあとに、

```sh
> echo %JAVA_HOME%
C:\Program Files\Java\jdk1.8.0_91
> java -version
java version "1.8.0_91"
Java(TM) SE Runtime Environment (build 1.8.0_91-b14)
Java HotSpot(TM) 64-Bit Server VM (build 25.91-b14, mixed mode)
```
が実行できればOKです。またこの時、`java -version`で表示されたバージョンが、自分がインストールしたJavaのバージョンと一致していることを確認してください。
