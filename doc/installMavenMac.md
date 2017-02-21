# Mavenのインストール(Mac)

## 前提条件

* [Terminalを起動](tipsForMac.md#terminalの起動方法)して `java -version` とコマンドを入力した時、結果が返ってきますか？

## [brew](http://brew.sh/index_ja.html)のインストール

[Terminalを起動](tipsForMac.md#terminalの起動方法)して
```sh
> which brew
/usr/local/bin/brew
```
というように表示されたらスキップしてください。 `brew not found` と言われた場合は以下のステップを実行してください。
```sh
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
を実行して終了したらOKです。処理が終了した時に明らかにエラーと分かるような赤い文字などが出ていたら、エラー内容と共にインターン実施担当者まで問い合わせてください。

## mavenのインストール

自分のMacで [Terminalを起動](tipsForMac.md#terminalの起動方法) して以下を実行します。

```
brew install maven
```

処理が終了した時に :beer: のアイコンが出ていたらOKです。

## インストールできたら

[Terminalを起動](tipsForMac.md#terminalの起動方法)して
```sh
mvn --version
Apache Maven 3.3.9 (bb52d8502b132ec0a5a3f4c09453c07478323dc5; 2015-11-11T01:41:47+09:00)
Maven home: /usr/local/Cellar/maven/3.3.9/libexec
Java version: 1.8.0_91, vendor: Oracle Corporation
Java home: /Library/Java/JavaVirtualMachines/jdk1.8.0_91.jdk/Contents/Home/jre
Default locale: ja_JP, platform encoding: UTF-8
OS name: "mac os x", version: "10.11.3", arch: "x86_64", family: "mac"
```
というように `mvn` コマンドが動くことが確認できればOKです。

またこの時表示されたバージョンが、自分がインストールしたMavenのバージョンと一致していることを確認してください。
