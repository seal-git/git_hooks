# git hooks
.git/hooksに置くhooksスクリプト集。ついでにgitignoreも。

prepare-commit-msg
----
コミットメッセージの先頭に日付を追加する。

post-commit
----
commit後に自動pushが走る。コミットメッセージを`test`にすると走らない。