# Git Practice

これは`Git`についての学習を行うためのリポジトリです．



## Setting
グローバルに自分のユーザネームとメールアドレスを登録しておく．
登録の仕方
```
# user.name
git config --global user.name "User Name"

# user.email
git config --global user.email "User Email Address"
```


## Branch
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

ファイルの追加
```
git add <file name>
git add <folder name>
```

commit
```
git commit -m "変更内容を簡潔に書く"
```

push
```
git push origin <branch name>
```

pushまでの流れ
1. ファイルの追加
2. commitをする
3. pushする

## 参考文献
[ローカルブランチに特定のリモートブランチをpull](https://qiita.com/hinatades/items/d47dec72a87c5fed50f7)<br>
[ブランチの名前を変更する](https://docs.github.com/ja/repositories/configuring-branches-and-merges-in-your-repository/managing-branches-in-your-repository/renaming-a-branch)