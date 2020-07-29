　ipynbファイルをクリックするとJupyter notebook形式のファイルが表示されます。先頭にある「Open in Colab」ボタンを押すと、Google Colab上で実行できます。使用環境は、Google Colab が動作すれば、どんなものでも構いません。
 
 # Transformer_en_run.ipynb\
 Transformerによる英語データのネガポジ判定と判定根拠の可視化を行うコードです。
 ・使用するデータセットはIMDbです。これは、映画のレビュー(英文)から文章を取り出し、それがポジテイブな表現なのか、ネガティブな表現なのかをまとめたものです。 　　
 ・学習後、テスト文章で推論を行い、その文章のどの単語が判断根拠になっているか(Attention)を可視化します。\
 
 # Transformer_ja_run.ipynb\
 Transformerによる日本語データのネガポジ判定と根拠の可視化を行うコードです。
 ・使用するデータセットはchABSA-datasetです。これは、日本の上場企業の有価証券報告書から文章を取り出し、それがポジテイブな表現なのか、ネガティブな表現なのかをまとめたものです。\
 ・学習後、テスト文章で推論を行い、その文章のどの単語が判断根拠になっているか(Attention)を可視化します。\
