# ap3-weights

VRChat ワールドの AP3 無人機が読み込む、学習済み方策の重みの置き場所です。

- `weights.bin` … 全版の重み・照合データを1つにまとめたファイル(ワールドが VRCStringDownloader で読む)
- `catalog.json` … 載っている版の一覧(人が見る用)

形式は書き出し側の `export_bundle.py` の冒頭に記載。
