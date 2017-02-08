# プロキシの設定(Windows)

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

環境変数に自身のプロキシについて設定する必要があります。
1. スタート > コンピューターを右クリック > プロパティ > システムの詳細設定を選択してください。
![Herokuのプロキシ設定1](image/proxy_setting_Heroku1.png)

1. システムのプロパティウィンドウの詳細設定 > 環境変数を選択します。
![Herokuのプロキシ設定2](image/proxy_setting_Heroku2.png)

1. ユーザー環境変数内の新規ボタンを押下してください
![Herokuのプロキシ設定3](image/proxy_setting_Heroku3.png)

1. 変数名に`HTTP_PROXY`、変数値に各自の設定を入力し、OKを選択します。
![Herokuのプロキシ設定4](image/proxy_setting_Heroku4.png)

1. 同様に変数名に`HTTPS_PROXY`、変数値に各自の設定を入力し、OKを選択します。
![Herokuのプロキシ設定5](image/proxy_setting_Heroku5.png)

1. 環境変数ウィンドウ内のOKボタンを押下してください。
![Herokuのプロキシ設定6](image/proxy_setting_Heroku6.png)

1. スタート > すべてのプログラム > アクセサリ > コマンドプロンプトを選択してください。

1. コマンドに`set`を入力し、先程入力した設定が反映されていることを確認してください。
![Herokuのプロキシ設定7](image/proxy_setting_Heroku7.png)
