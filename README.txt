# 模擬試験タイマー（PWA）

## 使い方
1. このフォルダのファイルを GitHub リポジトリへアップロード（`index.html`, `sw.js`, `manifest.webmanifest`, `icon-192.png`, `icon-512.png`）
2. GitHub: Settings → Pages → Source: Deploy from a branch / Branch: main / (root)
3. 公開URLにアクセス。iOS/iPad は最初の再生時に画面のタップが必要な場合があります。

## オフライン（PWA）
- 初回アクセス時に Service Worker がキャッシュします。2回目以降はオフラインでも起動可能。
- アイコンは `icon-192.png` / `icon-512.png` を差し替えてください。
