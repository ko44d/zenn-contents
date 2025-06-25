# zenn-contents

このリポジトリは、Zenn CLIを活用して記事や本を管理するためのプロジェクトです。

## プロジェクト概要
- Zenn CLIを使用して、技術記事や書籍の執筆・公開を行います。
- Git管理により、バージョン管理と共同編集が可能です。

## ディレクトリ構成（例）
```
/articles        # 記事ファイル（Markdown）
/books           # 本のセクションごとのMarkdownファイル
zenn.json        # Zenn用設定ファイル
```
 
## 使用方法
1. Zenn CLIのインストール  
   [Zenn CLIをインストールする](https://zenn.dev/zenn/articles/install-zenn-cli)

2. プロジェクト初期化・設定  
   ```
   zenn init
   ```

3. 記事・本の作成  
   ```
   zenn new:article
   zenn new:book
   ```

4. ローカルプレビュー  
   ```
   zenn preview
   ```

## 参考リンク
- [Zenn CLIで記事・本を管理する方法](https://zenn.dev/zenn/articles/zenn-cli-guide)
