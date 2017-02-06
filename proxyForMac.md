# プロキシの設定(Mac)

自分のPCが接続しているネットワークにプロキシが設定されている場合、別途設定が必要となります。
インターン当日はプロキシ設定が無い状態で行います。

## 自分がプロキシを使用しているのか確認する

1. `システム環境設定 > ネットワーク` で自分が使用しているインターネット接続手段を選択します。
1. その手段の `「詳細...」ボタン > プロキシ` タブを開き、設定が書いてあればプロキシを使用しています。
1. プロキシサーバのホスト名とポート番号をメモしておいてください。
1. 以下の手順を追って、プログラミングに使うツールにプロキシの設定を追加してください。

## Mavenでのプロキシ設定

Mavenのプロキシ設定は、[Apache Maven3 (3.2.5) インストール手順](http://weblabo.oscasierra.net/install-maven-32-windows/)の「手順.5」を参照してください。

## IntelliJでのプロキシ設定

1. IntelliJのWelcome画面(または `メニューバー > File` )からSettingsを選択します。
![IntelliJのプロキシ設定1](image/proxy_setteing_IntelliJ1.png)

1. Settingsウィンドウが表示されるので、左のバーから `Appearance & Behavior > 一般 > HTTP Proxy` を選択します。

1. 「HTTPプロキシを使用する」を選択し、各自の設定を記載します。

1. 下部OKボタンを押下します。
![IntelliJのプロキシ設定2](image/proxy_setteing_IntelliJ2.png)

## Heroku動作のためのプロキシ設定

### Terminal を起動する

`Terminal.app` を起動してください。

### プロキシ設定を設定ファイルに書き込む

```sh
echo 'export HTTP_PROXY=https://${your.proxy.host}:${your-proxy-port} >> ~/.bashrc'
echo 'export HTTPS_PROXY=https://${your.proxy.host}:${your-proxy-port} >> ~/.bashrc'
```

を実行してください。その時 `your.proxy.host` は

他の*shをを使っている方は自身の環境に合った設定ファイルに設定を追加してください。

### 適用確認

`Terminal.app` を一度閉じてから再度開き、

```sh
> echo $HTTP_PROXY
https://${your.proxy.host}:${your-proxy-port}
> echo $HTTPS_PROXY
https://${your.proxy.host}:${your-proxy-port}
```

というような表示が出ればOKです。
