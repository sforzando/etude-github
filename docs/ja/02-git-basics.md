# Gitの基礎

## 基本概念

| 用語 | 説明 |
| ---------- | ------------------------------------------------- |
| リポジトリ | Gitによって追跡されるプロジェクトフォルダ |
| コミット | 履歴に保存される変更のスナップショット |
| ブランチ | 独立した開発の分岐 |
| マージ | あるブランチの変更を別のブランチに統合すること |
| リモート | サーバー上にホストされているリポジトリのバージョン |

## 一般的なコマンド

### ステータスの確認

```bash
git status
```

### 変更のステージング

```bash
# 特定のファイルをステージング
git add README.md


# すべての変更をステージング
git add .
```

### 変更のコミット

このプロジェクトでは、[Commitizen](https://commitizen-tools.github.io/commitizen/) を使用して、
[Conventional Commits](https://www.conventionalcommits.org/) 形式を強制しています。

`git commit` の代わりに、以下を使用してください：

```bash
npm run commit
```

プロンプトに従って、適切な形式のコミットメッセージを入力するよう案内されます。

### 履歴の確認

```bash
git log --oneline
```

## 実践演習

1. `docs/` ディレクトリに `hello.md` という名前の新しいファイルを作成してください。
2. `npm run commit` を使用して、そのファイルをステージングし、コミットしてください。
3. [GitHub Flow](03-github-flow.md) に進んでください。
Inline corrections
