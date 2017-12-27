# 自作コマンド
## コマンド一覧
|ファイル名|コマンド名|説明|
|:--------|:--------|:----|
|test.sh|testcommand|`Hello World!`とだけ表示するコマンド|
|morning.sh|mor|朝起きたあとのコマンドで, ChatWork,NewsPicks,GoogleNews,NHK Newsを開く|
|dmm.sh|dmm|dmm英会話を始める前のコマンドで, dmm英会話のホームページ,翻訳ページを2つ, 検索ページを開く |

## 導入手順
1. `bin`ディレクトリをダウンロードし, ホームディレクトリ直下に置く.
2. `bin`ディレクトリのパスを通す  
```
$ PATH="~bin:$PATH"
```
3. `bin`ディレクトリ内の全てのファイルに実行属性を与える.
```command
$ ls -l [file名]
$ chmod 755 [file名]
$ ls -l [file名]
```
4. `.bashrc`にエイリアスを書く.
5. `.bashrc`を実行する.  
```command
$ source .bashrc
```

## 新規作成手順
1. 導入手順を行う.
2. `bin`ディレクトリに新規shファイルを作成する.
3. ファイル作成後, そのファイルに実行属性を与える.
4. `bashrc`にエイリアスを書く.

## 参考
[自作コマンドの作り方](https://qiita.com/b4b4r07/items/129f11c80aa34479b764)
[Linux初心者のシェルスクリプト](https://qiita.com/lrf141/items/6c01d2f7afff79cd7286)
[Linux入門 「パスを通す」とは](https://qiita.com/Naggi-Goishi/items/2c49ea50602ea80bf015)
