# 旅ログ Ver.0.8 — GitHub Pages 実地図テスト

- `index.html` だけで動く静的なサンプルです。
- MapLibre GL JS（CDN）と OpenFreeMap の地図スタイルを使用します。Google API キー・請求先登録は不要です。
- 池袋周辺のサンプル座標を結んだ**架空ルート**です。実際の道路・線路との一致や交通手段の判定は未実装です。
- 位置情報、写真、実際の移動履歴は取得・保存しません。

## GitHub Pages で公開

1. GitHub でテスト用の**公開**リポジトリを新規作成。
2. `index.html` をリポジトリのルートにアップロードしてコミット。
3. Settings → Pages → Build and deployment → Deploy from a branch → `main` / `/(root)` → Save。
4. 数分後、表示された Pages URL を iPhone の Safari で開きます。

※ Pages の公開サイトに個人の写真や移動履歴をアップロードしないでください。

## 外部通信

- `https://unpkg.com/` — MapLibre の JS / CSS
- `https://tiles.openfreemap.org/` — 地図スタイル・地図データ

地図表示には通信が必要です。無料の外部サービスは提供条件や利用制限が変更される可能性があります。
