# 桜丘地区 道路網の簡易シミュレーション

渋谷区 桜丘地区の地区計画（素案）について、道路の配置の違いが経路・混み具合・緊急車両の到達に与える影響を比べた、個人による簡易なシミュレーションの結果ページです。

**区の公式推計ではありません。個人による簡易なシミュレーションで、仮定にもとづく例示です。**

- `index.html`：車の流れ（トップ。補50を整備した場合と素案の比較）
- `routes.html`：経路の比較
- `dashboard.html`：結果のまとめ
- `emergency.html`：緊急車両の到達

## データとライセンス

- 道路網のデータ（`data/net.js` ほか、道路網から計算した `data/*.js`）は OpenStreetMap のデータを加工したものです。© OpenStreetMap contributors。これらのデータには Open Database License（ODbL 1.0）が適用されます：https://opendatacommons.org/licenses/odbl/1-0/
- 背景地図：国土地理院タイル・ベクトルタイル
- 地図表示：MapLibre GL JS（BSD-3-Clause、`vendor/LICENSE-maplibre.txt`）
