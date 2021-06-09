# Memo

# TILの書き方

- リポジトリを作ります
- コンテンツを作ります

## Git メモ

### git add .
- Gitの保存対象とする。ディレクトリ内の全てのファイル・ディレクトリを対象。

### git commit -m　”コメント”
- コミット（保存）。”コメント”でコミット内容をメモ。

### git status
- 前回のコミットとの差分を表示する。

### git diff
- 前回のコミットとの差分を比較する

### git log  /  git log --oneline
- コミットの履歴の確認。 --oneline で一行で表示。
- git reset --hard と組み合わせて、過去のコミットまで戻る。

### git restore sample.rb
- 最新のコミットの状態に戻る。


### git remote add origin URL
- 先にGitHubでリモートリポジトリーを作成し、紐付ける。

### git push origin HEAD
- プッシュ。ローカルからリモートに共有する。

### git clone URL
- リモートリポジトリからクローン（コピー）を作成する。

### git branch
- 現在のブランチ状況の確認。

### git branch -c feature/git-name
- ブランチを切る。ブランチの変更。

### コミットメッセージの変更方法
- https://qiita.com/kenose0328/items/185f7e8634d816c85a84
