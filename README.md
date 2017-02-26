# 環境構築手順

ここでは、[tiscon2](https://github.com/tiscon/tiscon2)を実際に動かしてプログラミングができるようになるためのいくつかのステップを紹介します。

## 前提条件

* インターネット接続した状態で行って下さい。
* 作業想定時間は2~3時間です。
* このステップが終わらないまま参加すると、当日の作業時間が減ってしまいます！わからないことがあった時に問い合わせる時間も考慮に入れて、余裕をもって準備を始めてください。

## 自分のPCでプログラミングする時の便利設定

* [Windowsマシンで開発を始める前に](doc/preparationForWin.md)
* [Macマシンで開発を始める前に](doc/preparationForMac.md)

## ツールのインストール

### Java

プログラミング言語のJavaでプログラミングするのに必要なソフトウェアをインストールします。
これをインストールすると、自分のPCでJavaのプログラムを動かすことができるようになります。

* [Windowsマシン](doc/installJavaWin.md)
* [Macマシン](doc/installJavaMac.md)

### Maven

Javaで書いたプログラムを簡単に動せるようにするためのソフトウェアです。ビルドツールと呼ばれるツールの一種です。

* [Windowsマシン](doc/installMavenWin.md)
* [Macマシン](doc/installMavenMac.md)

### Git

書いたプログラムを、変更履歴とともに保存するソフトウェアです。このようなツールはバージョン管理ツールと呼ばれます。

* [Windowsマシン](doc/installGitWin.md)
* [Macマシン](doc/installGitMac.md)

### IntelliJ IDEA

Javaのプログラムを書くのに便利なすごいメモ帳です。これ1つでJavaのプログラム開発に関わる様々な作業をまとめて実行できる優れものです。

* [Windowsマシン](doc/installIntelliJWin.md)
* [Macマシン](doc/installIntelliJMac.md)

## 外部サービスの準備

### Heroku

作ったアプリケーションを世界に公開するためのサイトです。こういうサービスはPaaSと呼ばれたりします。

* [Herokuの準備](doc/heroku.md)

### GitHub

Gitリポジトリのホスティングサービスです。

> Gitに関して深く学びたい場合は、下記サイトを見てみてください。
> * [Gitの基本 | サルでもわかるGit入門](http://www.backlog.jp/git-guide/intro/intro1_1.html)
> * [ギットクエスト](http://unit8.net/gq/)

* [GitHubの準備](doc/github.md)

## tiscon2のソースコードを手に入れる

* [tiscon2をforkする](doc/forkTiscon2.md)

## 動作確認

自分のPCでWebアプリケーションが正常に動作するかを確認します。

* [Windowsマシン](doc/operationCheckWin.md)
* [Macマシン](doc/operationCheckMac.md)

## オンライン上での動作確認

[Heroku](http://heroku.com/) 上でtiscon2が動くことを確認しましょう。

* [Heroku上で動かしてみる](doc/herokuCheck.md)

## 作業に行き詰った場合

* [作業に行き詰った場合](doc/whenYouAreStuck.md)
