# github-actions

## GitHub CLIの認証

GitHub CLIを利用するためには、下記のコマンドで認証を行う必要があります：

```
gh auth login
```

## GitHub CLIによる実行確認

GitHub CLIを使用すると、ターミナルからGitHub Actionsのワークフローの実行状況を簡単に確認できます。

- ワークフローの実行状況をリアルタイムで監視

```bash
gh run watch
```

- 特定のワークフロー実行の詳細情報を表示

```bash
gh run view
```

- 手動でワークフローを実行

```bash
gh workflow run manual.yml -f greeting=goodbye
```
