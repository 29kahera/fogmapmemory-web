# Fog Map Memory — Official Website

公式サイト / GitHub Pages でホストする静的サイト。

## 構成

```
fogmapmemory-web/
├── index.html      ← トップ（LP）
├── privacy.html    ← プライバシーポリシー
├── terms.html      ← 利用規約
├── css/
│   └── style.css
└── images/
    ├── favicon.png      ← TODO: 作成
    ├── og-image.png     ← TODO: 作成（1200×630px）
    └── screenshot-*.png ← TODO: アプリリリース後に追加
```

## GitHub Pages 公開手順

1. このフォルダを GitHub にリポジトリとして push する
2. Settings → Pages → Source: `main` branch / `/ (root)`
3. 公開URL: `https://[username].github.io/fogmapmemory-web/`

## リリース後に差し替えが必要な箇所

| ファイル | 箇所 | 内容 |
|---------|------|------|
| index.html | `href="#"` の App Store バッジ | App Store URL に変更 |
| index.html / footer | `YOUR_EMAIL@example.com` | 実際のメールアドレス |
| privacy.html | 同上 | 同上 |
| terms.html | 同上 | 同上 |
| index.html | OGP の `og:url` | 実際のURL |
| images/ | favicon.png / og-image.png | 実際のアセット |

## ブランドカラー

| 名前 | HEX |
|------|-----|
| Primary Green | `#2D8B55` |
| Forest Dark | `#1A5C35` |
| Treasure Gold | `#FFD700` |
| BG Dark | `#0D1B14` |
# fogmapmemory-web
