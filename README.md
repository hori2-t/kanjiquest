# kanjiquest

カンジクエスト (KanjiQuest) iOS アプリの公式サイト。

漢検 3〜10 級対応の児童・小中学生向け漢字学習アプリ。10 種類のレッスン形式と SRS 復習で楽しく続けられる。

## URL

- トップページ: https://hori2-t.github.io/kanjiquest/
- プライバシーポリシー: https://hori2-t.github.io/kanjiquest/privacy.html
- 利用規約: https://hori2-t.github.io/kanjiquest/terms.html

## ファイル構成

- `index.html` — トップページ（機能紹介・App Store リンク・法務ページへの導線）
- `privacy.html` — プライバシーポリシー（児童向けアプリ・TFCD 広告・IAP 対応）
- `terms.html` — 利用規約（買い切り IAP・準拠法）
- `app-ads.txt` — AdMob 認証ファイル
- `assets/` — アイコン画像（後で本番アイコンを差し替え）

## デプロイ

GitHub Pages (Settings → Pages → main branch / root) で配信。

```bash
git push origin main
# Settings → Pages → Source: main / root → Save
```

更新時は HTML ファイル内の「最終更新日」も忘れずに更新する。

## TODO

- [ ] `assets/icon-256.png` / `assets/icon-512.png` を本番アイコンに差し替え
- [ ] `index.html` 内の App Store リンク `id0000000000` を実 App ID に置換
- [ ] App Store 公開後、`index.html` ヒーローの `Coming Soon` / `準備中` 表記を削除

## ライセンス

本リポジトリは公開ドキュメントのみを含みます。アプリ本体のソースコードは含まれません。
