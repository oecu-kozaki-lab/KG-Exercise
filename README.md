# KG-Exercise

知識グラフ構築・SPARQL演習用教材（大阪電気通信大学 古崎研究室）。

## 利用方法

1. `index.html` を開く。
2. TSV2KG-EditorでKGを構築し、Turtle形式で保存する。
3. `tools/rdf-sparql.html` でRDFを読み込み、SPARQLを実行する。
4. `sparql/MiniKG-Ex.html` の例を試し、自分のKGに応用する。

## ファイル

- `tools/rdf-sparql.html`: 簡易RDF-DB v4.1（既存ファイルを変更せず収録）。
- `samples/sample.ttl`: 動作確認用サンプル。
- `samples/MiniKG.tsv`, `MiniKG.ttl`: 共通演習用。知識9件、RDF全22件。IRIは教材用に割り当てたもの。
- `sparql/MiniKG-Ex.html`: 7種類のクエリ例。
- `materials/`: 配布資料用（未収録）。

## GitHub Pages

Settings → Pages → Deploy from a branch → main / (root) を選択（ブランチ名は実際の設定に合わせる）。
外部CDNからJavaScriptライブラリを読み込むためインターネット接続が必要。RDF検索はブラウザ内で実行する。
