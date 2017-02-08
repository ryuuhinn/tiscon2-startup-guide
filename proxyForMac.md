# プロキシの設定(Mac)

自分のPCが接続しているネットワークにプロキシが設定されている場合、別途設定が必要となります。

> **補足**
> * インターン当日はプロキシ設定が無い状態で行います。

## IntelliJでのプロキシ設定

1. IntelliJのWelcome画面(または `メニューバー > File` )からSettingsを選択します。
![IntelliJのプロキシ設定1](image/proxy_setting_IntelliJ1.png)

1. Settingsウィンドウが表示されるので、左のバーから `Appearance & Behavior > 一般 > HTTP Proxy` を選択します。

1. 「HTTPプロキシを使用する」を選択し、各自の設定を記載します。

1. 下部OKボタンを押下します。
![IntelliJのプロキシ設定2](image/proxy_setting_IntelliJ2.png)

## Heroku動作のためのプロキシ設定

### Terminal を起動する

`Terminal.app` を起動してください。

### プロキシ設定を設定ファイルに書き込む

```sh
echo 'export HTTP_PROXY=https://${your.proxy.host}:${your-proxy-port} >> ~/.bashrc'
echo 'export HTTPS_PROXY=https://${your.proxy.host}:${your-proxy-port} >> ~/.bashrc'
```

を実行してください。その時 `your.proxy.host` は事前にメモしたプロキシサーバのホスト名を、 `your-proxy-port` はポート番号に書き換えてください。

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
