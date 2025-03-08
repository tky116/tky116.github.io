# tky116.github.io

## 概要
このリポジトリは、GitHubPages上で公開されているポートフォリオサイトです。
Hugoフレームワークを使用して構築しており、プロジェクト、スキル、経歴などを紹介しています。

## 技術スタック
- Windows 11
- Go（1.24.1）
- [Hugo](https://gohugo.io/) - 静的サイトジェネレーター
- [Hugo Blox](https://hugoblox.com/)の[Academic CV](https://github.com/HugoBlox/theme-academic-cv.git) - テーマ
- GitHub Actions - CI/CD
- GitHub Pages - ホスティング

## 環境構築
### ローカル開発環境のセットアップ
1. リポジトリをクローン
   ```bash
   git clone https://github.com/tky116/tky116.github.io.git
   cd tky116.github.io

### Hogo導入
v0.137.1(hugo_extended_0.137.1_windows-amd64.zip)をインストールしました。

以下から入手。
[https://github.com/gohugoio/hugo/releases/tag/v0.137.1](https://github.com/gohugoio/hugo/releases/tag/v0.137.1)

### サイトのプレビュー
以下のコマンドでローカル起動をさせる。
```bash
hugo server
```
ブラウザで http://localhost:1313 にアクセスすれば、プレビューできる。
