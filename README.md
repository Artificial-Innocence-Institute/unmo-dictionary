# unmo-dictionary is 何

Ruby向けの書籍「[恋するプログラム][book]」で解説されているチャットボットの`Unmo`をPythonに移植した[sandmark/unmo][releases]用の学習済み辞書セットを提供するためのリポジトリです。

## インストール

`git`による`clone`か、またはパッケージを[ダウンロード][unmo-dictionary]して展開してください。その後`Unmo`の辞書ディレクトリに配置してください。

    git clone https://github.com/Artificial-Innocence-Institute/unmo-dictionary.git
	cp -R unmo-dictionary/dics/* ~/.unmo/dics/*

### 注意

上記の方法でインストールすると、今まで`Unmo`で学習した辞書を上書きしてしまいます。
バックアップを取ってから辞書をインストールすることをお勧めします。

## 謝辞

- [恋するプログラム][book]の著者、秋山 智俊さん
- python3版Unmo開発者、sandmarkさん

[releases]: https://github.com/sandmark/unmo/releases
[book]: http://amzn.to/2kYltNz
[python3]: https://www.python.org/downloads/
[unmo-dictionary]: https://github.com/Artificial-Innocence-Institute/unmo-dictionary.git