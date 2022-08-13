# ファイルの説明

投稿の編集、削除機能を持たせたPHP掲示板です。

投稿内容はMySQLに保管されます。

## v1について

投稿の削除機能を、データベースから投稿の情報を完全に削除する方法で作成したバージョンです。

投稿が削除されたのか、バグで表示されていないのかが利用者からは分かりにくいのではないかと考えました。

## v2について

ｖ1の課題を解決するために、投稿の情報を完全に削除はせず、削除されたという情報を残すようにしたのがv2です。

投稿者による削除に加え、管理者のパスワードですべての投稿を削除できる機能も追加しました。
