# Git と GitHub の始め方

## 準備環境

始める前に、以下のものがインストールされていることを確認してください

- [Git](https://git-scm.com/)
- [VS Code](https://code.visualstudio.com/)
- [GitHub](https://github.com) アカウント
- [ghq](https://github.com/x-motemen/ghq)

## Git の設定

コミットがあなた自身に帰属するように、ユーザー情報を設定します

```bash
git config --global user.name "あなたの名前"
git config --global user.email "you@example.com"
```

設定を確認します

```bash
git config --list
```

## リポジトリのクローン

このリポジトリのローカルコピーを取得するには、以下を実行します

```bash
ghq get https://github.com/sforzando/etude-github.git
cd [ghq.root]/github.com/sforzando/etude-github
```

## 演習

1. このリポジトリをクローンします。
2. VS Codeで開いてください。
3. `docs/` フォルダの内容を確認してください。
4. [Gitの基礎](02-git-basics.md)に進んでください。
