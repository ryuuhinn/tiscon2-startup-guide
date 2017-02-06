# Javaのインストール(Mac)

[MacでのJavaのインストール方法 | java.com](https://java.com/ja/download/help/mac_install.xml)の手順に従ってください。

手順を終えたあとに、

```sh
> echo $JAVA_HOME
/Library/Java/JavaVirtualMachines/jdk1.8.0_91.jdk/Contents/Home
> java -version
java version "1.8.0_91"
Java(TM) SE Runtime Environment (build 1.8.0_91-b14)
Java HotSpot(TM) 64-Bit Server VM (build 25.91-b14, mixed mode)
```
が実行できればOKです。またこの時、`java -version`で表示されたバージョンが、自分がインストールしたJavaのバージョンと一致していることを確認してください。
