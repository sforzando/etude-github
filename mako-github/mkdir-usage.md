# GitHub作業用コマンド・チートシート

> 1. *issueのタイトルと状態を明記する*

- タイトル: **Create `mako-github` directory**
- 説明: `etude-github`の中に`mako-github`という名前のディレクトリが存在している

↓作業するリポジトリに移動する

```bash
cd ~/Workspace/github.com/sforzando/etude-github
```

`etude-github`←ここへいく

↓main branchに移動します

```bash
git sw main
```

↓リモートリポジトリの最新状態を取得し、その情報をmainに反映させる

```bash
git fetch
git pull origin main
```

↓新しいbranchを作って移動

```bash
git switch -c [ブランチ名]
```

feat: `028_feature_directory`

↓ディレクトリーを作る

```Bash
mkdir ディレクトリ名
```

feat:`mako-github`

> 2.ファイル`mkdir-usage.md`を作る

- タイトル:Create`mkdir-usage.md`
- 説明:`mako-github`ディレクトリの中に`mkdir-usage.md`というファイルが存在する

↓`mako-github`へ移動

```bash
cd ~/Workspace/github.com/sforzando/etude-github
```

↓ファイルを作る

```bash
touch ファイル名
```

feat:`mkdir-usage.md`

↓変更されたファイル確認

```bash
git status
```

↓全ての変更をステージングする

```bash
git add .
```

↓確認する

```bash
git status
```

↓コミットする

```bash
git commit -m "コミット名"
```

feat: `Create mako-github and mkdir-usage.md`
なにをしたか書く

↓確認する

```bash
git status
```

↓pushする

```bash
git push origin HEAD
```

feat: `028_feature_directory`

↓GitHub上でMerge pull request が完成した後

↓メイン移動

```bash

git switch main

```

↓最新化

```bash

git pull origin main

```

↓古いローカルブランチを消す

```bash

git branch -d [使っていたブランチ]

```

↓チェック

```bash

git status

```

終わり
