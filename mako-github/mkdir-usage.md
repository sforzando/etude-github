# ディレクトリーを作る

> 1. *issueのタイトルと状態を明記する*

- タイトル: **Create `mako-github` directory**
- 説明: `etude-github`の中に`mako-github`が存在している

↓作業するディレクトリーに移動する

```bash
cd ~
```

例:Users/mako/Workspace/github.com/sforzando/etude-github/mako-github
`etude-github`←ここへいく

↓メインにいることを確認

```bash
g sw main
```

↓最新の状態を取り込む

```bash
g pull origin main
```

↓新しいbranchを作って移動

```bash
g sw -c [ブランチ名]
```

例: `028_feature_directory`

↓ディレクトリーを作る

```Bash
mkdir ディレクトリ名
```

例:`mako-github`

> 2.ファイル`mkdir-usage.md`を作る

- タイトル:Create`mkdir-usage.md`
- 説明:`mako-github`ディレクトリの中に`mkdir-usage.md`というファイルが存在する

↓`mako-github`へ移動

```bash
cd ~
```

例:Users/mako/Workspace/github.com/sforzando/etude-github/mako-github

↓ファイルを作る

```bash
touch ファイル名
```

例:`mkdir-usage.md`

↓確認する

```bash
g s
```

↓ステージングする

```bash
g add .
```

↓確認する

```bash
g s
```

↓コミットする

```bash
g commit -m "コミット名"
```

例: `Create mako-github and mkdir-usage.md`
なにをしたか書く

↓確認する

```bash
g s
```

↓pushする

```bash
g push origin 使っているブランチ名
```

例: `028_feature_directory`

↓プルリクを書く

↓メイン移動

```bash

g sw main

```

↓最新化

```bash

g pull origin main

```

↓古いブランチを消す

```bash

g branch -d [使っていたブランチ]

```

↓チェック

```bash

g s

```

終わり
