# about
このproject:es(eaglecraft.bySchool)は学校のパソコンでする向けです。家庭で遊ぶ場合などはhttps://mi-go45.github.io/eagecraft/
がおすすめです。

## password
[リンク] (https://mi-go45.github.io/es/)

※パスワードは `bob` です。


## 使い方 / 仕組み
ハッシュ化されたパスワードをそのままディレクトリ名に利用し、URL の存在の有無で認証を行なっています。

この方法のデメリットとして URL が知られる / ディレクトリリストが取得される という方法によっても突破されてしまうため、URL の共有やサーバの設定に注意しましょう。

ハッシュ化には SHA-256 を使用しており、入力に対するハッシュ値の確認には [check.html](https://higurashi-takuto.github.io/password/check.html) が利用できます。ここで取得できるハッシュ値をディレクトリ名に付けましょう。

## 使用リポジトリ
https://github.com/higurashi-takuto/password ←簡易パスワードのレポジトリ
https://github.com/U5KUN/Eaglercraft-Japanese ←Eaglercraft日本語版のレポジトリ
