# GitHub作業用コマンド・チートシート

> 1. *issueのタイトルと状態を明記する*

- タイトル: **Create `mako-github` directory**
- 説明: `etude-github`の中に`mako-github`という名前のディレクトリが存在している

---

`cd ~/Workspace/github.com/sforzando/etude-github`-作業するリポジトリに移動する

`etude-github`←ここへいく

`git sw main`-main branchに移動します

`git fetch`-リモートリポジトリの最新状態を取得

`git pull origin main`-その情報をmainに反映させる

`git switch -c [ブランチ名]`-新しいbranchを作って移動

feat: `028_feature_directory`

`mkdir ディレクトリ名`-ディレクトリーを作る

feat:`mako-github`

> 2.ファイル`mkdir-usage.md`を作る

- タイトル:Create`mkdir-usage.md`
- 説明:`mako-github`ディレクトリの中に`mkdir-usage.md`というファイルが存在する

`mako-github`へ移動

`cd ~/Workspace/github.com/sforzando/etude-github`

`touch ファイル名`-ファイルを作る

feat:`mkdir-usage.md`

`git status`-変更されたファイル確認


`git add .`-全ての変更をステージングする

`git status`-確認する

`git commit -m "コミット名"`-コミットする

feat: `Create mako-github and mkdir-usage.md`
なにをしたか書く

`git status`-確認する

`git push origin HEAD`-pushする
↓
GitHub上でMerge pull request が完成した後
↓
`git switch main`-メイン移動

`git pull origin main`-最新化

`git branch -d [使っていたブランチ]`-古いローカルブランチを消す

`git status`-チェック

終わり
