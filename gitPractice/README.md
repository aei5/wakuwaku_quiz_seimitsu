# Git Practice

これは`Git`についての学習を行うためのリポジトリです．


ローカルのブランチを表示する
```
git branch
```

リモートのブランチを表示する
```
git branch -r
```

リモートの特定のブランチをpullする
```
git pull origin <local branch name>:<remote branch name>
```

branchの名前の変更
```
git branch -m <old branch name> <new branch name>
```

gitのコミット履歴を調べる
```
git reflog
```
-> `<commit id> HEAD@{num}`

戻り方
```
git reset HEAD@{num}
```

## 参考文献
[ローカルブランチに特定のリモートブランチをpull](https://qiita.com/hinatades/items/d47dec72a87c5fed50f7)
[ブランチの名前を変更する](https://docs.github.com/ja/repositories/configuring-branches-and-merges-in-your-repository/managing-branches-in-your-repository/renaming-a-branch)