# Git Practice

このリポジトリは、Git の基本操作を学ぶための練習用プロジェクトです。

## 目的
- Git の基本的な流れを理解する
- コミット、ブランチ、プッシュ、プルの操作を体験する
- 変更内容を管理する練習を行う

## 構成
- [hello.txt](hello.txt): Git の練習用テキストファイル

## 使い方
1. リポジトリをクローンする
   ```bash
   git clone <repository-url>
   ```
2. 作業用ブランチを作成する
   ```bash
   git checkout -b <branch-name>
   ```
3. ファイルを編集する
4. 変更をステージングする
   ```bash
   git add .
   ```
5. コミットする
   ```bash
   git commit -m "説明"
   ```
6. リモートにプッシュする
   ```bash
   git push origin <branch-name>
   ```

## よく使うコマンド
```bash
git status
git log
git pull
git fetch
git branch
```

## 備考
このプロジェクトはシンプルな構成のため、Git の基本操作を理解するための最小構成として利用できます。
