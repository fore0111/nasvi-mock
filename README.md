# NAsVI マップ（モック）

技大祭の立体マップと、AR ガイドへの目的地の引き渡しを試すモック。

- `index.html`：地図画面（検索窓・立体マップ・タブ）。企画を選ぶと経路と距離を表示
- `ar.html`：AR ガイド。`ar.html?dest=<企画場所の id>&ev=<企画の番号>` で目的地を指定して起動
- `data/`：建物形状（© OpenStreetMap contributors）と企画データ

このリポジトリは公開用の出力先。編集は `ar-guide` 側（`mock/index.html`、`index.html`、`data/`）で行い、`sh mock/deploy.sh` で反映する。
