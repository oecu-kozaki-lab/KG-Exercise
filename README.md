# KG-Exercise

知識グラフ構築・SPARQL演習用教材（大阪電気通信大学 古崎研究室）。

## 利用方法

1. `index.html` を開く。
2. TSV2KG-EditorでKGを構築し、Turtle形式で保存する。
3. `tools/rdf-sparql.html` でRDFを読み込み、SPARQLを実行する。
4. `sparql/MiniKG-Ex.html` の例を試し、自分のKGに応用する。

## ファイル

- `tools/rdf-sparql.html`: 簡易RDF-DB v4.1（既存ファイルを収録。表示名のみスライドに合わせて「簡易RDF-DB v4.1」に変更）。
- `samples/sample.ttl`: 動作確認用サンプル。
- `samples/MiniKG.tsv`, `MiniKG.ttl`, `MiniKG.svg`（グラフ図）: 共通演習用。知識9件、RDF全22件。IRIは教材用に割り当てたもの。
- `sparql/MiniKG-Ex.html`: 7種類のクエリ例（スライドSPARQL①〜⑥に対応。例7は名前表示版7bあり）。
- `materials/`: 配布資料用（未収録）。

## スライドとの対応

| スライド | サイト |
|---|---|
| 演習①・② KG構築・RDF変換 | STEP 1（TSV2KG-Editor） |
| 演習③ 簡易RDF-DBの操作 | STEP 2（簡易RDF-DB v4.1）＋ STEP 3のMiniKG.ttl |
| 演習③ MiniKGで検索 | STEP 3（クエリ例1〜7） |
| 演習③ 自分のKGに対する検索 | STEP 2で学籍番号_KG.ttlを読み込む |
| SPARQL① | 例1・例2 |
| SPARQL②〜④ | 例3〜例5 |
| SPARQL⑤ 名前から検索 | 例6 |
| SPARQL⑥ 同じ研究室 | 例7（名前表示版は例7b） |
| 発展C | STEP 3 SPARQLサンプル集（発展編） |

提出先（共有Googleスライド／ドキュメント）は授業内で案内する。

## GitHub Pages

Settings → Pages → Deploy from a branch → main / (root) を選択（ブランチ名は実際の設定に合わせる）。
外部CDNからJavaScriptライブラリを読み込むためインターネット接続が必要。RDF検索はブラウザ内で実行する。
