# ブランチ間差分

git 3 dots diffでブランチ間の差分を表示する。git 2 dots diffはファイルの差分を表示する。

```git
# git 3 dots diff
git diff hoge...fuga

# git 2 dot diff
git diff hoge..huga
# 以下はgit 2 dot diffと同じ結果になる
dgit diff hoge huga
```

https://zenn.dev/waruby/articles/a89f9ba30b28fd

# 単語単位の差分

`--word-diff`オプションは単語単位の差分を表示する。オプションなしは行単位での差分を表示する。

```git
# メインブランチとカレントブランチの単語単位の差分を表示する
git diff --word-diff main...HEAD
```

https://qiita.com/tamanobi/items/74282b166ef4eb4c007b