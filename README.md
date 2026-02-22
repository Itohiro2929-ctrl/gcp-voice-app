# Cloud Text-to-Speech 音声出力アプリ

Google Cloud Text-to-Speech API と Streamlit を使用して作成した、テキストデータを音声ファイル（MP3）に変換するWebアプリケーションです。

## 主な機能

* **テキスト入力**: テキストエリアへの直接入力、またはテキストファイル（`.txt`）のアップロードに対応しています。
* **言語選択**: 日本語（ja-JP）と英語（en-US）から選択可能です。
* **話者の性別選択**: default, male, female, neutral の4種類から音声のトーンを選択できます。
* **音声の再生**: 生成された音声をブラウザ上で直接再生・確認できます。

## 動作環境・事前準備

このアプリをローカル環境で動かすには、以下の準備が必要です。

1. Python 3.x のインストール
2. Google Cloud  アカウント
3. Google Cloudプロジェクトでの **Cloud Text-to-Speech API** の有効化
4. サービスアカウントの秘密鍵（JSONファイル）の取得

## セットアップ手順

### 1. リポジトリのクローン
```bash
git clone https://github.com/あなたのユーザー名/リポジトリ名.git
cd リポジトリ名