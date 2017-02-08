# Herokuのアカウント作成とツールインストール(Windows)

下記サイトを参考に、herokuのアカウント作成、heroku toolbeltのインストールを行って下さい。

## 前提条件

* [自身のPCが何bitのOSか知っていますか？](preparationForWin.md#自分のPCのbit数を知っておく)

## アカウント作成

下記サイトの「herokuのアカウント作成」を参考に、アカウント作成を行って下さい。

## heroku toolbeltのインストール

引き続き下記サイトの「heroku toolbeltのインストール」を参考に、heroku toolbeltのインストール及び動作確認を行って下さい。  

> **注意点**
> * 「1.インストーラーのダウンロード」と「2.動作確認」まで行って下さい。
> * 「3. heroku認証確認」以降は実施しないでください。
> * 下記サイトでは、ダウンロードページのスクリーンショットが最新ではありません。
> * ダウンロードページの[Download and install]以下から自分のOSに合ったファイルをダウンロードしてください。
> * heroku toolbeltのインストーラを実行すると、[Git](https://git-scm.com/)も合わせてインストールされます。
> * [Git](https://git-scm.com/)インストール時、各種設定は全て初期状態のままで大丈夫です。

## [Git](https://git-scm.com/)の動作確認

[コマンドプロンプトを起動](tipsForWin.md#コマンドプロンプトの起動方法)して
```
git --version
```
と入力します。gitのバージョン情報が表示されれば正常にインストールできています。

自分のPCが32bitの場合、heroku toolbeltのインストーラ実行時にgitのインストールが失敗することがあります。
上記コマンドを実行してもバージョン情報が表示されない場合、gitのインストールに失敗しています。
[Git For Windows](https://git-for-windows.github.io/)のサイトからGitのインストーラをダウンロードして再度インストールしてください。

インストール時の設定は全て初期状態のままで大丈夫です。

**[herokuを使ってWebアプリケーションを公開しよう | dcom](http://www.dcom-web.co.jp/technology/heroku1/)**
