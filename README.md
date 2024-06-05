# git_command_list
**勉強中のアウトプットのため誤りがある可能性があります。**

## Gitでの大まかな流れ
- コマンドラインで新しいリポジトリを作成する
1. 作業ディレクトリにGitを使う宣言をする
2. ステージングエリアにあげる
3. ローカルリポジトリに変更を記録する
4. どのブランチに上げるか設定する
5. GitHubのリポジトリとローカルのGitを紐づける
6. ローカルリポジトリ()Gitにあげたものをリモートリポジトリ(GitHub)にあげる
```bash
git init
git add README.md
git commit -m "{コメント}"
git branch -M main
git remote add origin https://github.com/{ユーザ名}/{リポジトリ名}.git
git push -u origin main
```
- コマンドラインから既存のリポジトリをプッシュする
```bash
git remote add origin https://github.com/{ユーザ名}/{リポジトリ名}.git
git branch -M main
git push -u origin main
```

## 作業ディレクトリにGitを使う宣言をする
```bash
git init
```

## ステージングエリアにあげる
- すべてのファイル
```bash
git add .
```
- 任意のファイル
```bash
git add {ファイル名}
```

## ローカルリポジトリに変更を記録する(コミット)
```bash
git commit "{コメント}"
```
