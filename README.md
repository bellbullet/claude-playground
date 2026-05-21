# Claude Playground

Claudeのアーティファクト（HTML / React / Mermaid）をペーストしてその場で実行できるプレイグラウンド環境です。

## 対応形式

|形式             |説明                                |
|---------------|----------------------------------|
|HTML / CSS / JS|そのまま実行                            |
|React (JSX)    |Babel + React 18 をCDN経由でトランスパイル・実行|
|Mermaid        |Mermaid.jsで図を描画                   |

## 使い方

1. コードエリアにClaudeのアーティファクトコードをペースト
1. 種別は自動判定（手動切替も可能）
1. **実行** ボタン or `Ctrl+Enter` で実行

## 内蔵ライブラリ

- React 18 / ReactDOM
- Babel Standalone（JSXトランスパイル）
- Tailwind CSS
- Recharts
- D3.js
- Lucide Icons
- mathjs
- lodash
- `window.storage` ポリフィル（Claude artifact互換）

## デプロイ

Vercel に接続するだけで静的サイトとして公開できます。