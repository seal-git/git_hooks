# git hooks
.git/hooksに置くhooksスクリプト集。ついでにgitignoreも。
https://qiita.com/seal_qiita/items/7d595bd54b39eec9ea4b

prepare-commit-msg
----
コミットメッセージの先頭に日付を追加する。

post-commit
----
commit後に自動pushが走る。コミットメッセージを`test`にすると走らない。
`git config push.default current` をしておく。
