# GitHubのアカウント作成

## アカウント作成
下記サイトを参考に、**GitHubのアカウント作成**を行って下さい。

GithubはシステムエンジニアのSNSであり、GitHubアカウントはSEにとって名刺のようなものです。一生モノのアカウント名なので、気を付けて作成してください。

[【GitHub アカウントの作成方法】](http://fnya.cocolog-nifty.com/blog/2014/01/github-185e.html)

## [Git](https://git-scm.com/)の設定

今後の作業内容をあなたのGitHubアカウントに紐付けられるようにします。

IntelliJを起動して、 `Shift` キーを2回連続で押します。すると検索窓が表示されるので、

![検索窓](image/install_intellij_add_git_config_1.png)

そこに `terminal` と入力します。

![terminalを探す](image/install_intellij_add_git_config_2.png)

`Terminal` が検索結果に出てくるので、選択してください。するとコマンドプロンプトの画面が表示されるので
```sh
git config user.name GitHubのユーザー名
git config user.email GitHubのメールアドレス
```
を入力してください。
