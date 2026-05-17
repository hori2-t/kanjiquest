# assets

アイコン画像のプレースホルダディレクトリ。

## TODO

- `icon-256.png` (256x256, アイコンファビコン用)
- `icon-512.png` (512x512, OGP / Twitter Card 用)

本番アプリアイコンが確定したら、以下のサイズで書き出して配置:

| ファイル名 | サイズ | 用途 |
|------------|--------|------|
| `icon-256.png` | 256×256 | `<link rel="icon">`, `apple-touch-icon` |
| `icon-512.png` | 512×512 | OGP, Twitter Card |

差し替え後、`index.html` `privacy.html` `terms.html` の `<link rel="icon">` 参照に問題がないかブラウザで確認すること。
