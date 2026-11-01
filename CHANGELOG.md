# Changelog

## 2026-11-01

- 開発用 Miniflare の Undici を 7.30.1 に限定固定し、過剰な Content-Encoding による DoS（GHSA-xjj6-f33q-929c）へ対応しました。Wrangler・エディター本体・保存形式は変更していません。

## 2026-10-22

- 開発・配備用 Wrangler を 4.147.0 に更新し、Node.js 22 以上の実行要件を明記しました。エディター本体と保存済みデータの形式は変更していません。
- 配備ツールの間接依存 sharp を 0.35.5 に固定し、GHSA-wq5f-xc86-pv6w を修正しました。
