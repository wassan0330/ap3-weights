# ap3-weights

VRChat ワールドの AP3 無人機が読み込む、学習済み方策の重みの置き場所です。

- `weights.bin` … 全モデルの重みと動作確認用のデータを1つにまとめたファイル(先頭が最新)(ワールドが VRCStringDownloader で読む)
- `catalog.json` … 載っているモデルの一覧(人が見る用)
- `ap35.bin` … AP3.5(型を選ぶ無人機)用。型ごとの重みと動作確認用のデータを1つにまとめたファイル(ワールドの AP3.5 のパネルが読む・読めない時はワールドに内蔵の型で飛ぶ)
- `ap35_catalog.json` … ap35.bin に載っている型の一覧(人が見る用)

形式は書き出し側の `export_bundle.py`(ap35.bin は `export_bundle35.py`)の冒頭に記載。
