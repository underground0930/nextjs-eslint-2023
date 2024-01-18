# [2023 年]Next.js + eslint 周りの設定

## 解説記事

https://zenn.dev/resistance_gowy/articles/91b4f62b9f48ec


## 更新履歴

- 2024/01/18 : モジュールをアップデート

## 自分のリポジトリで使用する


```
mkdir `自分で設定したいディレクトリ作成`
cd `自分で設定したいディレクトリ作成`

# カレントディレクトリにcloneする
git clone git@github.com:underground0930/nextjs-eslint-2023.git .

# 既存のリポジトリ情報を削除
rm -rf .git

# 新しいリポジトリを初期化
git init

# リモートのリポジトリと「origin」という名前を紐付け
git remote add origin [新しいリポジトリのURL]

# addからpushまで行う
git add .
git commit -m "Initial commit"
git push -u origin main

```
