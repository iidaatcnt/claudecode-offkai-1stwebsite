# First WEB 問診チェック

Claude Code（クロコ）デスクトップ版インストール済みの方を対象に、
はじめてのWebサイト公開オフ会の事前確認を行う問診Webアプリです。

## 概要

- **対象**：Claude Code インストール済みで、初めてWebサイトを公開したい方
- **目的**：オフ会当日にスムーズにWebサイト公開できるよう事前に環境・スキルを確認する

## 当日のゴール

1. ChatGPT でサイトのデザイン画像を生成
2. Claude Code にその画像を渡してHTML/CSSをコーディング
3. Cloudflare Pages にデプロイ → スマホでも見られるURLで公開

## 設問構成

| No | 内容 |
|---|---|
| Q1 | Claude Code でチャットができているか（前提確認） |
| Q2 | Mac / Windows の選択 |
| Q3 | OSバージョン確認（Claude Code動作確認） |
| Q4 | ChatGPTアカウントの有無 |
| Q5 | Cloudflareアカウントの有無 |
| Q6 | 作りたいサイトのジャンル |
| Q7 | ファイル操作スキル確認 |
| Q8 | スクリーンショットが撮れるか |
| Q9 | Claude Code への画像添付チャット経験 |

## ボタン色のルール

- **緑**：準備OK・推奨の選択肢
- **オレンジ**：要確認・事前準備が必要な選択肢

## デザイン

- ベースカラー：Claude Code オレンジ（`#DA7756`）
- スマートフォン対応（480px以下でボタン縦並び）
- 単一ファイル構成（`index.html`）・外部依存なし

## デプロイ先

- **Cloudflare Pages**：`claudecode-offkai-1stwebsite.miidacnt.workers.dev`
- GitHub への push で自動デプロイ
