# Javaのインストール(Windows)

## 前提条件

* [自分のPCのOSが何bitか知っていますか？](preparationForWin.md#自分のpcのbit数を知っておく)
* [ファイルの拡張子が表示されていますか？](preparationForWin.md#ファイルの拡張子表示)

## インストール

下記のサイトを参考に、**JDK8のインストール**及び**環境変数の設定**を行って下さい。

> **注意点**
> * 下記サイトに記載されたjdkのバージョンは最新ではありません(jdk-8u5)。作業時の最新バージョンをダウンロードしてください。
> * 環境変数のパス設定には、自身がインストールした先のパスを設定してください。
> * コマンドプロンプトの開き方が分からない方は、[コマンドプロンプトの起動方法 | Windowsマシンの開発TIPS](tipsForWin.md#コマンドプロンプトの起動方法)を読んでみてください。
> * [環境変数の修正時は必ず **追記** してください！](tipsForWin.md#環境変数pathの編集)すでに書かれた内容を消してしまうと、最悪の場合PCが起動しなくなります。

**[JDK8(Java8)のインストール方法](http://javaworld.helpfulness.jp/post-24/)**

## インストールできたら

[コマンドプロンプトを起動](tipsForWin.md#コマンドプロンプトの起動方法)して、

```sh
C:\Users\yourUserName> echo %JAVA_HOME%
C:\Program Files\Java\jdk1.8.0_91
```
というように `echo` コマンドが動くことと、
```sh
C:\Users\yourUserName> java -version
java version "1.8.0_91"
Java(TM) SE Runtime Environment (build 1.8.0_91-b14)
Java HotSpot(TM) 64-Bit Server VM (build 25.91-b14, mixed mode)
```
というように `java` コマンドが動くことが確認できればOKです。

またこの時、`java -version`で表示されたバージョンが、自分がインストールしたJavaのバージョンと一致していることを確認してください。
