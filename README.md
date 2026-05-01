# DISC別口ぐせ診断 v2

## ファイル構成

```
disc-gukuse-pwa4/          ← GitHubリポジトリ名（例）
├── index.html             ← メインアプリ
├── manifest.json          ← PWA設定
├── images/
│   ├── profile.jpg        ← 講師プロフィール写真（1D9A9461.jpg）
│   └── qr.webp            ← QRコード画像（preview.webp）
└── icons/                 ← PWAアイコン（任意）
    ├── icon-192.png
    └── icon-512.png
```

## GitHub Pages デプロイ手順

### 1. 新しいリポジトリを作成
- GitHubで新リポジトリ作成
- 例：`disc-gukuse-pwa4`

### 2. ファイルをアップロード
以下のファイルをすべてアップロード：
- `index.html`
- `manifest.json`
- `images/profile.jpg`（プロフィール写真）
- `images/qr.webp`（QRコード）

### 3. GitHub Pages を有効化
- Settings → Pages → Source: `main` ブランチ → Save

### 4. アクセス
- URL: `https://kuchiguseh.github.io/disc-gukuse-pwa4/`

## 画像ファイルの準備

| ファイル名 | 内容 | 保存先 |
|-----------|------|--------|
| 1D9A9461.jpg | 講師写真 | `images/profile.jpg` として保存 |
| preview.webp | QRコード | `images/qr.webp` として保存 |

## PDF出力方法

1. 診断を完了してレポート画面を開く
2. 「🖨️ PDFで保存する」ボタンをクリック
3. ブラウザの印刷画面で「PDFに保存」を選択
4. 用紙サイズ：A4、余白：最小を推奨
